<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-27)</strong></span>

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

**1. What are the advantages of Jenkins?**

<strong>A.</strong> At integration stage, build failures are cached <br>
<strong>B.</strong> For each code commit changes an automatic build report notification generates <br>
<strong>C.</strong> To notify developers about build report success or failure, it is integrated with LDAP mail server <br> 
<strong>D.</strong> All of the above  <br>



**Answer:** *D*

<br>

**2. What are the useful plugins in Jenkins? (choose three)**

<strong>A.</strong> Maven 2 project <br>
<strong>B.</strong> Anaconda  <br>
<strong>C.</strong> HTML publisher <br> 
<strong>D.</strong> Amazon EC2 <br>
<strong>E.</strong> Sublime text 3 <br>


**Answer:** *A,C and D*


<br><br><br><br><br><br><br><br>

**3.What is this command used for?**
```
$ sudo docker run -i -t alpine /bin/bash
```

<strong>A.</strong> to stop the docker container  <br>
<strong>B.</strong> to see all running container in Docker   <br>
<strong>C.</strong> to run the image as a container <br> 
<strong>D.</strong> to copy the docker container <br>


**Answer:** *C*

<br>

**4. You can't create multiple containers from the same image?**

<strong>A.</strong> True  <br>
<strong>B.</strong> False <br>

**Answer:** *B*


<br>

**5. Which of the following commands will merge `branch-a` into the `master` branch?**

<strong>A.</strong> `git checkout branch-a` and `git merge master`  <br>
<strong>B.</strong> `git clone branch-a` and `git merge master`  <br>
<strong>C.</strong> `git checkout master` and `git merge branch-a` <br> 
<strong>D.</strong> `git branch branch-a` and `git merge master` <br>


**Answer:** *C*

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. A team is planning to host data on the AWS Cloud. Following are the key requirements: <br> - Ability to store data as JSON documents <br> - High availability and durability** 

**Select the ideal schemaless storage mechanism that should be employed to fit this requirement?**

<strong>A.</strong> Amazon EFS  <br>
<strong>B.</strong> Amazon Redshift  <br>
<strong>C.</strong> DynamoDB  <br> 
<strong>D.</strong> AWS CloudFormation <br>


**Answer:** *C*

*AWS Documentation mentions the following on DynamoDB:*
- Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. <br>
- The data in DynamoDB is stored in JSON format and hence is the perfect data store for the requirement in question. <br>
- DynamoDB is a NoSQL database and is schemaless.

*For more information on AWS DynamoDB, please visit the following* [Link](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

Note: As per AWS Docs <br>
*"DynamoDBMapper has a new feature that allows you to save an object as a JSON document in a DynamoDB attribute. The mapper does the heavy work of converting the object into a JSON document and storing it in DynamoDB. DynamoDBMapper also takes care of loading the Java object from the JSON document when requested by the user."*



<br>

**2. Which of the following are valid integration sources for API Gateway? (choose 3 options)**

<strong>A.</strong> Public facing HTTP-based endpoints outside AWS network.  <br>
<strong>B.</strong> Lambda functions from another account.   <br>
<strong>C.</strong> Database connections on internet outside AWS network.   <br> 
<strong>D.</strong> VPC Link E. SFTP connection
 <br>



**Answer:** *A, B and D*

*Option A is correct. AWS API Gateway can integrate with any HTTP-based endpoints available over the internet.*<br>
*Option B is correct. AWS can use Lambda function from another account as an integration type.* <br>
*Option C is incorrect. AWS API gateway can connect to AWS services which will make proxy calls only to their respective AWS APIs. There is no integration type for database connections directly from API Gateway. You can use Lambda function to connect with database and make Lambda as integration type for API Gateway.*<br>
*Option D is correct. AWS has introduced VPC Link, a way to connect to the resources within a private VPC.*


<br>

**3. You have a web application hosted on AWS VPC with a single EC2 instance with Auto Scaling enabled. You have also assigned elastic IP address to the EC2 instance. When you access the elastic IP address, you are able to successfully connect to your web application. You decided to route requests to your application from a custom domain through Route 53. You have performed the setup on Route 53. However, when you access your custom domain name from the internet, you get “Server Not Found” error. Which of the following could be a reason?**


<strong>A.</strong> Route 53 service is for internal application routing. It does not support routing trac from the internet.   <br>
<strong>B.</strong> You must configure elastic load balancer in order to use Route 53 for web application hosting.  <br>
<strong>C.</strong> IP address configured in Route 53 DNS record set might be incorrect.   <br> 
<strong>D.</strong>  The resource on EC2 instance that you're routing trac to is unavailable. <br>

**Answer:** *C* <br>

*Option A and B are not valid statements.* <br>
*Although option D looks correct, the question states the connection to the web application was successful when connected through elastic IP address. So this option is not the cause of failure.*


<br>

**4. What is the best way to create Docker images?**


**Answer:** 

*Always create Docker images using a Dockerfile. Dockerfiles are text documents that specify a clear series of steps that the daemon should use to create an image. They are easy for other engineers to read and change.*

*Don’t create images by making a container, changing it by hand, then running ‘docker commit’. This may create an image, but it will be challenging for other engineers to reproduce the image.*



<br>

**5. How Can You Clone A Git Repository Via Jenkins?**


**Answer:**

*If you want to clone a Git repository via Jenkins, you have to enter the e-mail and user name for your Jenkins system. Switch into your job directory and execute the “git config” command for that.*  <br>




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Top 7 Cloud Infrastructure Interview Questions](https://www.youtube.com/watch?v=yulGNwmync0)


<br> <br><br><br><br><br>

<table style= "width:97%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Retro Meeting on a personal and team level</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

Ask the questions below:

- What went well? 
- What could be improved? 
- What will we commit to do better in the next week? 



<table style= "width:96%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Presentation of Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

We assume that each group has two sub teams. If this is possible one of the sub teams will present the coding challenge of last week. The other sub team will present the solution to the previous problem of the week. If there is only one sub team then, the sub team will present both of the solutions.



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- [Find the Non-Repeated Values](https://github.com/clarusway/clarusway-aws-devops-1-20/blob/master/python/coding-challenges/cc-009-find-non-repeated-values/README.md)

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


**Case study should be explained to the students during the weekly meeting and has to be completed in one week by the students. Students should work in small teams to complete the case study.**

- [Project-202: Dockerization of Bookstore Web API (Python Flask) with MySQL](https://github.com/clarusway/clarusway-aws-devops-1-20/blob/master/devops/projects/202-dockerization-bookstore-api-on-python-flask-mysql/README.md)



<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
