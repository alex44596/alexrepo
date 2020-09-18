<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-3)</strong></span>

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

**1. Which GIT command creates and changes to new branch?**

<strong>A.</strong> git branch "branch name"  <br>
<strong>B.</strong> git checkout "branch name"   <br>
<strong>C.</strong> git checkout -b "branch name" <br> 
<strong>D.</strong> git branch -r  <br>

 
**Answer:** *C*

<br>

**2. Which Linux command gives the number of lines, words and characters in the data?**

<strong>A.</strong> cat  <br>
<strong>B.</strong> wc  <br>
<strong>C.</strong> tee <br> 
<strong>D.</strong> tr  <br>

**Answer:** *B*

<br>


**3. By default, sort command reorders lines in ASCII collating sequence.**

<strong>A.</strong> True  <br>
<strong>B.</strong> False   <br>


**Answer:** *A*

*By default, sort reorders lines in ASCII collating sequence i.e. whitespaces first, then numerals, uppercase letters and at last lowercase letters. But we can change this default sorting sequence using a certain sequence.*

<br>


**4. This command sends a request out and expects a response, indicating that both hosts are communicating.**

<strong>A.</strong> tracert  <br>
<strong>B.</strong> ping  <br>
<strong>C.</strong> nslookup <br> 
<strong>D.</strong> ipconfig/renew  <br>

**Answer:** *B*


<br>

**5. A ________ routing table contains information entered manually.**

<strong>A.</strong> static <br>
<strong>B.</strong> dynamic <br>
<strong>C.</strong> hierarchical <br> 
<strong>D.</strong> none of the above  <br>

**Answer:** *A*
<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>


**1. Which of the below AWS services allows you to increase the number of resources on the demand of the application or users?**


<strong>A.</strong> AWS EC2 <br>
<strong>B.</strong> AWS Autoscaling <br>
<strong>C.</strong> AWS ELB <br> 
<strong>D.</strong> AWS Inspector <br>

**Answer:** *B* <br>

*AWS Auto Scaling enables you to configure automatic scaling for the scalable AWS resources for your application in a matter of minutes. AWS Auto Scaling uses the Auto Scaling and Application Auto Scaling services to configure scaling policies for your scalable AWS resources.*

*For more information on AWS Autoscaling, please refer to the* [Link](https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html)


<br><br><br><br><br><br>

**2. Which of the following components effectively facilitate a user to set up AutoScaling on EC2 instances for a web-based application? Choose 3 correct Options:**

<strong>A.</strong> Launch Configuration <br>
<strong>B.</strong> Elastic Load Balancer <br>
<strong>C.</strong> Lambda <br> 
<strong>D.</strong> AutoScaling Group <br>
<strong>E.</strong> Elastic IP <br>

**Answer:** *A,B and D*

*Option A is correct. A launch configuration specifies the type of EC2 instance that Amazon EC2 Auto Scaling creates for you. You create the launch configuration by including information such as the ID of the Amazon Machine Image (AMI) to use, the instance type, the key pair, security groups, and block device mapping.*

*Option B is correct. You can attach a load balancer to your Auto Scaling group. The load balancer automatically distributes incoming traffic across the instances in the group.*

*Option C is not correct. Lambda functions are not required to setup auto scaling for EC2 instances.*

*Option D is correct. An Auto Scaling group is a collection of EC2 instances, and the core of Amazon EC2 Auto Scaling. When you create an Auto Scaling group, you include information such as the subnets for the instances and the number of instances the group must maintain at all times.*

*Option E is not correct. Elastic IP is not required to set up auto scaling for EC2 instances.*



<br>

**3. An ELB instance is configured with the default HealthCheck and Response Timeout intervals as 30 seconds and 5 seconds respectively. How long will it take for an instance within a target group to be labelled as OutOfService, if it goes down a second after the latest HealthCheck?**

