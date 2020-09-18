<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-7)</strong></span>

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

**1. Networking Hardware Address is referred with ________.**

<strong>A.</strong> IP address <br>
<strong>B.</strong> MAC address  <br>
<strong>C.</strong> NIC <br> 
<strong>D.</strong> Organizationally Unique Identifier  <br>

**Answer:** *B*

<br>

**2. Encapsulation is the process of taking data from one protocol and translating it into another protocol, so the data can continue across a network.**

<strong>A.</strong> True <br>
<strong>B.</strong> False
<br>

**Answer:** *A*

<br>

**3. What is the output?**

```
def calculate(numbers):
    result = 0
    for x in numbers:
        result += x
    return total
print(calculate((8, 2, 3, 0, 7)))
```

<strong>A.</strong> 10 <br>
<strong>B.</strong> 8  <br>
<strong>C.</strong> 0 <br> 
<strong>D.</strong> 20 <br>

**Answer:** D

<br>

**4. A media organization offers news in local languages around the world. Which Route 53 routing policy should be used to direct readers to the website with the correct language?**

<strong>A.</strong> Latency
 <br>
<strong>B.</strong> Geolocation
  <br>
<strong>C.</strong> Multivalue answer
 <br> 
<strong>D.</strong> Weighted
  <br>

**Answer:** *B*

<br>



**5. You need to transfer files between two hosts. Which protocol can you use?**

<strong>A.</strong> TCP <br>
<strong>B.</strong> NFS <br>
<strong>C.</strong> FTP <br> 
<strong>D.</strong> UDP   <br>

**Answer:** *C*

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. A company is planning to build a 2-tier architecture with a web server and a database server with separate environments for development and testing.  The architecture will be hosted on EC2 Instances accordingly, and the database server would require more than 10,000 IOPS per volume.  Which of the following EBS volumes are optimum for the underlying EC2 Instances? (Select Two)**

<strong>A.</strong> General Purpose SSD for the web server <br>
<strong>B.</strong> Provisioned IOPS for the web server
<br>
<strong>C.</strong> General Purpose SSD for the database server <br> 
<strong>D.</strong>  Provisioned IOPS for the database server <br>


**Answer:** *A and C*<br>


*The General Purpose SSD would be suitable for development and test environments and the IOPS SSD for business critical applications*

*For more information on EBS Volume types, please visit the following* [Link](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volume-types.html ) 


<br><br><br><br>

**2. A website is hosted on two EC2 instances that sit behind an Elastic Load Balancer. The response time of the website has been slowed down dramatically, and customers are placing fewer orders due to the wait time. Troubleshooting showed that one of the EC2 instances has failed and only one instance is running now. What is the best course of action to prevent this from happening in the future?**

<strong>A.</strong> Change the instance size to the maximum available to compensate for the failure <br>
<strong>B.</strong> Use CloudWatch to monitor the VPC Flow Logs for the VPC, where the instances are deployed in  <br>
<strong>C.</strong> Configure the ELB to perform health checks on the EC2 instances and implement auto-scaling <br> 
<strong>D.</strong> Replicate the existing configuration in several regions for failover
<br>

**Answer:** *C* <br>

Option C is correct. *Using the elastic load balancer to perform health checks will determine whether or not to remove a non-performing or underperforming instance, and have the auto-scaling group launch a new instance.* <br>
Option A is incorrect. *Increasing the instance size doesn’t prevent failure of one or both the instances, therefore the website can still become slow or unavailable.* <br>
Option B is incorrect. *Monitoring the VPC flow logs for the VPC will capture the VPC traffic, not the traffic for the EC2 instance. You would need to create a flow log for a network interface.*<br>
Option D is incorrect. *Replicating the same two instance deployment may not prevent failure of instances and could still result in the website becoming slow or unavailable.*

*For more information, please visit the following* <br>
[Link-1](https://d1.awsstatic.com/whitepapers/aws-building-fault-tolerant-applications.pdf) ,
[Link-2](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html#working-with-flow-logs) 

<br> 

**3. You are hosting a web server on an EC2 Instance. With the number of requests consuming a large part of the CPU, the response performance for the application is getting degraded. Which of the following would help to alleviate the problem and provide a better response time?**

<strong>A.</strong> Place the EC2 Instance behind a Classic Load Balancer. <br>
<strong>B.</strong> Place the EC2 Instance behind an Application Load Balancer. <br>
<strong>C.</strong> Place the EC2 Instance in an Auto Scaling Group with the max size as 1. <br>
<strong>D.</strong> Place a CloudFront distribution in front of the EC2 Instance. <br>


**Answer:** *D*

*Since there is a mention of only one EC2 instance, placing it behind the ELB would not make much sense, hence Options A and B are invalid.*<br>
*Having it in an Auto Scaling Group with just one instance would not make much sense.*<br>
*CloudFront distribution would help to alleviate the load on the EC2 Instance because of its edge location and cache feature.*

*For more information on CloudFront, please visit the following* [Link](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html
) 
<br><br><br><br><br><br><br>


**4. You have an application developed in .NET. This applications works with the S3 buckets in a particular region. The application is hosted on an EC2 Instance.**

**Which of the following should ideally be used to ensure that the EC2 Instance has the appropriate access to the S3 buckets?**


<strong>A.</strong> AWS Users <br>
<strong>B.</strong> AWS Groups <br>
<strong>C.</strong> AWS IAM Roles<br> 
<strong>D.</strong> AWS IAM Policies


**Answer:** C

*You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources.*

*Groups are collections of Users which will not be appropriate for the EC2 Instance so A and B are incorrect.*<br>
*The creation of a new policy cannot ensure appropriate access. They must be attached to a User, Group or Role.
Therefore D is incorrect.*


<br>

**5. A company is hosting a MySQL database in AWS using the AWS RDS service. To offload the reads, a Read Replica has been created and reports are run off the Read Replica database. But at certain times, the reports show stale data. What could be the possible reason behind this?**


<strong>A.</strong> The Read Replica has not been created properly. <br>
<strong>B.</strong> The backup of the original database has not been set properly. <br>
<strong>C.</strong>  This is due to the replication lag. <br> 
<strong>D.</strong> The Multi-AZ feature is not enabled.


**Answer:** *C*

*An AWS Whitepaper on the caveat for reading Replicas is given below which must be taken into consideration by architects:*

*Read Replicas are separate database instances that are replicated asynchronously. As a result, they are subject to replication lag and might be missing some of the latest transactions. Application architects need to consider which queries have the tolerance to slightly stale data. Those queries can be executed on a Read Replica, while the rest should run on the primary node. Read Replicas may also not accept any write queries.*

*For more information on Amazon RDS Read Replicas, please visit the following*  [Link](https://aws.amazon.com/rds/features/read-replicas/) 





<br><br><br><br><br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Find the Non-Repeated Values](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/python/coding-challenges/cc-006-find-non-repeated-values/README.md) 



<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Top 7 Cloud Infrastructure Interview Questions](https://www.youtube.com/watch?v=yulGNwmync0)



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

- [Project-104: Kittens Carousel Static Website deployed on AWS Cloudfront, S3 and Route 53 using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/tree/master/aws/projects/104-kittens-carousel-static-web-s3-cf)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
