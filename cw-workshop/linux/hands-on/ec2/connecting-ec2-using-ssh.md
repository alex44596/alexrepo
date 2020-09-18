# scenario-how-to-use-ssh
# launch an Amazon Linux 2 EC2 instance 
# login with SSH to EC2 instance
# instal nmap network tool
sudo yum install nmap -y
# show that SSH port is open
```bash
nmap localhost
Starting Nmap 6.40 ( http://nmap.org ) at 2020-06-16 22:27 UTC
Stats: 0:00:00 elapsed; 0 hosts completed (0 up), 1 undergoing Ping Scan
Ping Scan Timing: About 100.00% done; ETC: 22:27 (0:00:00 remaining)
Nmap scan report for localhost (127.0.0.1)
Host is up (0.00028s latency).
Not shown: 997 closed ports
PORT    STATE SERVICE
22/tcp  open  ssh
25/tcp  open  smtp
111/tcp open  rpcbind
```
# show that ssh service is running
```bash
sudo systemctl status sshd
● sshd.service - OpenSSH server daemon
   Loaded: loaded (/usr/lib/systemd/system/sshd.service; enabled; vendor preset: enabled)
   Active: active (running) since Tue 2020-06-16 22:16:15 UTC; 14min ago
     Docs: man:sshd(8)
           man:sshd_config(5)
 Main PID: 3310 (sshd)
   CGroup: /system.slice/sshd.service
           └─3310 /usr/sbin/sshd -D
```
# back up the current version of this file before editing: /etc/ssh/sshd_config
```bash
sudo cp /etc/ssh/sshd_config{,.bak}
```
# show the content of the configuration /etc/ssh/sshd_config
```bash
sudo cat /etc/ssh/sshd_config | less
```
# Open the configuration file for editing

```bash
sudo vim /etc/ssh/sshd_config
```
```bash
# The strategy used for options in the default sshd_config shipped with
# OpenSSH is to specify options with their default value where
# possible, but leave them commented.  Uncommented options override the
# default value.

# If you want to change the port on a SELinux system, you have to tell
# SELinux about this change.
# semanage port -a -t ssh_port_t -p tcp #PORTNUMBER
#
#Port 22
#AddressFamily any
#ListenAddress 0.0.0.0
#ListenAddress ::

HostKey /etc/ssh/ssh_host_rsa_key
#HostKey /etc/ssh/ssh_host_dsa_key
HostKey /etc/ssh/ssh_host_ecdsa_key
HostKey /etc/ssh/ssh_host_ed25519_key

# Ciphers and keying
#RekeyLimit default none
```

# Uncomment the login grace time and change the value
```bash
LoginGraceTime 110
```

# Allow user to view remote system's graphical user interface on the localhost by enabling display offset

```bash
X11Forwarding yes
X11DisplayOffset 10
```
**This option must be enabled on the server and given with the SSH client during connection with the **-X** option**

Exit and reconnect to server to apply changes you made in the sshd server

```bash
W12: Warning: File "/etc/ssh/sshd_config" has changed and the buffer was changed in Vim as well
```
see the warning about the change

# Generate key for your local computer

```bash
ssh-keygen -t rsa
```
**Out would be like**
```bash
Generating public/private rsa key pair.
Your identification has been saved in /home/ec2-user/.ssh/id_rsa.
Your public key has been saved in /home/ec2-user/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:nTNTVF+RxNLJ4+jPyvDKO4JfZ****************************
The key's randomart image is:
+---[RSA 2048]----+
|            *****|
|           ******|
|           ******|
|         . ******|
|        *********|
|           ******|
|        ******** |
|       . .=.= .o |
|        ...+++.  |
+----[SHA256]-----+
```
As you can see with the output message your public and private rsa key is generated

# Now check the permissions for these generated files. First you need to go to the location where it saved the key files. You can find it under ssh folder

```bash
cd ~/.ssh
```
**To check the permissions list all the files 

```bash
ls -l
```
Output

```bash
-rw-r--r-- 1 demo demo  807 Sep  9 22:15 authorized_keys
-rw------- 1 demo demo 1679 Sep  9 23:13 id_rsa
-rw-r--r-- 1 demo demo  396 Sep  9 23:13 id_rsa.pub
```
** See the difference for the id_rsa.**

# Exit from the server. Try to check if your SSH port is open just using one command.

```bash
ssh -i \Users\kullanici.pem ec2-user@ec2.111.222.333.amazonaws.com nmap localhost
```
Output
```bash
Starting Nmap 6.40 ( http://nmap.org ) at 2020-06-22 09:07 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.00025s latency).
Not shown: 997 closed ports
PORT    STATE SERVICE
22/tcp  open  ssh
25/tcp  open  smtp
111/tcp open  rpcbind

Nmap done: 1 IP address (1 host up) scanned in 0.06 seconds
```

# Disable password-only authentication. But you proceed make sure that you installed a public key to your server. **Otherwise you will be locked**

Open the configuration file. 

```bash
sudo vim /etc/ssh/sshd_config
```
Uncomment password authentication and make it no to make it not required.

```bash
PasswordAuthentication no
```

Uncomment the public key authentication if commented and make it yes since it will be required. Let it not challange the response authentication by changing no if it is yes

```bash
PubkeyAuthentication yes
ChallengeResponseAuthentication no
```

Save and exit.

Reload the SSH deamon.

```bash
sudo systemctl restart ssh
## CentOS/RHEL/Fedora (older version) Linux server reload sshd ##
sudo service sshd reload
 
## CentOS/RHEL/Fedora (latest version i.e. systemd based) Linux server reload sshd ##
sudo systemctl reload sshd 
 
## Debian/Ubuntu Linux (older version) server reload sshd ##
sudo /etc/init.d/ssh reload
 
## Debian/Ubuntu Linux (systemd based latest) server reload sshd ##
sudo systemctl reload ssh 
 
## Generic Unix method to reload sshd ##
sudo kill -HUP `cat /var/run/sshd.pid`
OR
sudo kill -HUP $(cat /var/run/sshd.pid)
```

```bash
sudo systemctl status sshd
```
You can check the status one more time to see it is running.

```bash
  Loaded: loaded (/usr/lib/systemd/system/sshd.service; enabled; vendor preset: enabled)
   Active: active (running) since Mon 2020-06-22 09:16:58 UTC; 2min 46s ago
     Docs: man:sshd(8)
           man:sshd_config(5)
  Process: 30087 ExecReload=/bin/kill -HUP $MAINPID (code=exited, status=0/SUCCESS)
 Main PID: 30080 (sshd)
   CGroup: /system.slice/sshd.service
           ├─30080 /usr/sbin/sshd -D
           ├─30089 sshd: [accepted]
           └─30090 sshd: [net]
```
**Password authentication should now be disabled, and your server should be accessible only through SSH key authentication.**

