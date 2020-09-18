<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-4)</strong></span>

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

**Answer:** C

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


**Answer:** A

<br><br><br><br><br>

**3. Auto Scaling will create a new instance according to the features determined by ...................**

<strong>A.</strong> Launch Configuration or Launch Templates <br>
<strong>B.</strong> Random   <br>
<strong>C.</strong> Root User <br> 
<strong>D.</strong> AWS   <br>

**Answer:** A


<br>

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




**Answer:** C

<br><br><br><br><br><br><br>

**5. After you increase the size of an EBS volume, you must use file system-specific commands to ………. the file system to the larger size.**

<strong>A.</strong> Identify <br>
<strong>B.</strong> Format
   <br>
<strong>C.</strong> Extend<br> 
<strong>D.</strong> Mount   <br>

**Answer:** C

<br>


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



**Answer:** *A*<br>

Option B *is incorrect because it does not help in durability of EBS Volumes.*
Option C *is incorrect since EC2 Instance stores are not durable.*
Option D *is incorrect since mirroring data across EBS Volumes is inefficient when you already have an option for EBS Snapshots.*

The AWS Documentation mentions the following on AWS EBS Snapshots: <br>
*You can back up the data on your Amazon EBS Volumes to Amazon S3 by taking point-in-time snapshots. Snapshots are incremental backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved. This minimizes the time required to create the snapshot and saves on storage costs by not duplicating data. When you delete a snapshot, only the data unique to that snapshot is removed. Each snapshot contains all of the information needed to restore your data (from the moment when the snapshot was taken) to a new EBS volume.*

For more information on AWS EBS Snapshots, please visit the following [Link](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)



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



**Answer:** *B* <br>

*Adding Lifecycle Hooks to the Auto Scaling group puts the instance into wait state before termination. During this wait state, you can perform custom activities to retrieve critical operational data from a stateful instance. Default Wait period is 1 hour.* <br
>
Option A *is incorrect as the cooldown period will not help to copy data from the instance before termination.* <br>
Option C *is incorrect as Termination policy is used to specify which instances to terminate first during scale in, configuring termination policy for the Auto Scaling group will not copy data before instance termination.*  <br>
Option D *is incorrect as Suspending Terminate policy will not prevent data loss but will disrupt other processes & prevent scale in.*

For more information on lifecycle-hooks, refer to the following 
[Link](https://docs.aws.amazon.com/autoscaling/ec2/userguide/lifecycle-hooks.html) 

<br> 

**3. You are working as an AWS consultant for a start-up company. They have developed a web application for their employees to share files with external vendors securely. They created an AutoScaling group for the web servers which requires two m4.large EC2 instances running at all times, scaling up to a maximum of twelve instances. Post-deployment of the application, a huge rise in cost was observed. Due to a limited budget, the CTO has requested your advice to optimize the usage of instances in the Auto Scaling groups. What would you suggest to reduce costs without any adverse impact on the performance?**

<strong>A.</strong> Create an Auto Scaling group with t2. micro On-Demand instances.
 <br>
<strong>B.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as zero. Above On-Demand base, select 100% of On-Demand instance & 0% of Spot Instance.
 <br>
<strong>C.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as 2. Above On-Demand base, select 20% of On-Demand instance & 80% of Spot Instance. <br>
<strong>D.</strong> Create an Auto Scaling group with a mix of On-Demand & Spot Instance. Select the On-Demand base as 2. Above On-Demand base, select 20% of On-Demand instance & 80% of Spot Instance. <br>


**Answer:** D

Auto Scaling group supports a mix of On-Demand & Spot instance which help to design a cost-optimized solution without any impact on the performance. You can choose the percentage of On-Demand & Spot instance based on the application requirements. With Option D, Auto Scaling group will have 2 instances initially as the On-Demand instances while remaining instances will be launched in a ratio of 20 % On-Demand instance & 80% Spot Instance.


Option A *is incorrect. With t2. micro, there would be a reduction in cost, but it will impact the performance of the application.* <br>
Option B *is incorrect as there would not be any cost reduction with all On-Demand instances.* <br>
Option C *is incorrect. Although this will reduce cost, all spot instance in an auto-scaling group may cause inconsistencies in the application & lead to poor performance.*

For more information on Auto Scaling with multiple Instance types & purchase options, refer to the following URLs:

[Link-1](https://aws.amazon.com/blogs/aws/new-ec2-auto-scaling-groups-with-multiple-instance-types-purchase-options/) ,
[Link-2](https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html#asg-purchase-options) 



**4. Development teams in your organization use S3 buckets to store log files for various applications hosted in AWS development environments. The developers intend to keep the logs for a month for troubleshooting purposes, and subsequently purge the logs.**

**Which feature should be used to enable this requirement?**

<strong>A.</strong> Adding a bucket policy on the S3 bucket.
<br>
<strong>B.</strong> Configuring lifecycle configuration rules on the S3 bucket.
 <br>
<strong>C.</strong> Creating an IAM policy for the S3 bucket. <br> 
<strong>D.</strong> Enabling CORS on the S3 bucket.


**Answer:** B

*AWS Documentation mentions the following on Lifecycle policies:
Lifecycle configuration enables you to specify the Lifecycle management of objects in a bucket. The configuration is a set of one or more rules, where each rule defines an action for Amazon S3 to apply to a group of objects. These actions can be classified as follows:*

- Transition actions: In which you define when objects transition to another storage class. For example, you may choose to transition objects to the STANDARD_IA (IA, for infrequent access) storage class 30 days after creation or archive objects to the GLACIER storage class one year after creation. <br>
- Expiration actions – In which you specify when the objects expire. Then, Amazon S3 deletes the expired objects on your behalf.

For more information on AWS S3 Lifecycle policies, please visit the following [Link](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html) 




<br>

**5. In Amazon S3, what is the difference between lifecycle policies and intelligent tiering?**

<strong>A.</strong> Lifecycle policies are not dependant on access patterns as is the case with intelligent tiering, instead they are pre-configured with a transition rule.
 <br>
<strong>B.</strong>  Intelligent tiering is an object storage class which is not dependant on access patterns, it uses a pre-configured transition rule.
 <br>
<strong>C.</strong> When transitioning objects into different storage classes, intelligent tiering is automatic whilst lifecycle policies have to be manually triggered.
 <br> 
<strong>D.</strong> Lifecycle policies cannot be configured to permanently delete objects from an S3 bucket whilst intelligent tiering can do so if versioning is turned on.


**Answer:** A

Within Amazon S3, lifecycle policies are used to automatically transition objects through different storage classes in accordance to a preconfigured rule. This rule will typically move the object regardless of how frequently it is accessed.
[Link](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html).



Option B *is incorrect because intelligent tiering uses access patterns when determining transitioning action.* <br>

Option C *is incorrect because lifecycle policies are automatically triggered when the ‘days after creation’ period lapses.* <br>
Option D *is incorrect because lifecycle policies can indeed be configured to permanently delete objects. Intelligent tiering cannot be configured to permanently delete objects even if versioning is turned on for the objects.*





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



- [Python Lists](https://www.youtube.com/watch?v=ohCDWZgNIU0&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-&index=14)

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
