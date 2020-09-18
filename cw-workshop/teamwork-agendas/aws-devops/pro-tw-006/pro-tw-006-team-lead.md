<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-6)</strong></span>

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

**1. What is** `$ top` **command used for in linux?**

<strong>A.</strong> to change the read, write, and execute permissions of files and directories <br>
<strong>B.</strong> to display the running processes dynamically   <br>
<strong>C.</strong> to check your connectivity status to a server <br> 
<strong>D.</strong> to download files from the internet   <br>

**Answer:** B

<br>

**2. Which one of the following options are correct about python dictionaries?**

<strong>A.</strong> Dictionaries are mutable <br>
<strong>B.</strong> Dictionaries are accessed by key
<br>
<strong>C.</strong> Dictionaries can be nested to any depth <br> 
<strong>D.</strong> All of the above<br>

**Answer:** D

<br>

**3. Which piece of hardware would reduce the size of a broadcast domain?**
 
<strong>A.</strong> Hub <br>
<strong>B.</strong> Router  <br>
<strong>C.</strong> Packet injector <br> 
<strong>D.</strong> Switch <br>

**Answer:** B

<br><br><br><br>

**4. What is the purpose of the OSI model?**

<strong>A.</strong> Enable users to access the internet
 <br>
<strong>B.</strong> Improve the network performance by compressing data
  <br>
<strong>C.</strong> To provide a set of standards for manufacturers
 <br> 
<strong>D.</strong> Make network devices such as a router, switch, hub communicate with each other
  <br>

**Answer:** C

<br>



**5. Which layer provides the logical addressing that routers will use for path determination?**

<strong>A.</strong> Network Layer <br>
<strong>B.</strong> Datalink Layer  <br>
<strong>C.</strong> Transport Layer <br> 
<strong>D.</strong> Physical Layer   <br>

**Answer:** A

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. You have a requirement to host a static website following the best practices for a domain named mycompany.com in AWS.**

**How would you set up this? (SELECT TWO)**

<strong>A.</strong> DHost the static site on an EC2 Instance.
 <br>
<strong>B.</strong> Use Route53 with a static web site in S3. <br>
<strong>C.</strong> Enter the DNS records from Route53 in the hosted zones..
 <br> 
<strong>D.</strong>  Place the EC2 instance behind the ELB. <br>



**Answer:** *B and C*<br>


*You can host a static website in S3. You need to ensure that the nameserver records for the Route53 hosted zone are entered in your domain registrar.*

*For more information on website hosting in S3, please visit the following links:*<br> [Link-1](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html) , 
[Link-2](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/RoutingToS3Bucket.html) 


<br>

**2. A company hosts 5 web servers in AWS. They want to ensure that Route53 can be used to route user traffic to random healthy web servers when they request for the underlying web application. Which routing policy should be used to fulfill this requirement?**

<strong>A.</strong> Simple <br>
<strong>B.</strong> Weighted  <br>
<strong>C.</strong> Multivalue Answer <br> 
<strong>D.</strong> Latency



**Answer:** *C* <br>

*If you want to route traffic randomly to multiple resources such as web servers, you can create one multivalue answer record for each resource and, optionally, associate an Amazon Route 53 health check with each record.*

*For example, suppose you manage an HTTP web service with a dozen web servers where each has its own IP address. No web server could handle all the traffic, but if you create a dozen multivalue answer records, Amazon Route 53 responds to DNS queries with up to eight healthy records in response to each DNS query. Amazon Route53 gives different answers to different DNS resolvers. If a web server becomes unavailable after a resolver caches a response, client software can try another IP address in the response.*

*For more information, please visit the following* 
[Link](https://aws.amazon.com/about-aws/whats-new/2017/06/amazon-route-53-announces-support-for-multivalue-answers-in-response-to-dns-queries/) 

<br> 

**3. Which of the following statements are FALSE when it comes to elasticity. Choose 2 answers from the options given below.**

<strong>A.</strong> Diverting traffic to instances based on the demand <br>
<strong>B.</strong> Diverting traffic to instances with the least load <br>
<strong>C.</strong> Diverting traffic across multiple regions <br>
<strong>D.</strong> Diverting traffic to instances with higher capacity <br>


**Answer:** *C and D*

*The concept of Elasticity is the means of an application having the ability to scale up and scale down based on demand. An example of such a service is the Autoscaling service*


**4. Your team has developed an application and now needs to deploy that application onto an EC2 Instance. This application interacts with a DynamoDB table. Which of the following is the correct and MOST SECURE way to ensure that the application interacts with the DynamoDB table?**

<strong>A.</strong> Create a role which has the necessary permissions and can be assumed by the EC2 instance<br>
<strong>B.</strong> Use the API credentials from an EC2 instance. Ensure the environment variables are updated with the API access keys.
 <br>
<strong>C.</strong> Use the API credentials from a bastion host. Make the application on the EC2 Instance send requests via the bastion host.
<br> 
<strong>D.</strong> Use the API credentials from a NAT Instance. Make the application on the EC2 Instance send requests via the NAT Instance


**Answer:** A

*IAM roles are designed in such a way so that your applications can securely make API requests from your instances, without requiring you to manage the security credentials that the applications use.
Options B, C, and D are invalid because it is not secure to use API credentials from any EC2 instance. The API credentials can be tampered with and hence is not the ideal secure way to make API calls.*

*For more details on AWS Credentials, please refer the*
[Link](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey_API) 


*For more information on IAM roles for EC2, please refer the* [Link](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html) 



<br>

**5. A consulting firm repeatedly builds large architectures for their customers using AWS resources from several AWS services including IAM, Amazon EC2, Amazon RDS, DynamoDB and Amazon VPC. The consultants have architecture diagrams for each of their architectures, and are frustrated that they cannot use them to automatically create their resources.**

**Which service should provide immediate benefits to the organization?**

<strong>A.</strong> CAWS Beanstalk
 <br>
<strong>B.</strong> AWS CloudFormation <br>
<strong>C.</strong>  AWS CloudFront
 <br> 
<strong>D.</strong> AWS CodeDeploy



**Answer:** *B*

*AWS CloudFormation: This supplements the requirement in the question and enables consultants to use their architecture diagrams to construct CloudFormation templates.*

*AWS Documentation mentions the following on AWS CloudFormation:
AWS CloudFormation is a service that helps you model and set up your Amazon Web Service resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you.*

*For more information on AWS Cloudformation, please visit the following* [Link](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) 

 
*AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js etc. You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring.*

*In question mentioned that "A consulting firm repeatedly builds large architectures for their customers using AWS resources from several AWS services including IAM, Amazon EC2, Amazon RDS, DynamoDB and Amazon VPC."*

*When you are building large architectures repeatedly, you can use the cloud formation template so that create or modify an existing AWS CloudFormation template. A template describes all of your resources and their properties. When you use that template to create an AWS CloudFormation stack, AWS CloudFormation provisions the Auto Scaling group, load balancer, and database for you. After the stack has been successfully created, your AWS resources are up and running. You can delete the stack just as easily, which deletes all the resources in the stack. By using AWS CloudFormation, you easily manage a collection of resources as a single unit. whenever working with more number of AWS resources together, cloud formation is the best option.*


<br><br><br><br><br><br><br><br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Find the Most Frequent Letter](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/blob/master/python/coding-challenges/cc-005-find-the-most-frequent-letter/README.md)



<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [What are Microservices?](https://www.youtube.com/watch?v=CdBtNQZH8a4)



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
