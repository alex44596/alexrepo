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
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ask Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. What happens if the .git directory gets deleted?**
 
**Answer:** *The moment you create a repository, you will find a .git directory present inside it. This .git directory contains all the metadata of the repository and maintains a track of all the changes made to the files in your repository, by keeping a commit history.*

*All the information regarding commits, hooks, refs, object databases, remote repository addresses, etc. are kept inside this folder. This is the most crucial part of Git. When you clone any Git repository on your local machine, this .git is the directory that actually gets copied.*

*If the .git/ directory gets deleted, then you will lose track of your project’s history. The repository will no longer be under version control.*


<br>

**2. Now, imagine that you have a local repository, but other team members have pushed changes into the remote repository. What Git operation would you use to download those changes into your working copy?**

<strong>A.</strong> checkout  <br>
<strong>B.</strong> commit   <br>
<strong>C.</strong> export <br> 
<strong>D.</strong> pull   <br>
<strong>E.</strong> update   <br>



**Answer:** D


<br><br><br><br><br><br><br>


**3. What are characteristics of Amazon S3?** **(Choose 2 answers from the options given below.)**

<strong>A.</strong> S3 allows you to store objects of virtually unlimited size.  <br>
<strong>B.</strong> S3 allows you to store virtually unlimited amounts of data  <br>
<strong>C.</strong> S3 should be used to host a relational database. <br> 
<strong>D.</strong> Objects are directly accessible via a URL.  <br>


**Answer:** B and D

*Each object does have a limitation in S3, but you can store virtually unlimited amounts of data. Also each object gets a directly accessible URL.*

<br>

**4. What is the difference between | and || in Linux?**

**Answer:** *A pipe (|) is a form of redirection (transfer of standard output to some other destination) that is used in Linux and other Unix-like operating systems to send the output of one command/program/process to another command/program/process for further processing.
But || is a logical OR operator. The second command is executed only when the first command fails.*

<br>


**5. What is the output of the following Python program section?**

 
    st='Python Programming'
    x=st.lower()
    y=x.replace('python','Python')
    print y

<br>
<strong>A.</strong> python programming   <br>
<strong>B.</strong> Python Programming    <br>
<strong>C.</strong> Python programming  <br> 
<strong>D.</strong> PYTHON PROGRAMIN    <br>




**Answer:** C

<br><br><br><br><br><br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. In Amazon S3, what is the difference between lifecycle policies and intelligent tiering?**

<strong>A.</strong> Lifecycle policies are not dependent on access patterns as is the case with intelligent tiering, instead they are pre-configured with a transition rule.  <br>
<strong>B.</strong> Intelligent tiering is an object storage class which is not dependent on access patterns, it uses a pre-configured transition rule.   <br>
<strong>C.</strong> When transitioning objects into different storage classes, intelligent tiering is automatic whilst lifecycle policies have to be manually triggered.
 <br> 
<strong>D.</strong> Lifecycle policies cannot be configured to permanently delete objects from an S3 bucket whilst intelligent tiering can do so if versioning is turned on.  <br>



**Answer:** *A*<br>

*Within Amazon S3, lifecycle policies are used to automatically transition objects through different storage classes in accordance to a preconfigured rule. This rule will typically move the object regardless of how frequently it is accessed. For more information, please refer to the*
[Link](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html)



<br>

**2. A company wants to utilize aws storage. For them low storage cost is paramount, the data is rarely retrieved, and data retrieval times of several hours are acceptable for them. What is the best storage option to use?**

<strong>A.</strong> AWS Glacier <br>
<strong>B.</strong> AWS S3 Reduced Redundancy Storage  <br>
<strong>C.</strong> EBS backed storage connected to EC2 <br> 
<strong>D.</strong> AWS CloudFront


**Answer:** *A* <br>
*Amazon Glacier is a storage service optimized for infrequently used data, or "cold data." The service provides durable and extremely low-cost storage with security features for data archiving and backup. With Amazon Glacier, you can store your data cost effectively for months, years, or even decades.* 

*For more information on AWS Glacier, please refer to the* [Link](https://aws.amazon.com/documentation/glacier/) 

<br> 

**3. Which of the following can be attached to EC2 Instances to store data?**

<strong>A.</strong> Amazon Glacier <br>
<strong>B.</strong> Amazon EBS Volumes  <br>
<strong>C.</strong> Amazon EBS Snapshots <br> 
<strong>D.</strong> Amazon SQS 


**Answer:** B

*An Amazon EBS volume is a durable, block-level storage device that you can attach to a single EC2 instance. You can use EBS volumes as primary storage for data that requires frequent updates, such as the system drive for an instance or storage for a database application*


<br>

**4. Which of the following can be used to manage identities in AWS?**

<strong>A.</strong> AWS Config <br>
<strong>B.</strong> AWS IAM  <br>
<strong>C.</strong> AWS Trusted Advisor <br> 
<strong>D.</strong> AWS RDS

**Answer:** B

*AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
For more information on AWS IAM, please refer to the*  [Link](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) 




<br>

**5. You have a devops team in your current organization structure. They are keen to know if there is any service available in AWS which can be used to manage infrastructure as code. Which of the following can be met with such a requirement?**

<strong>A.</strong> Using AWS Cloudformation
 <br>
<strong>B.</strong>  Using AWS Config
 <br>
<strong>C.</strong> Using AWS Inspector
 <br> 
<strong>D.</strong> Using AWS Trusted Advisor


**Answer:** A

*AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. You don't need to individually create and configure AWS resources and figure out what's dependent on what; AWS CloudFormation handles all of that.

For more information on AWS Cloudformation, please refer to the
[Link](hhttps://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html).




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Codding Challenge - 009: find the power set](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/python/coding-challenges/cc-002-find-the-power-set/README.md) 

<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [What is SQL?](https://www.youtube.com/watch?v=27axs9dO7AE )

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
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Case study/Project</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>15m</p><td>                </tr>
</table>


**Case study should be explained to the students during the weekly meeting and has to be completed in one sprint (2 weeks) by the students. Students should work in small teams to complete the case study.**

- [Project-102 : Kittens Carousel Static Website deployed on AWS EC2 with ALB and ASG using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/tree/master/aws/projects/102-kittens-carousel-static-website-alb-asg)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
