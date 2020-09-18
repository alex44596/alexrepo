<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-29)</strong></span>

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

**1. By default, all manager nodes are also worker nodes and are capable of executing tasks when they have the resources available to do so. (Docker Swarm)**

<strong>A.</strong> True <br>
<strong>B.</strong> Flase <br>




**Answer:** *A*

<br>

**2. Which command is used to initialize Docker Swarm mode?**

<strong>A.</strong> docker swarm create <br>
<strong>B.</strong> docker init swarm <br>
<strong>C.</strong> docker swarm init <br> 
<strong>D.</strong> docker swarm run
<br>



**Answer:** *C*


<br>

**3. Replication Controller makes sure that a pod or a homogeneous set of pods is always up and available? (Kubernetes)** 


<strong>A.</strong> True <br>
<strong>B.</strong> Flase <br>


**Answer:** *A*

<br>

**4. Which one is used to help restricting the service within the cluster?  (Kubernetes)**

<strong>A.</strong> LoadBalancer  <br>
<strong>B.</strong> NodePort  <br>
<strong>C.</strong> ClusterIP <br> 
<strong>D.</strong> kubectl <br>


**Answer:** *C*


<br>

**5. If you want to make radical changes to your team's project and don't want to impact the rest of the team, you should implement your change in  _________. (Git)**

<strong>A.</strong> the root  <br>
<strong>B.</strong> a tag <br>
<strong>C.</strong> the trunk<br> 
<strong>D.</strong> None of the above


**Answer:** *D*

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. Your organization is planning to use AWS ECS for docker applications. However, they would like to apply 3rd party monitoring tools on the ECS instances. They approached you asking for a recommendation. What do you suggest?**

<strong>A.</strong> AWS ECS is a managed service. Customers cannot install 3rd party softwares. Use CloudWatch for monitoring metrics. <br>
<strong>B.</strong> Customers will have control over AWS ECS instances and can setup monitoring like a normal EC2 instance.  <br>
<strong>C.</strong>  Raise a case with AWS to install 3rd party software on ECS. AWS will review the case and install if 3rd party software is in their trusted software entries. <br> 
<strong>D.</strong> AWS ECS is a managed service. Customers cannot install 3rd party softwares. Use application level monitoring.



**Answer:**  *B*

*Options A and D are not correct. AWS ECS uses EC2 instances with ECS-optimized AMI. You will have root access to the instances and you can manage them.*

*Option C is not a valid statement*

*For more information on ECS instances,* [Link](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_instances.html)





<br><br><br><br><br>

**2.  Which of the following are the parameters specified in task definition? (Amazon ECS) (choose 3 options)**

<strong>A.</strong> The Docker images to use with the containers in your task. <br>
<strong>B.</strong> EC2 instance types to be used as container instances. <br>
<strong>C.</strong> How much CPU and memory to use with each container.  <br> 
<strong>D.</strong> AWS VPC and subnets to launch containers in.
<br>
<strong>E.</strong> The command the container should run when it is started.
<br>



**Answer:** *A, C and E*

*Option B and D are paramters specified in creating an ECS cluster.*



<br>

**3. What is a pod in Kubernetes?**

**Answer:** 

*Pod is a single or bunch of containers that is controlled as a single application*

- *Containers inside the Pod operate closely together and share a common life cycle, but has to be scheduled on the same node.*
- *Pods are managed as a unit and share common environment wrt volume and IP address space.*
- *Every Pods consists of master container that satisfies of balancing the workload among the other containers that facilitate to orchestrate other related tasks.*
- *For example, a pod may have one container running the primary application server and a helper container pulling down files to the shared file system when changes are detected in an external repository.*
- *Users are recommended not to manage pods themselves, because they might miss few features specifically needed in applications.* 
- *Users are advised to operate with the objects that use pod templates as base components and add additional functionality to them.*


<br>

**4. What is Kubectl?**

**Answer:** 

*Kubectl is a Kubernetes command-line tool that is used for deploying and managing applications on Kubernetes. Kubectl is especially useful for inspecting the cluster resources, and for creating, updating, and deleting the components.*



<br>

**5. Do all of the nodes have to be at the same size in your cluster? (kubernetes)**


**Answer:**

*No, they don’t. The Kubernetes components, like kubelet, will take up resources on your nodes, and you’ll still need more capacity for the node to do any work. In a larger cluster, it often makes sense to create a mix of different instance sizes. That way, pods that require a lot of memory with intensive compute workloads can be scheduled by Kubernetes on large nodes, and smaller nodes can handle smaller pods.*  <br>




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
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


- [Generate Password](https://github.com/clarusway/cw-workshop/blob/python/cc-15/python/coding-challenges/cc-015-Generate-Password/RADME.md)

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

- [Project-203: Docker Swarm Deployment of Phonebook Application (Python Flask) with MySQL](https://github.com/clarusway/cw-workshop/tree/python/cc-15/devops/projects/203-docker-swarm-deployment-of-phonebook-app-on-python-flask-mysql)



<br><br><br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
