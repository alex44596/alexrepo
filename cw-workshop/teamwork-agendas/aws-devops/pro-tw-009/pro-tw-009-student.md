<h1><strong><span style="color: #77C8D5;">sTUDENT VERSION (Week-9)</strong></span>

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


<br>

**2. A ________ routing table contains information entered manually.**

<strong>A.</strong> static <br>
<strong>B.</strong> dynamic <br>
<strong>C.</strong> hierarchical <br> 
<strong>D.</strong> none of the above  <br>


<br>

**3. Python supports the creation of anonymous functions at runtime, using a construct called __________?**

<strong>A.</strong> anonymous <br>
<strong>B.</strong> Pi <br>
<strong>C.</strong> lambda <br> 
<strong>D.</strong> built-in   <br>


<br><br><br><br><br><br><br><br>

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


<br>


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



<br>

**2. You are the architect of a custom application running inside your corporate data center. The application runs with some unresolved bugs that produce a lot of data inside custom log files generating time-consuming activities to the operation team who is responsible for analyzing them.**

**You want to move the application to AWS using EC2 instances, and at the same time, take the opportunity for improving logging and monitoring capabilities but without touching the application code.**

**What AWS service should you use to satisfy the requirement?**

<strong>A.</strong> AWS Kinesis Data Streams <br>
<strong>B.</strong> AWS CloudTrail <br>
<strong>C.</strong> AWS CloudWatch Logs <br> 
<strong>D.</strong> AWS Application Logs <br>



<br>

**3. While reviewing the Auto Scaling events for your application, you notice that your application is scaling up and down multiple times in the same hour.**

**What changes would you suggest in order to optimize costs while preserving elasticity? (SELECT TWO)**

<strong>A.</strong> Modify the Auto Scaling group termination policy to terminate the older instance first. <br>
<strong>B.</strong> Modify the Auto Scaling group termination policy to terminate the newest instance first.  <br>
<strong>C.</strong> Modify the Auto Scaling group cool down timers. <br> 
<strong>D.</strong> Modify the Auto Scaling group to use Scheduled Scaling actions. <br>
<strong>E.</strong> Modify the CloudWatch alarm period that triggers your Auto Scaling scale down policy <br>


<br> 

**4. Your company currently has a set of EC2 Instances hosted in AWS. The states of these instances need to be monitored and each state needs to be changed when a metric breaches a threshold value. Which step could be helpful to fulfill this requirement? (SELECT TWO)**

<strong>A.</strong> Use CloudWatch logs to store the state change of the instances. <br>
<strong>B.</strong> Create an Amazon CloudWatch alarm that monitors an Amazon EC2 instance <br>
<strong>C.</strong> Use SQS to trigger a record to be added to a DynamoDB table. <br>
<strong>D.</strong> Use AWS Lambda to store a change record in a DynamoDB table. <br>



<br>


**5. You have been designing a CloudFormation template that creates one elastic load balancer fronting two EC2 instances. Which section of the template should you edit so that the DNS of the load balancer is returned upon creation of the stack??**


<strong>A.</strong> Resources <br>
<strong>B.</strong> Parameters <br>
<strong>C.</strong> Outputs <br> 
<strong>D.</strong> Mappings




<br>

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
