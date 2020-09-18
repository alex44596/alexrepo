<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-24)</strong></span>

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
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. What is the trigger function in AWS Lambda?**
 
**Answer:** 
*Thanks to the trigger function, Lambda automatically operates the code you deploy in it. After you upload your code to AWS Lambda, you can associate your function with specific AWS resources (e.g. a particular Amazon S3 bucket or Amazon SNS notification). Then, when the resource changes, Lambda will execute your function and manage the computing resources as needed in order to keep up with incoming requests.*

<br>

**2. What is Amazon API Gateway?**

**Answer:** *Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale.*

*APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services. Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications.*


<br>


**3. What are the Reading Methods of the CSV Files in Python?**

**Answer:** There are several ways to read CSV files in Python.

- *You can use the ordinary way of reading using open() function and .read() method just you learned in the previous lesson.*
- *You can use* csv Module.
- *You can use the* Pandas *library for which created data analysis purposes. It is highly recommended if you have a lot of data to analyze.*


<br>

**4. Give some examples of standard errors that occour in Python.**

**Answer:** 

**TypeError-** It occurs when the expected type does not match with the given type of a variable.<br>
**ValueError-** It occurs when an expected value is not given, suppose you are expecting 6 elements in a list and you gave 2. <br>
**NameError-** It occurs when you are trying to access an undefined variable or a function.<br>
**IOError-** It occurs when you are trying to access a file that does not exist.<br>
**IndexError-** It occurs when you are trying to access an invalid index of a sequence.<br>
**KeyError-** It occurs when you use an invalid key to access a value in the dictionary.

<br>


**5. How to Load a Module in Python?**

**Answer:** <br> 
For loading a module, we use keyword <code>import</code> and the **name** of the module. 

The formula syntax is :  <code>import module_name</code>

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. Which of the following is a serverless compute offering from AWS?**

<strong>A.</strong> AWS EC2  <br>
<strong>B.</strong> AWS Lambda   <br>
<strong>C.</strong> AWS SNS <br> 
<strong>D.</strong> AWS Config   <br>
<strong>E.</strong>  AWS SQS  <br>


**Answer:** *B*<br>

*AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second.* <br>
*For more information, please refer to the*  [Link](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

<br><br><br><br><br><br><br><br>

**2. Your company is currently hosting a heavy load application on its On-premise environment. The company has developed this application in-house. Consulting companies then use this application via API calls. You now need to consider moving this application to AWS. Which of the following services would best be suited in the architecture design, which would also help deliver a cost-effective solution? Choose 2 answers from the options given below.**

<strong>A.</strong> AWS Lambda <br>
<strong>B.</strong> AWS API Gateway  <br>
<strong>C.</strong> AWS Config <br> 
<strong>D.</strong> AWS EC2

<br>

**Answer:** *B and D* <br>
Option A *might be a valid choice but the question specifies heavy load application which may lead to a need for time-out of API greater than 15min. As per AWS documentation, AWS Lambda can handle max time-out of up to 15 minutes. In this case, the application may take more time to run.*<br>

Option B *is correct because Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. With a few clicks in the AWS Management Console, you can create an API that acts as a “front door” for applications to access data, business logic, or functionality from your back-end services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, or any web application.*<br>

Option C *is incorrect since this is a configuration service available from AWS.*<br>

Option D is correct because EC2 would fit for using API calls for the application. <br>

For more information on AWS EC2 and the API gateway, please refer to the below URLs. <br>
 [Link-1](https://aws.amazon.com/api-gateway/) <br>
 [Link-2](https://aws.amazon.com/ec2)


<br>

**3. You have an application developed in .NET. This applications works with the S3 buckets in a particular region. The application is hosted on an EC2 Instance. Which of the following should ideally be used to ensure that the EC2 Instance has the appropriate access to the S3 buckets?**

<strong>A.</strong> AWS Users <br>
<strong>B.</strong> AWS Groups  <br>
<strong>C.</strong> AWS IAM Roles <br> 
<strong>D.</strong> AWS IAM Policies
<br>



**Answer:** *C*

*You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources.*<br>
*For more information on IAM Roles, please refer to the* [Link](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html) <br>
Groups *are collections of Users which will not be appropriate for the EC2 Instance so A and B are incorrect.*<br>
*The creation of a new policy cannot ensure appropriate access. They must be attached to a User, Group or Role. Therefore D is incorrect.*
   


**4. A professional educational institution maintains a dedicated web server and database cluster that hosts an exam results portal for modules undertaken by its students. The resource is idle for most of the learning cycle and becomes excessively busy when exam results are released. How can this architecture be improved to be cost-efficient?**

<strong>A.</strong> Configure AWS elastic load-balancing between the webserver and database cluster<br>
<strong>B.</strong> Configure RDS multi-availability zone for performance optimisation  <br>
<strong>C.</strong> Configure serverless architecture leveraging AWS Lambda functions <br> 
<strong>D.</strong> Migrate the web servers onto Amazon EC2 Spot Instances
<br>

**Answer:** *C*

*Leveraging AWS Lambda functions will remove the need to run a dedicated web server for the organisation. During periods of high requests to the database cluster, AWS lambda backend infrastructure will automatically scale out resources to adequately meet the demand. AWS Lambda provides a platform to run code without provisioning or managing any servers. The organisation pays only for the compute time they consume - there is no charge when your code is not running.*<br>
[Link](https://aws.amazon.com/lambda/)  <br>

Option A. INCORRECT *because the premise of the scenario is about cost-efficiency more than load and server responsiveness. Load-balancing would manage the traffic amongst the database clusters but would not relieve the organisation of maintaining a dedicated web server which only works occasionally.*<br>
[Link](https://aws.amazon.com/elasticloadbalancing/)   <br>

Option B. INCORRECT *because RDS multi-availability zone does not optimise the setup, rather it allows for disaster recovery, enhanced availability and durability. The scenarios requires a solution that reduces the cost of maintaining the organization's infrastructure and run it efficiently.*<br>
[Link]( https://aws.amazon.com/rds/details/multi-az/)   <br>

Option D. INCORRECT *because migrating to Amazon EC2 Spot Instances will negatively affect the operation of the portal during periods of high traffic. Instances could be terminated mid-transaction which would have adverse effects on the overall user experience. This would not be a cost-effective solution. Spot Instances let you take advantage of unused EC2 capacity in the AWS cloud. Spot Instances are available at up to a 90% discount compared to On-Demand prices. Spot Instances can reclaim the capacity back with two-minutes of notice.* <br>
[Link]( https://aws.amazon.com/ec2/spot/)  



<br><br><br><br><br><br><br><br><br><br><br><br><br>

**5. An application currently allows users to upload files to an S3 bucket. You want to ensure that the file name for each uploaded file is stored in a DynamoDB table. How could this be achieved? (SELECT TWO)**


<strong>A.</strong> Create an AWS Lambda function to insert the required entry for each uploaded file.<br>
<strong>B.</strong> Use AWS CloudWatch to probe for any S3 event.
 <br>
<strong>C.</strong> Add an event in S3 with notification send to Lambda.
 <br> 
<strong>D.</strong> Add the CloudWatch event to the DynamoDB table streams section.

<br>

**Answer:** *A and C* <br>

*You can create a Lambda function containing the code to process the file, and add the name of the file to the DynamoDB table.*

*You can then use an Event Notification from the S3 bucket to invoke the Lambda function whenever the file is uploaded.*

 
*For more information on Amazon S3 Event Notifications, please visit the following* [Link](https://docs.aws.amazon.com/AmazonS3/latest/dev/NotificationHowTo.html)  




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>



- [Exceptions in Python](https://www.youtube.com/watch?v=nlCKrKGHSSk&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-&index=32)

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

<br><br><br><br><br><br><br><br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Problem of the week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- Students should work in small teams to complete the problem of the week.


![POW](POW24.png)
<br>

**Answer:** *NORTON*

**Solution:** <br>

[Link](https://www.youtube.com/watch?v=2a5IbGs0KJA&list=PLhQjrBD2T3800qy4mK16nSThBr-_8J1Bb&index=4)



**Computational thinking:**

**Pattern recognition:** *Both quotes that are given in the question are talking about not paying attention. From this, it can be understood that the message was written without paying attention and while looking away from the keyboard or screen.*

**Abstraction:** *If it is thought of each letter that was typed as a position in the keyboard, one can understand that it is quite possible to shift this position while typing without paying attention and in a hurry.  So the abstraction in here is thinking of the letters as positions rather than their actual meaning.* 

**Algorithm Design:** *Now after finding out the shift that happened to the position of the fingers on the keyboard one can design an algorithm to find meaning of the rest of the message.* 

*Starting from the first letter:* <br>
1-)Pick the letter.  <br>
2-)Shift it to the direction that you found out. <br>
3-) Repeat for each letter. <br>

 <br> <br>

<table style= "width:96%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Presentation of Coding  Challenge & POW</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

We assume that each group has two sub teams. If this is possible one of the sub teams will present the coding challenge of last week. The other sub team will present the solution to the previous problem of the week. If there is only one sub team then, the sub team will present both of the solutions.


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- [Codding Challenge: Calculating the Amount of Water to be Trapped on Terrain](https://github.com/clarusway/clarusway-aws-devops-1-20/tree/master/python/coding-challenges/cc-006-calculate-amount-of-water-trapped) 

<br>


<table style= "width:96%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Presentation of Case Study of Previous Sprint</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

We assume that each group has two sub teams. Each week, one of the sub-teams will present their solution.



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Case study/Project</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


**Case study should be explained to the students during the weekly meeting and has to be completed in one sprint (2 weeks) by the students. Students should work in small teams to complete the case study.**

- [Project-004 : Phonebook Application (Python Flask) deployed on AWS Application Load Balancer with Auto Scaling and Relational Database Service using AWS Cloudformation](https://github.com/clarusway/clarusway-aws-devops-1-20/tree/master/aws/projects/004-phonebook-web-application)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
