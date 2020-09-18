<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-9)</strong></span>

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

**1. This command sends a request out and expects a response, indicating that both hosts are communicating.**

<strong>A.</strong> tracert  <br>
<strong>B.</strong> ping  <br>
<strong>C.</strong> nslookup <br> 
<strong>D.</strong> ipconfig/renew  <br>

**Answer:** *B*


<br>

**2. A ________ routing table contains information entered manually.**

<strong>A.</strong> static <br>
<strong>B.</strong> dynamic <br>
<strong>C.</strong> hierarchical <br> 
<strong>D.</strong> none of the above  <br>

**Answer:** *A*

<br>

**3. Python supports the creation of anonymous functions at runtime, using a construct called __________?**

<strong>A.</strong> anonymous <br>
<strong>B.</strong> Pi <br>
<strong>C.</strong> lambda <br> 
<strong>D.</strong> built-in   <br>

**Answer:** *C*

<br><br><br>

**4. What is the output of the following code snippet?**

```
func = lambda x: return x
print(func(2))
```

<strong>A.</strong> 2 <br>
<strong>B.</strong> 2.0 <br>
<strong>C.</strong> x <br> 
<strong>D.</strong> SyntaxError  <br>
<strong>E.</strong> 0 <br>

**Answer:** *D*

*A lambda function can’t contain the return statement. In a lambda function, statements like return, pass, assert, or raise will raise a SyntaxError exception.*

<br> 

**5. What will be the output of the following Python code?**

```
def writer():
	title = 'Sir'
	name = (lambda x:title + ' ' + x)
	return name
 
who = writer()
who('Arthur')
```

<strong>A.</strong> Arthur Sir <br>
<strong>B.</strong> Sir Arthur <br>
<strong>C.</strong> Arthur <br>
<strong>D.</strong> None of the mentioned <br>

**Answer:** *B*

<br><br><br><br><br><br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>



**1. An organization runs several EC2 instances inside a VPC using three subnets, one for Development, one for Test and one for Production. The Security team has some concerns about the VPC configuration and requires to restrict the communication across the EC2 instances using Security Groups.** 

**Which of the following options is true for Security Groups?**


<strong>A.</strong> You can change a Security Group associated to an instance if the instance state is stopped or running. <br>
<strong>B.</strong> You can change a Security Group associated to an instance if the instance state is stopped but not if the instance state is running. <br>
<strong>C.</strong> You can change a Security Group only if there are no instances associated to it. <br> 
<strong>D.</strong> The only Security Group you can change is the Default Security Group. <br>
<strong>E.</strong> The only Security Group you can change is the Default Security Group.


**Answer:** *A*

*Option A is CORRECT because the AWS documentation mentions it in the section called  “Changing an Instance’s Security Group” using the following sentence: “After you launch an instance into a VPC, you can change the security groups that are associated with the instance. You can change the security groups for an instance when the instance is in the running or stopped state.”*


