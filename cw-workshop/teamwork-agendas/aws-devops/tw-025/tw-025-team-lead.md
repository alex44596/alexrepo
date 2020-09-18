<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-25)</strong></span>

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

**1. What command should you run to see all running container in Docker?**

<strong>A.</strong> docker run  <br>
<strong>B.</strong> docker ps   <br>
<strong>C.</strong> docker --help <br> 
<strong>D.</strong> docker build   <br>
<strong>E.</strong> docker pull <br>



**Answer:** B

<br>

**2. Which of the following is not a state of Docker container?**

<strong>A.</strong> Running  <br>
<strong>B.</strong> Freezed   <br>
<strong>C.</strong> Paused <br> 
<strong>D.</strong> Restarting  <br>
<strong>E.</strong> Exited <br>

**Answer:** B


<br><br>
<br>
<br>
<br>



**3. Imagine that you just joined a development team that uses Git for version control and collaboration. To start contributing to the project, what Git operation would you most likely invoke first?**

<strong>A.</strong> checkout  <br>
<strong>B.</strong> clone   <br>
<strong>C.</strong> export <br> 
<strong>D.</strong> revert  <br>
<strong>E.</strong> update <br>


**Answer:** B


<br>

**4. Which of the following services are not supported by AWS Lambda?**


<strong>A.</strong> EC2  <br>
<strong>B.</strong> S3   <br>
<strong>C.</strong> Alexa <br> 
<strong>D.</strong> Cloudront  <br>
<strong>E.</strong> RedShift <br>

**Answer:** A

*To a certain extent, lambda and EC2 are competing technologies. While lambda aims to remove or drastically reduce the amount of configuration needed to run your software, EC2 exposes the developer to the virtual machine that ultimately runs their code. In addition lambda scales effortlessly while EC2 requires more complex configuration to achieve the same result.*

<br>


**5. Of the following, which are handled by Lambda by default? (choose 2)?**

<strong>A.</strong> Automatic scaling  <br>
<strong>B.</strong> Security patches   <br>
<strong>C.</strong> Triggers that activate the function <br> 
<strong>D.</strong> The lambda functions code  <br>


**Answer:** A and B

*Lambda provides auto scaling and security patches for the underlying operating systems that run your lambda functions.*
<br><br><br><br><br><br><br><br><br><br><br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. What is difference between virtualization and containerization?**

**Answer:** <br>

*Containers provide an isolated environment for running the application. The entire user space is explicitly dedicated to the application. Any changes made inside the container is never reflected on the host or even other containers running on the same host. Containers are an abstraction of the application layer. Each container is a different application.*

*Whereas in Virtualization, hypervisors provide an entire virtual machine to the guest(including Kernal). Virtual machines are an abstraction of the hardware layer. Each VM is a physical machine.*

<br>

**2. What are Docker Images?**


**Answer:**  <br>
*Docker image is the source of Docker container. In other words, Docker images are used to create containers. When a user runs a Docker image, an instance of a container is created. These docker images can be deployed to any Docker environment.*

<br>

**3. Explain Docker Architecture?**




**Answer:** 

*Docker Architecture consists of a Docker Engine which is a client-server application with three major components:*

- A server which is a type of long-running program called a daemon process (the docker command).
- A REST API which specifies interfaces that programs can use to talk to the daemon and instruct it what to do.
- A command line interface (CLI) client (the docker command). <br>

*The CLI uses the Docker REST API to control or interact with the Docker daemon through scripting or direct CLI commands. Many other Docker applications use the underlying API and CLI.*
   


**4. You are requested to expose your serverless application implemented with AWS Lambda to HTTP clients.( using HTTP Proxy )** <BR>
**Which of the following AWS services can you use to accomplish the task? (Select TWO)**


<strong>A.</strong> AWS Elastic Load Balancing (ELB)<br>
<strong>B.</strong> AWS Route53 <br>
<strong>C.</strong> AWS API Gateway <br> 
<strong>D.</strong> AWS Lightsail <br>
<strong>E.</strong> AWS Elastic Beanstalk <br> 



**Answer:** *A and C*

**Option A is CORRECT** *because AWS documentation mentions it “Application Load Balancers now support invoking Lambda functions to serve HTTP(S) requests. This enables users to access serverless applications from any HTTP client, including web browsers.* <br>
**Option B is INCORRECT** *because Route53 is a Domain Name System and not an HTTP proxy.* <br>
**Option C is CORRECT** *because API Gateway + Lambda is a common pattern for exposing serverless functions via HTTP/HTTPS. AWS documentation mentions it “Creating, deploying, and managing a REST application programming interface (API) to expose backend HTTP endpoints, AWS Lambda functions, or other AWS services”* <br>
**Option D is INCORRECT** *because AWS Lightsail has a completely different goal. It is a service to speed up provisioning of AWS resources.* <br>
**Option E is INCORRECT** *because AWS Elastic Beanstalk has a completely different goal. It is a service that makes easier for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.*



<br>

**5.A company wants to build a brand new application on the AWS Cloud. They want to ensure that this application follows the Microservices architecture. Which of the following services can be used to build this type of architecture? (SELECT THREE)**


<strong>A.</strong> AWS Lambda<br>
<strong>B.</strong> AWS ECS <br>
<strong>C.</strong> AWS API Gateway <br> 
<strong>D.</strong> AWS Config


**Answer:** *A, B and C* <br>

*AWS Lambda is a serverless compute service that allows you to build independent services.*<br>
*The Elastic Container Service (ECS) can be used to manage containers.* <br>
*The API Gateway is a serverless component for managing access to APIs.*<br>
*For more information about Microservices on AWS, please visit the following* [Link](https://aws.amazon.com/microservices/)  




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>




- [DevOps Pipeline](https://www.youtube.com/watch?v=DLIF9Gnyum4)


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



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Problem of the week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- Students should work in small teams to complete the problem of the week.


![POW](POW25.png)
<br>

**Answer:** *AMINO*

**Solution:** <br>

[Link](https://www.youtube.com/watch?v=2OSm-GwwoW4&list=PLhQjrBD2T3800qy4mK16nSThBr-_8J1Bb&index=10)



**Computational thinking:**

**Abstraction:** *Each card actually represents a letter.* 

**Decomposition:** There are 2 sub tasks that should be completed. One of them is finding the corresponding letter of each card and the other one is finding the best hand.* 


 <br> 

<table style= "width:96%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Presentation of Coding  Challenge & POW</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

We assume that each group has two sub teams. If this is possible one of the sub teams will present the coding challenge of last week. The other sub team will present the solution to the previous problem of the week. If there is only one sub team then, the sub team will present both of the solutions.



<br><br><br><br><br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>


- [Codding Challenge: Calculate Stock Profit](https://github.com/clarusway/clarusway-aws-devops-1-20/blob/master/python/coding-challenges/cc-007-calculate-stock-profit/README.md) 

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

- [Project-006 : Kittens Carousel Static Website deployed on AWS Cloudfront, S3 and Route 53 using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-1-20/tree/master/aws/projects/006-kittens-carousel-static-web-s3-cf)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
