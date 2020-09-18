<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-1)</strong></span>

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

**1. Imagine that you have a local repository, but other team members have pushed changes into the remote repository. What Git operation would you use to download those changes into your working
copy?**

<strong>A.</strong> checkout  <br>
<strong>B.</strong> commit   <br>
<strong>C.</strong> export <br> 
<strong>D.</strong> pull  <br>
<strong>E.</strong> update <br>

 
**Answer:** *D*

<br>

**2. What happens if the .git directory gets deleted?**

**Answer:** 

*The moment you create a repository, you will find a .git directory present inside it. This .git directory
contains all the metadata of the repository and maintains a track of all the changes made to the files in your repository, by keeping a commit history.*

*All the information regarding commits, hooks, refs, object databases, remote repository addresses, etc. are kept inside this folder. This is the most crucial part of Git. When you clone any Git repository on your local machine, this .git is the directory that actually gets copied.*

*If the .git/ directory gets deleted, then you will lose track of your project’s history. The repository will no longer be under version control.*


<br>


**3. Which piece of hardware would reduce the size of a broadcast domain?**

<strong>A.</strong> Hub  <br>
<strong>B.</strong> Router   <br>
<strong>C.</strong> Packet injector <br> 
<strong>D.</strong> Switch  <br>

**Answer:** *B*


<br>

**4. What is the purpose of the OSI model?**

<strong>A.</strong> Enable users to access the internet  <br>
<strong>B.</strong> Improve the network performance by compressing data  <br>
<strong>C.</strong> To provide a set of standards for manufacturers <br> 
<strong>D.</strong> Make network devices such as a router, switch, hub communicate with each other  <br>

**Answer:** *C*

<br>


**5. What will be the output?**

`$ find ./GFG -name sample.txt`


<strong>A.</strong> It will search for all files in GFG directory.  <br>
<strong>B.</strong> It will creat a directory named GFG and create sample.txt file in it.   <br>
<strong>C.</strong> It will search for sample.txt in GFG directory. <br> 
<strong>D.</strong> It will search for all files in GFG directory except named sample.txt.  <br>

**Answer:** *C*<br> 



<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. You are planning to serve a web application on the AWS Platform by using EC2 Instances. Which of the below principles would you adopt to ensure that even if some of the EC2 Instances crashes , you still have a working
application.?**

<strong>A.</strong> Using a scalable system  <br>
<strong>B.</strong> Using an elastic system   <br>
<strong>C.</strong> Using a regional system <br> 
<strong>D.</strong> Using a fault tolerant system  <br>

**Answer:** *D*<br>

A fault tolerant system is one that ensures that the entire system works as expected even if there are issues. 
For more information on designing fault tolerant applications in AWS, please refer to: [Link](https://d1.awsstatic.com/whitepapers/aws-building-fault-tolerant-applications.pdf?did=wp_card&trk=wp_card)

<br>

**2. The company you work for is considering migrating to AWS. They are concerned about cost and the initial investment needed. Which of the following features of AWS pricing helps lower the initial investment amount needed? Choose 3 answers from the options given below:**

<strong>A.</strong> The ability to choose the lowest cost vendor <br>
<strong>B.</strong> The ability to pay as you go 
 <br>
<strong>C.</strong> No upfront costs<br> 
<strong>D.</strong> Discounts for upfront payments
<br>

**Answer:** *B, C and D* <br>

A is incorrect. *The ability to choose the lowest cost vendor is not exclusive to AWS over on-premise solutions. The some of the good reasons of moving to the AWS Cloud are:*<br>
- *No upfront costs*  <br>
- *The ability to pay as you go where the customer only pays for the resources needed*

*On-demand EC2 instances offer no upfront costs whereas for the reserved instances they offer a discount for the upfront costs you pay.*


<br>

**3. What can developers now do with AWS CloudFormation that they could not
before?**


**Answer:** 

*AWS CloudFormation automates and simplifies the task of repeatedly and predictably creating groups of related resources that power your applications. Creating and interconnecting all resources your application needs to run is now as simple as
creating a single EC2 or RDS instance.*
   
<br>

**4. I have some private servers on my premises, also I have distributed some of my workload on the public cloud, what is this architecture called?**

<strong>A.</strong> Private Cloud<br>
<strong>B.</strong> Hybrid Cloud <br>
<strong>C.</strong> Public Cloud <br> 
<strong>D.</strong> Virtual Private Cloud <br>

**Answer:** *B*

*This type of architecture would be a hybrid cloud. Because we are using both, the public cloud, and your on premises servers i.e the private cloud.*

<br><br><br><br><br>

**5. A cloud solutions architect needs to execute urgent mission-critical tasks on the  AWS Management console, but has left their Windows-based machine at home. What secure option can be used to administer these tasks on the cloud infrastructure given that only non-graphical user interface (non-GUI), Linux-based machines are readily available?**

<strong>A.</strong> Share the AWS Management console credentials with the person at home over the phone, so they can execute on the cloud solutions architect behalf<br>
<strong>B.</strong> Use third-party remote desktop software to access the Windows-based machine at home from the non-GUI workstations and administer the necessary tasks<br>
<strong>C.</strong> Use Secure Shell (SSH) to securely connect to the Windows-based machine from one of the non-GUI Linux-based machines then log onto the AWS Management console<br>
<strong>D.</strong> Install and run AWS CLI on one of the non-GUI Linux-based machines, in a shell environment such as bash, the cloud solutions architect can access ALL services just as they could from a Windows-based machine.



**Answer:** *D* <br>
AWS Command Line Interface (AWS CLI) is an open source tool that enables access and interaction with AWS services using commands in the command-line shell. With minimal configuration the cloud solutions architect would  start using the functionality equivalent to that provided by the browser-based AWS Management Console from the command prompt in a terminal program such as bash. [Link-1](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html )
<br>
Option A. is INCORRECT because sharing AWS Management console credentials is bad-practice and poses a high security risk. [Link-2](https://aws.amazon.com/iam/details/managing-user-credentials/ )
 <br>
Option B. is INCORRECT accessing the AWS Management console via third-party remote desktop software is insecure since the remote machine can be compromised.<br> Option C. is INCORRECT because it is rather cumbersome in comparison, though secure the option is oblivious of the direct access method of AWS CLI

<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Static vs Dynamic Websites - What's the Difference?](https://www.youtube.com/watch?v=_wFJj94kSTU)


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

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- [Codding Challenge: Convert to Roman Numerals](https://github.com/clarusway/clarusway-aws-devops-4-20/tree/master/python/coding-challenges/cc-001-convert-to-roman-numerals) 

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
