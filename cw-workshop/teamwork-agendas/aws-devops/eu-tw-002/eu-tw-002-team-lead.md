<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-2)</strong></span>

![logo](teamwork_logo.png)

<br>
<br>
<br>
<br>
<br>
<br>

<h1><strong><span style="color: #3498DB;">Meeting Agenda</strong></h1></span>

<span class="c16 c30">▶ </span><span
class="c42 c82">Icebreaking</span><span class="c16 c23"> </span>

<span class="c16 c30">▶ </span><span
class="c42 c82">Questions</span><span class="c46 c42 c48"> </span>

<span class="c16 c30">▶ </span><span
class="c46 c48 c42">Interview/Certification Questions</span>

<span class="c30">▶ </span><span class="c46 c48 c42">Coding Challenge
</span>

<span class="c16 c30">▶ </span><span class="c23 c16">Video of the
week</span>

<span class="c16 c30">▶ </span><span class="c23 c16">Retro
meeting</span>


<span class="c30">▶ </span><span class="c46 c48 c42">Case study /
project</span>

<br>
<br>
<br>

<h1><strong><span style="color: #3498DB;">Teamwork Schedule</strong></h1></span>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ice-breaking</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

- Personal Questions (Stay at home & Corona, Study Environment, Kids etc.) 
- Any challenges (Classes, Coding, AWS, studying, etc.) 
- Ask how they’re studying, give personal advice. 
- Remind that practice makes perfect. 

<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Team work</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

- Ask what exactly each student does for the team, if they know each other, if they care for each other, if they follow and talk with each other etc. 


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ask Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>15m</p><td>                </tr>
</table>

**1. In On-Demand  instance model, each virtual machine has an ........... price.**

<strong>A.</strong> Yearly  <br>
<strong>B.</strong> Weekly   <br>
<strong>C.</strong> Hourly <br> 
<strong>D.</strong> Monthly  <br>

 
**Answer:** *C*

<br>

**2. Encapsulation is the process of taking data from one protocol and translating it into another protocol, so the data can continue across a network.**

<strong>A.</strong> True  <br>
<strong>B.</strong> False   <br>

**Answer:** *A*

<br>


**3. Which command is used for modifying a user's properties?**

<strong>A.</strong> who am i  <br>
<strong>B.</strong> sudo su   <br>
<strong>C.</strong> usermod <br> 
<strong>D.</strong> groupadd  <br>

**Answer:** *C*


<br>


**4. The network address of 172.16.0.0/19 provides how many subnets and hosts?**

<strong>A.</strong> 7 subnets, 30 hosts each  <br>
<strong>B.</strong> 8 subnets, 8.190 hosts each  <br>
<strong>C.</strong> 8 subnets, 2.046 hosts each <br> 
<strong>D.</strong> 7 subnets, 2.046 hosts each  <br>

**Answer:** *B*


<br>

**5. What is the default subnet mask for a Class B address?**

<strong>A.</strong> 255.0.0.0 <br>
<strong>B.</strong> 255.255.0.0 <br>
<strong>C.</strong> 255.255.255.0 <br> 
<strong>D.</strong> 255.255.255.255  <br>

**Answer:** *B*
<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. Which of the following can be used to manage identities in AWS.**

<strong>A.</strong> AWS Config <br>
<strong>B.</strong> AWS IAM <br>
<strong>C.</strong> AWS Trusted Advisor <br> 
<strong>D.</strong> AWS CloudFormation <br>

**Answer:** *B*

*AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.<br>
For more information on AWS IAM, please refer to the* [Link](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

<br>

**2. You have an application developed in .NET. This applications works with the S3 buckets in a particular region. The application is hosted on an EC2 Instance. Which of the following should ideally be used to ensure that the EC2 Instance has the appropriate access to the S3 buckets?**

<strong>A.</strong> AWS Users <br>
<strong>B.</strong> AWS Groups <br>
<strong>C.</strong> AWS IAM Roles<br> 
<strong>D.</strong> AWS IAM Policies<br>

**Answer:** *C* <br>

*The AWS Documentation mentions the following:*<br>
*You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources.
For more information on IAM Roles, please refer to the* [Link](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)

*Groups are collections of Users which will not be appropriate for the EC2 Instance so A and B are incorrect.The creation of a new policy cannot ensure appropriate access. They must be attached to a User, Group or Role. Therefore D is incorrect.*


<br>

**3. What happens when one of the resources in a stack cannot be created successfully? (CloudFormation)**

**Answer:** <br>

*By default, the “automatic rollback on error” feature is enabled. This will cause all AWS resources that AWS CloudFormation created successfully for a stack up to the point where an error occurred to be deleted. This is useful when, for example, you accidentally exceed your default limit of Elastic IP addresses, or you don’t have access to an EC2 AMI you’re trying to run. This feature enables you to rely on the fact that stacks are either fully created, or not at all, which simplifies system administration and layered solutions built on top of AWS CloudFormation.*

<br>





**4. A company has a set of EC2 Instances that store critical data on EBS Volumes. There is a fear from IT Supervisors that if data on the EBS Volumes is lost, then it could result in a lot of effort to recover the data from other sources. Which of the following would help alleviate this concern in an economical way?**

<strong>A.</strong> Take regular EBS Snapshots <br>
<strong>B.</strong> Enable EBS Volume encryption <br>
<strong>C.</strong> Create a script to copy data to an EC2 Instance Store <br> 
<strong>D.</strong> Mirror data across 2 EBS Volumes <br>

**Answer:** *A*

*Option B is incorrect because it does not help in durability of EBS Volumes.*<br>
*Option C is incorrect since EC2 Instance stores are not durable.*<br>
*Option D is incorrect since mirroring data across EBS Volumes is inefficient when you already have an option for EBS Snapshots.*<br>
*The AWS Documentation mentions the following on AWS EBS Snapshots:
You can back up the data on your Amazon EBS Volumes to Amazon S3 by taking point-in-time snapshots. Snapshots are incremental backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved. This minimizes the time required to create the snapshot and saves on storage costs by not duplicating data. When you delete a snapshot, only the data unique to that snapshot is removed. Each snapshot contains all of the information needed to restore your data (from the moment when the snapshot was taken) to a new EBS volume.* <br>
*For more information on AWS EBS Snapshots, please visit the* [Link](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)



<br><br><br><br>

**5. A new department has recently joined the organization and the administrator needs to compose access permissions for the group of users. Given that they have varying roles and access needs, what is the best-practice approach when granting access?**

<strong>A.</strong> After gathering information on their access needs, the administrator should allow every user to access the most common resources and privileges on the system. <br>
<strong>B.</strong> The administrator should grant all users the same permissions and then grant more upon request.  <br>
<strong>C.</strong> The administrator should grant all users the least privilege and add more privileges to only to those who need it. <br>
<strong>D.</strong> Users should have no access and be granted temporary access on the occasions that they need to execute a task.



**Answer:** *C* <br>

*The best-practice for AWS Identity Access Management (IAM) is to grant the least amount of permissions on the system, enough to only execute the required tasks of the user’s role. Additional permissions can be granted per user in accordance to the tasks they wish to perform on the system.*  [Link](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege)

*Option A. is incorrect because granting users access to the most common resources presents security vulnerabilities, especially from those who have access to resources they do not need.*<br>
*Option B. is incorrect because granting users the same privileges on the system means other users might get access to resources they do not need to carry out their job functions. This presents a security risk.*<br>
*Option D. is incorrect because the users are part of the organisation, it will be cumbersome for the administrator to constantly create temporal access passes for internal staff.*


<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Introduction to YAML](https://www.youtube.com/watch?v=o9pT9cWzbnI)


<br>

<table style= "width:97%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Retro Meeting on a personal and team level</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

Ask the questions below:

- What went well? 
- What could be improved? 
- What will we commit to do better in the next week? 

<br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- [Coding Challenge: Convert Milliseconds into Hours, Minutes, and Seconds](https://github.com/clarusway/cw-workshop/tree/dev/python/coding-challenges/cc-002-convert-millisecs-to-hours-mins-secs) 

<br>

We assume that each group has two sub teams. Each week, one of the sub-teams will present their solution.



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Case study/Project</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


**Case study should be explained to the students during the weekly meeting and has to be completed in one sprint (2 weeks) by the students. Students should work in small teams to complete the case study.**

- [Project-101 : Kittens Carousel Static Website deployed on AWS EC2 using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-4-20/tree/master/aws/projects/101-kittens-carousel-static-website-ec2)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
