<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-5)</strong></span>

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
 m = [[1, 2], [4, 5, 6]]
 for i in range(0, 2):
    print(m[i][1], end=" ")
```

<strong>A.</strong> 1 4  <br>
<strong>B.</strong> 2 5   <br>
<strong>C.</strong> error <br> 
<strong>D.</strong> 1 2 4   <br>

**Answer:** B

<br>

**2. What is the command to view all the available partitions on the system in linux?**

**Answer:** `fdisk -l`

*For more info please visit:*  [Link](https://www.tldp.org/HOWTO/Partition/fdisk_partitioning.html/UserGuide/EBSSnapshots.html)
  

<br>

**3. Which of the following is not the disadvantages of SQL?**
 
<strong>A.</strong> It requires strict coordination with database developers <br>
<strong>B.</strong> The requests must be determined correctly in advance   <br>
<strong>C.</strong> Low flexibility due to the determined scheme <br> 
<strong>D.</strong> Join functions are not available in SQL  <br>


**Answer:** D

<br><br>

**4. Which of the statements below are true about Databases?**

**I-** Databases make the information meaningful and useful <br>
**II-** Database is an organized collection of data. <br>
**III-** Database only stores data. So, you can’t fetch any information from the database


<strong>A.</strong> II-III <br>
<strong>B.</strong> I-III   <br>
<strong>C.</strong> I-II-III <br> 
<strong>D.</strong> I-II   <br>

**Answer:** D

*We can also fetch the information based on the desired format and queries from the database. So, III is incorrect.*

<br>



**5. Which of the below is a false statement in python?**

<strong>A.</strong> `int(144) == 144` <br>
<strong>B.</strong> `int('144') == 144`   <br>
<strong>C.</strong> `int(144.0) == 144`<br> 
<strong>D.</strong> `None of the above`   <br>

**Answer:** D

*The built-in int() type constructor converts string and floating value to integer.*


*Please visit below link for more info about python built-in Types:* [Link](https://docs.python.org/3/library/stdtypes.html ) 
<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. Why is Amazon DynamoDB service best-suited for implementation in mobile, Internet of Things (IoT) and gaming applications?**

<strong>A.</strong> DynamoDB is a fully-managed database instance with no infrastructure overheads <br>
<strong>B.</strong> DynamoDB has a flexible data model and single-digit millisecond latency  <br>
<strong>C.</strong> Whilst in operation, DynamoDB instances are spread across at least three geographically distinct centers, AWS Regions <br> 
<strong>D.</strong> DynamoDB supports eventual and strongly consistent reads  <br>



**Answer:** *B*<br>


The use cases mentioned in the scenario have unstructured data in common, therefore, the most appropriate attribute of Amazon DynamoDB is its flexible data model and single-digit millisecond latency. [Link](
https://aws.amazon.com/blogs/database/how-to-determine-if-amazon-dynamodb-is-appropriate-for-your-needs-and-then-plan-your-migration/ ) 

**Option A** is INCORRECT because being fully-managed and having no infrastructure overheads does not distinguish DynamoDB as the best-suited solution for the given use cases. <br>
**Option C** is INCORRECT because the aspect of fault-tolerance, disaster recovery and high availability is also present in Amazon Relational Databases (RDS), this feature does not distinguish the service in accordance with the described use cases.<br>
**Option D** is INCORRECT because this attribute of DynamoDB does not fully justify its exclusive choice over other instances when considered for implementation in the use cases mentioned in the question.

<br>

**2. What is the AWS service which provides a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability?**

<strong>A.</strong> AWS RDS <br>
<strong>B.</strong> DynamoDB  <br>
<strong>C.</strong> Oracle RDS <br> 
<strong>D.</strong> Elastic Map Reduce



**Answer:** *B* <br>

*DynamoDB is a fully managed NoSQL offering provided by AWS.*

*For more information, please refer to the* [Link](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) 

<br> 

**3. Which of the following AWS managed database services provides processing power that is up to 5X faster than a traditional MySQL database.**

<strong>A.</strong> MariaDB
 <br>
<strong>B.</strong> Aurora
 <br>
<strong>C.</strong> PostgreSQL
 <br>
<strong>D.</strong> DynamoDB <br>


**Answer:** B

*The AWS Documentation mentions the following;
Amazon Aurora (Aurora) is a fully managed, MySQL- and PostgreSQL-compatible, relational database engine. It combines the speed and reliability of high-end commercial databases with the simplicity and cost-effectiveness of open-source databases. It delivers up to five times the throughput of MySQL and up to three times the throughput of PostgreSQL without requiring changes to most of your existing applications.*

*For more information on AWS Aurora, please refer to the* [Link](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Aurora.Overview.html) 



**4. Your development team is planning to host a development environment on the cloud. This consists of EC2 and RDS instances. This environment will probably only be required for 2 months. Which types of instances would you use for this purpose?**

**Which feature should be used to enable this requirement?**

<strong>A.</strong> On-Demand
<br>
<strong>B.</strong> Spot
 <br>
<strong>C.</strong> Reserved <br> 
<strong>D.</strong> Dedicated Hosts



**Answer:** A

*The best and cost effective option would be to use On-Demand Instances. The AWS documentation gives the following additional information on On-Demand EC2 Instances
With On-Demand instances you only pay for EC2 instances you use. The use of On-Demand instances frees you from the costs and complexities of planning, purchasing, and maintaining hardware and transforms what are commonly large fixed costs into much smaller variable costs.*

*For more information on AWS On-Demand Instances, please refer to the* [Link](https://aws.amazon.com/ec2/pricing/on-demand/) 


**Option B** *is incorrect. Spot instances may be terminated at any time with the fluctuation of market prices. Therefore, unless the question indicates this use case, we cannot assume the development team would not expect high availability.* <br>
**Option C** *is incorrect. Reserved Instances require a minimum 1 year commitment.*
**Option D** *is incorrect. Dedicated hosts are typically used when the underlying hardware cannot be shared across tenants (customers). This is the most expensive option and typically would not be ideal for development purposes.*



<br>

**5. You are creating a number of EBS Volumes for the EC2 Instances hosted in your company's AWS account. The company has asked you to ensure that the EBS volumes are available even in the case of an entire region facing an outage due to a natural disaster. How would you accomplish this? Choose 2 answers from the options given below**

<strong>A.</strong> Configure Amazon Storage Gateway with EBS volumes as the data source and store the backups on premise through the storage gateway <br>
<strong>B.</strong> Create snapshots of the EBS Volumes.
 <br>
<strong>C.</strong> Ensure the snapshots are made available in another availability zone
 <br> 
<strong>D.</strong> Ensure the snapshots are made available in another region



**Answer:** B and D

*The AWS Documentation mentions the following;*

*You can back up the data on your Amazon EBS volumes to Amazon S3 by taking point-in-time snapshots. Snapshots are incremental backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved. This minimizes the time required to create the snapshot and saves on storage costs by not duplicating data. When you delete a snapshot, only the data unique to that snapshot is removed. Each snapshot contains all of the information needed to restore your data (from the moment when the snapshot was taken) to a new EBS volume.*

**Option A** *is incorrect since you have to make use of EBS snapshots* <BR>
**Option C** *is incorrect since the snapshots need to be made available in another region for such a huge disaster. It may be rare for the whole AWS region to go down, but it could cause massive permanent damage if we don’t plan for it.*

*For more information on EBS snapshots, please visit the* [Link](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html) 

<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Coding Challenge: Rock, paper, scissors](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/python/coding-challenges/cc-004-create-rock-paper-scissors-game/README.md) 



<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [DevOps & Continuous Delivery Lifecycle Explained](https://www.youtube.com/watch?time_continue=212&amp;v=eWlZQxgcAPE&amp;feature=emb_logo)



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

- [Project-003 : To-Do Web API (Python Flask) deployed on AWS EC2 and RDS using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/aws/projects/103-to-do-web-api-ec2-rds/README.md)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