*For more information* [Link](https://docs.aws.amazon.com/en_pv/vpc/latest/userguide/VPC_SecurityGroups.html)

<br>

**2. You are the architect of a custom application running inside your corporate data center. The application runs with some unresolved bugs that produce a lot of data inside custom log files generating time-consuming activities to the operation team who is responsible for analyzing them.**

**You want to move the application to AWS using EC2 instances, and at the same time, take the opportunity for improving logging and monitoring capabilities but without touching the application code.**

**What AWS service should you use to satisfy the requirement?**

<strong>A.</strong> AWS Kinesis Data Streams <br>
<strong>B.</strong> AWS CloudTrail <br>
<strong>C.</strong> AWS CloudWatch Logs <br> 
<strong>D.</strong> AWS Application Logs <br>


**Answer:** *C*<br>

*Option A is INCORRECT because in order to feed a Data Streams from custom logs you have to change the application code. AWS documentations describes this with the following sentence: “To put data into the stream, you must specify the name of the stream, a partition key, and the data blob to be added to the stream.”
Option B is INCORRECT because is unrelated to the scenario and custom log files.
Option C is CORRECT because AWS CloudWatch Logs has the capability to reuse existing application logs increasing efficiency in operation with the ability to generate on them metrics, alerts and analytics with AWS CloudWatch Logs Insight.*

*As the application and custom log files are exactly as they were when the application was running on-prem you don’t need to change any piece of application code that make them ingestible by AWS CloudWatch Logs*

*AWS official documentation in the FAQ section highlights the reusing capability with the sentence “AWS CloudWatch Logs lets you monitor and troubleshoot your systems and applications using your existing system, application and custom log files… so, no code changes are required.”*

*You can also leverage CloudWatch Metrics, Alarms and Dashboards with Logs to get full operational visibility into your applications. This empowers you to understand your applications, make improvements, and find and fix problems quickly, so that you can continue to innovate rapidly.* 

*Option D is INCORRECT because AWS Application Logs does not exist.*



<br>

**3. While reviewing the Auto Scaling events for your application, you notice that your application is scaling up and down multiple times in the same hour.**

**What changes would you suggest in order to optimize costs while preserving elasticity? (SELECT TWO)**

<strong>A.</strong> Modify the Auto Scaling group termination policy to terminate the older instance first. <br>
<strong>B.</strong> Modify the Auto Scaling group termination policy to terminate the newest instance first.  <br>
<strong>C.</strong> Modify the Auto Scaling group cool down timers. <br> 
<strong>D.</strong> Modify the Auto Scaling group to use Scheduled Scaling actions. <br>
<strong>E.</strong> Modify the CloudWatch alarm period that triggers your Auto Scaling scale down policy <br>

**Answer:** *C and E* <br>

*Here, not enough time is being given for the scaling activity to take effect and for the entire infrastructure to stabilize after the scaling activity. This can be maintained by increasing the Auto Scaling group CoolDown timers.*

*For more information on Auto Scaling CoolDown, please visit the* [Link](https://docs.aws.amazon.com/autoscaling/ec2/userguide/Cooldown.html)

*You will also have to define the right threshold for the CloudWatch alarm for triggering the scale down policy.*

*For more information on Auto Scaling Dynamic Scaling, please visit the* [Link](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scale-based-on-demand.html) 
 

<br> 

**4. Your company currently has a set of EC2 Instances hosted in AWS. The states of these instances need to be monitored and each state needs to be changed when a metric breaches a threshold value. Which step could be helpful to fulfill this requirement? (SELECT TWO)**

<strong>A.</strong> Use CloudWatch logs to store the state change of the instances. <br>
<strong>B.</strong> Create an Amazon CloudWatch alarm that monitors an Amazon EC2 instance <br>
<strong>C.</strong> Use SQS to trigger a record to be added to a DynamoDB table. <br>
<strong>D.</strong> Use AWS Lambda to store a change record in a DynamoDB table. <br>


**Answer:** *A and B*

**Create Alarms That Stop, Terminate, Reboot, or Recover an Instance**

*Using Amazon CloudWatch alarm actions, you can create alarms that automatically stop, terminate, reboot or recover your instances. You can use the stop or terminate actions to save money when you no longer need an instance. You can use the reboot and recover actions to automatically reboot those instances or recover them onto new hardware if a system impairment occurs.*

*The AWSServiceRoleForCloudWatchEvents service-linked role enables AWS to perform alarm actions on your behalf. The first time you create an alarm in the AWS Management Console, the IAM CLI, or the IAM API, CloudWatch creates the service-linked role for you.*

*There are a number of scenarios in which you might want to automatically stop or terminate your instance. For example, you might have instances dedicated to batch payroll processing jobs or scientific computing tasks that run for a period of time and then complete their work. Rather than letting those instances sit idle (and accrue charges), you can stop or terminate them, which could help you to save money. The main difference between using the stop and the terminate alarm actions is that you can easily restart a stopped instance if you need to run it again later, and you can keep the same instance ID and root volume. However, you cannot restart a terminated instance instead, you must launch a new instance.*

*You can add the stop, terminate, reboot or recover actions to any alarm that is set on an Amazon EC2 per-instance metric, including basic and detailed monitoring metrics provided by Amazon CloudWatch (in the AWS/EC2 namespace), as well as any custom metrics that include the InstanceId dimension, as long as its value refers to a valid running Amazon EC2 instance.*
 
*Option A is correct. Using Cloudwatch logs collect, store, view, and search logs from AWS and non-AWS resources.*

*Option B is correct. CloudWatch alarms are used to trigger notifications for any metric. Alarms can go to auto-scaling, EC2 actions(stop, terminate, recover, or reboot) and SNS notifications.*

*Option C is incorrect as SQS cannot be used for monitoring.*

*Option D is incorrect as AWS Lambda cannot be used for monitoring.*


<br>


**5. You have been designing a CloudFormation template that creates one elastic load balancer fronting two EC2 instances. Which section of the template should you edit so that the DNS of the load balancer is returned upon creation of the stack??**


<strong>A.</strong> Resources <br>
<strong>B.</strong> Parameters <br>
<strong>C.</strong> Outputs <br> 
<strong>D.</strong> Mappings

**Answer:** *C*

*Option A is incorrect because this is used to define the main resources in the template

*Option B is incorrect because this is used to define parameters which can taken in during template deployment*

*Option D is incorrect because this used to map key value pairs in a template*

*To understand more on CloudFormation, please visit the* [Link](https://aws.amazon.com/cloudformation/)



<br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Generate Password](https://github.com/clarusway/cw-workshop/blob/python/cc-15/python/coding-challenges/cc-015-Generate-Password/RADME.md) 



<br>



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
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Case study/Project</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>15m</p><td>                </tr>
</table>


**Case study should be explained to the students during the weekly meeting and has to be completed in one sprint (2 weeks) by the students. Students should work in small teams to complete the case study.**

- [Project-105 : Roman Numerals Converter Application (Python Flask) deployed on AWS EC2 with Cloudformation](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/aws/projects/105-roman-numerals-converter/README.md)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