<strong>A.</strong> 34 seconds <br>
<strong>B.</strong> 30 seconds <br>
<strong>C.</strong> 35 seconds <br> 
<strong>D.</strong> 4 seconds <br>

**Answer:** *A* <br>

*Since the health check runs every 30 seconds and the instance goes down one second into the cycle, it means 29 seconds will lapse before a new health check is run. Additionally, it will take 5 more seconds of the ELB instance probing the instance that is down, upon getting no response, it would then fail the health check. Therefore, 29 + 5 seconds = 34 seconds.*

*Option B. is INCORRECT because when a health check starts, the ELB gives the instance 5 seconds to respond during the probe.*

*Option C. is INCORRECT because the instance within the target group goes down 1 second after the latest health check cycle.*

*Option D. is INCORRECT because the health check runs after every 30 seconds window. So during this window, the ELB will not be probing the target group.*


<br>


**4. You are working as an AWS Architect for a start-up company. They have a two-tier production website. Database servers are spread across multiple Availability Zones and are stateful.**

**You have configured Auto Scaling Group for these database servers with a minimum of 2 instances & maximum of 6 instances. During post-peak hours, you observe some data loss. Which feature needs to be configured additionally to avoid future data loss (and copy data before instance termination)?**

<strong>A.</strong> Modify the cooldown period to complete custom actions before the Instance terminates. <br>
<strong>B.</strong> Add lifecycle hooks to Auto Scaling group. <br>
<strong>C.</strong> Customize Termination policy to complete data copy before termination. <br> 
<strong>D.</strong> Suspend Terminate process that will avoid data loss. <br>

**Answer:** *B*

*Adding Lifecycle Hooks to Auto Scaling group puts the instance into wait state before termination. During this wait state, you can perform custom activities to retrieve critical operational data from a stateful instance. Default Wait period is 1 hour.*

*Option A is incorrect as the cooldown period will not help to copy data from the instance before termination.*

*Option C is incorrect as Termination policy is used to specify which instances to terminate first during scale in, configuring termination policy for the Auto Scaling group will not copy data before instance termination.*

*Option D is incorrect as Suspending Terminate policy will not prevent data loss but will disrupt other process & prevent scale in.*

*For more information on lifecycle-hooks, refer to the following URLs.*  [Link-1 ](https://docs.aws.amazon.com/autoscaling/ec2/userguide/lifecycle-hooks.html),  [Link-2](https://aws.amazon.com/ec2/autoscaling/faqs/)


<br>

**5. You are deploying an application on Amazon EC2 that must call AWS APIs. Which method would you use to securely pass the credentials to the application?**

<strong>A.</strong> Pass API credentials to the instance using Instance userdata. <br>
<strong>B.</strong> Store API credentials as an object in Amazon S3.  <br>
<strong>C.</strong> TEmbed the API credentials into your application. <br>
<strong>D.</strong> Assign IAM roles to the EC2 Instances.


**Answer:** *D* <br>

*You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources. It is not a good practice to use IAM credentials for a production-based application. However, it is a good practice to use IAM Roles.*

*For more information on IAM Roles, please visit the following* [Link](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.htmll)




<br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Using CloudFormation Intrinsic Functions](https://www.youtube.com/watch?v=w87ORuX-aWk)


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


- [Coding Challenge: Find the Largest Number](https://github.com/clarusway/cw-workshop/tree/dev/python/coding-challenges/cc-003-find-the-largest-number) 

<br>

We assume that each group has two sub teams. Each week, one of the sub-teams will present their solution.



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Case study/Project</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


**Case study should be explained to the students during the weekly meeting and has to be completed in one sprint (2 weeks) by the students. Students should work in small teams to complete the case study.**

- [Project-001 : Roman Numerals Converter Application (Python Flask) deployed on AWS EC2 with Cloudformation](https://github.com/clarusway/cw-workshop/tree/dev/aws/projects/001-roman-numerals-converter)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
