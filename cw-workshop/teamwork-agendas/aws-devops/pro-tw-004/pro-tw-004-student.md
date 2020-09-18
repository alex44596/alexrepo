<h1><strong><span style="color: #77C8D5;"> STUDENT VERSION (Week-4)</strong></span>

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

**1. What will be the output?**
```
list=[1, 2, 3, 4, 5]
list[2:3]=[]
print(list)
```

<strong>A.</strong> [1, 4, 5]  <br>
<strong>B.</strong> [1, 3, 4, 5]   <br>
<strong>C.</strong> [1, 2, 4, 5] <br> 
<strong>D.</strong> [1, 2, 5]   <br>


<br>

**2. What will be the output of the following Python code?**
```
print("Hello {0} and {1}".format('foo', 'bin'))
```


<strong>A.</strong> Hello foo and bin
  <br>
<strong>B.</strong> Hello {0} and {1} foo bin
 <br>
<strong>C.</strong> Error
 <br> 
<strong>D.</strong> Hello 0 and 1
<br>

<br>

**3. Auto Scaling will create a new instance according to the features determined by ...................**

<strong>A.</strong> Launch Configuration or Launch Templates <br>
<strong>B.</strong> Random   <br>
<strong>C.</strong> Root User <br> 
<strong>D.</strong> AWS   <br>



**4. Write a query to find the name, department ID and salary of the employees whose salary is greater than 2000.** <BR>

**EMPLOYEES**

| NAME  | DEPARTMENT_ID  |SALARY   | 
|---|---|---|---|---|
|  Getz |10   | 3000  |   
|  Davis | 20  | 1500   |   
|  King |  20  | 2200  |  
|  Davis | 30  | 2000  |   
|  Kochbar| 40 | 5000  |  

 
<br>

<strong>A.</strong> <br>SELECT name, department_ID <br>
FROM employees <br>
WHERE salary => 2000;  <br>

<strong>B.</strong> <br> SELECT name, department_ID <br>
FROM employees <br>
JOIN salary > 2000;  <br>

<strong>C.</strong> <br> SELECT name, department_ID <br>
FROM employees <br>
WHERE salary > 2000;  <br>


<br>

**5. After you increase the size of an EBS volume, you must use file system-specific commands to ………. the file system to the larger size.**

<strong>A.</strong> Identify <br>
<strong>B.</strong> Format
   <br>
<strong>C.</strong> Extend<br> 
<strong>D.</strong> Mount   <br>



<br><br><br><br><br><br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. A company has a set of EC2 Instances that store critical data on EBS Volumes. There is a fear from IT Supervisors that if data on the EBS Volumes is lost, then it could result in a lot of effort to recover the data from other sources. Which of the following would help alleviate this concern in an economical way?**

<strong>A.</strong> Take regular EBS Snapshots.
 <br>
<strong>B.</strong> Enable EBS Volume encryption
  <br>
<strong>C.</strong> Create a script to copy data to an EC2 Instance Store <br> 
<strong>D.</strong> Mirror data across 2 EBS Volumes
  <br>




<br>

**2. You are working as an AWS Architect for a start-up company. They have a two-tier production website. Database servers are spread across multiple Availability Zones and are stateful.
    You have configured Auto Scaling Group for these database servers with a minimum of 2 instances & maximum of 6 instances. During post-peak hours, you observe some data loss. Which feature needs to be configured additionally to avoid future data loss (and copy data before instance termination)?**

<strong>A.</strong> Modify the cooldown period to complete custom actions before the Instance terminates.
 <br>
<strong>B.</strong> Add lifecycle hooks to Auto Scaling group.
  <br>
<strong>C.</strong> Customize Termination policy to complete data copy before termination.
 <br> 
<strong>D.</strong> Suspend Terminate process that will avoid data loss.


<br> 

**3. You are working as an AWS consultant for a start-up company. They have developed a web application for their employees to share files with external vendors securely. They created an AutoScaling group for the web servers which requires two m4.large EC2 instances running at all times, scaling up to a maximum of twelve instances. Post-deployment of the application, a huge rise in cost was observed. Due to a limited budget, the CTO has requested your advice to optimize the usage of instances in the Auto Scaling groups. What would you suggest to reduce costs without any adverse impact on the performance?**

<strong>A.</strong> Create an Auto Scaling group with t2. micro On-Demand instances.
 <br>
<strong>B.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as zero. Above On-Demand base, select 100% of On-Demand instance & 0% of Spot Instance.
 <br>
<strong>C.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as 2. Above On-Demand base, select 20% of On-Demand instance & 80% of Spot Instance. <br>
<strong>D.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as 2. Above On-Demand base, select 20% of On-Demand instance & 80% of Spot Instance. <br>

<br><br><br><br><br><br>

**4. Development teams in your organization use S3 buckets to store log files for various applications hosted in AWS development environments. The developers intend to keep the logs for a month for troubleshooting purposes, and subsequently purge the logs.**

**Which feature should be used to enable this requirement?**

<strong>A.</strong> Adding a bucket policy on the S3 bucket.
<br>
<strong>B.</strong> Configuring lifecycle configuration rules on the S3 bucket.
 <br>
<strong>C.</strong> Creating an IAM policy for the S3 bucket. <br> 
<strong>D.</strong> Enabling CORS on the S3 bucket.




<br>

**5. In Amazon S3, what is the difference between lifecycle policies and intelligent tiering?**

<strong>A.</strong> Lifecycle policies are not dependant on access patterns as is the case with intelligent tiering, instead they are pre-configured with a transition rule.
 <br>
<strong>B.</strong>  Intelligent tiering is an object storage class which is not dependant on access patterns, it uses a pre-configured transition rule.
 <br>
<strong>C.</strong> When transitioning objects into different storage classes, intelligent tiering is automatic whilst lifecycle policies have to be manually triggered.
 <br> 
<strong>D.</strong> Lifecycle policies cannot be configured to permanently delete objects from an S3 bucket whilst intelligent tiering can do so if versioning is turned on.



<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Coding Challenge: Security Questions](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/tree/master/python/coding-challenges/cc-003-validate-customers-with-security-questions) 

<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Python Lists](https://www.youtube.com/watch?v=ohCDWZgNIU0&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-&index=14 )

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

<br><br><br>

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
