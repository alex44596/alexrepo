<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-8)</strong></span>

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

**1. The network address of 172.16.0.0/19 provides how many subnets and hosts?**

<strong>A.</strong> 7 subnets, 30 hosts each  <br>
<strong>B.</strong> 8 subnets, 8.190 hosts each  <br>
<strong>C.</strong> 8 subnets, 2.046 hosts each <br> 
<strong>D.</strong> 7 subnets, 2.046 hosts each  <br>

**Answer:** *B*


<br>

**2. What is the default subnet mask for a Class B address?**

<strong>A.</strong> 255.0.0.0 <br>
<strong>B.</strong> 255.255.0.0 <br>
<strong>C.</strong> 255.255.255.0 <br> 
<strong>D.</strong> 255.255.255.255  <br>

**Answer:** *B*

<br>

**3. Which of the following is NOT true for Python function?**

<strong>A.</strong> A function is a code block that only executes when it is called.
 <br>
<strong>B.</strong> Python function always returns a value.
  <br>
<strong>C.</strong> Python doesn’t support nested function
 <br> 
<strong>D.</strong> A function only executes when it is called and we can reuse it in a program
  <br>

**Answer:** *C*

<br> <br><br><br>

**4. A variable defined inside a function is referred to as __________.**


<strong>A.</strong> a global variable <br>
<strong>B.</strong> a function variable <br>
<strong>C.</strong> a block variable <br>
<strong>D.</strong> a local variable <br>

**Answer:** *D*

<br>


**5. Which command is used to manipulate TCP/IP routing table?**

<strong>A.</strong> ifconfig <br>
<strong>B.</strong> ping <br>
<strong>C.</strong> ipconfig <br> 
<strong>D.</strong> route   <br>
<strong>E.</strong> traceroute   <br>

**Answer:** *D*

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>



**1. You are planning on deploying a video based application onto the AWS Cloud. These videos will be accessed by users across the world. Which of the below services can help stream the content in an efficient manner to the users across the globe?**


<strong>A.</strong> Amazon Route 53 <br>
<strong>B.</strong> Amazon Cloudtrail <br>
<strong>C.</strong> Amazon CloudFront <br> 
<strong>D.</strong> Amazon S3



**Answer:** *C*

*Amazon CloudFront is a web service that gives businesses and web application developers an easy and cost effective way to distribute content with low latency and high data transfer speeds. Like other AWS services, Amazon CloudFront is a self-service, pay-per-use offering, requiring no long term commitments or minimum fees. With CloudFront, your files are delivered to end-users using a global network of edge locations.*


*For more information on Amazon Cloudfront, please refer to the* [Link](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

<br>

**2. There is a website hosted in AWS that might get a lot of traffic over the next couple of weeks. If the application experiences a natural disaster at this time, what should be used to reduce potential disruption to users?**

<strong>A.</strong> Use an ELB to divert traffic to an Infrastructure hosted in another region. <br>
<strong>B.</strong> Use an ELB to divert traffic to an Infrastructure hosted in another AZ.
<br>
<strong>C.</strong> Use CloudFormation to create backup resources in another AZ. <br> 
<strong>D.</strong> Use Route53 to route requests to another instance in a different region. <br>


**Answer:** *D*<br>

*In a disaster recovery scenario, the best choice out of all given options is to divert the traffic to a static website.*<br>
*Option A is wrong because ELB can only balance traffic in one region, not across multiple regions.*<br>
*Options B and C are incorrect because using backups across AZs is not enough for disaster recovery purposes.*
 
*For more information on disaster recovery in AWS, please visit the* [Link1](https://aws.amazon.com/premiumsupport/knowledge-center/fail-over-s3-r53/), [Link2](https://aws.amazon.com/disaster-recovery/)

*The wording "to reduce the potential disruption in case of issues" is pointing to a disaster recovery situation. There is more than one way to manage this situation. However, we need to choose the best option from the list given here. Out of this, the most suitable one is Option D.*<br>
*Most organizations try to implement High Availability (HA) instead of DR to guard them against any downtime of services. In the case of HA, we ensure there exists a fallback mechanism for our services. The service that runs in HA is handled by hosts running in different availability zones but in the same geographical region. This approach, however, does not guarantee that our business will be up and running in case the entire region goes down.*<br>
*DR takes things to a completely new level, wherein you need to be able to recover from a different region that is separated by over 250 miles. Our DR implementation is an Active/Passive model, meaning that we always have minimum critical services running in different regions, but a major part of the infrastructure is launched and restored when required.*<br>
*For more information on large scale disaster recovery using AWS regions, please visit the* [Link](https://aws.amazon.com/blogs/startups/large-scale-disaster-recovery-using-aws-regions/) 



<br>

**3. A company has an entire infrastructure hosted on AWS. It requires to create code templates used to provision the same set of resources in another region in case of a disaster in the primary region. Which AWS service can be helpful in this regard?**

<strong>A.</strong> AWS Beanstalk <br>
<strong>B.</strong> AWS CloudFormation  <br>
<strong>C.</strong> AWS CodeBuild <br> 
<strong>D.</strong> AWS CodeDeploy <br>

**Answer:** *B* <br>

*AWS CloudFormation provisions your resources in a safe and repeatable manner, allowing you to build and rebuild your infrastructure and applications, without having to perform manual actions or write custom scripts. CloudFormation takes care of determining the right operations to perform while managing your stack and rolls back changes automatically if errors are detected.*

*For more information on AWS CloudFormation, please visit the*
[Link](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) 

*AWS Beanstalk - is an orchestration service for deploying applications which orchestrates various AWS Services, including EC2, S3, SNS, CloudWatch, AutoScaling, and ELB.*

*AWS CodeBuild - is a fully managed continuous integration(CI) service that compiles source code, run tests, and produces software packages that are ready to deploy. Using it, you don't need to provision, manage, and scale your own build servers.*

*AWS CodeDeploy - is a service that automates application deployments to a variety of compute services including EC2, Fargate, Lambda, and on-premises instances. It protects your application from downtime during deployments through rolling updates and deployment health tracking.*

<br> 

**4. You are working as an AWS Architect for a start-up company. The company has web-servers deployed in all AZ’s in the eu-central-1 (Frankfurt) region. These web servers have German news & local web content for people accessing these websites within Germany. These web servers have multiple records created for a single domain. The company is looking for a random selection of web-servers that will increase its availability. What would be the most appropriate routing policy for this requirement?**

<strong>A.</strong> Latency routing policy <br>
<strong>B.</strong> Weighted routing policy <br>
<strong>C.</strong> Multivalue answer routing policy <br>
<strong>D.</strong> Geolocation routing policy <br>


**Answer:** *C*

*When Route 53 is configured with Multi-value answer routing, it returns multiple values for web-servers. Route 53 responds to DNS queries with up to eight healthy records and traffic is approximately load-balanced between these multiple web-servers.*

*Option A is incorrect. Latency routing policy is used when multiple resources are mapped with single domain & resource with the best latency to the resource is provided. Since most of the times these servers will be accessing locally from the German region, latency to the web servers will be approximately the same.*

*Option B is incorrect. Weighted routing policy is used when multiple resources are mapped with a single domain & you need to route traffic in a weighted proportionate to each resource. As in this case, the requirement is to use all web servers randomly, the weighted routing policy will not be an ideal option.*

*Option D is incorrect as Geolocation routing policy is used to choose resources based upon the user's location. In this case, all users will be Germany-based & so there would not be random selection on the resource.*

*For more information on using Multi-value Answer Routing for Route 53, refer to the* [Link](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-multivalue) 

<br>


**5. Which of the following components of the Cloudfront service can be used to distribute contents to users across the globe.?**


<strong>A.</strong> Amazon VPC <br>
<strong>B.</strong> Amazon Regions <br>
<strong>C.</strong> Amazon Availability Zones <br> 
<strong>D.</strong> Amazon Edge locations

**Answer:** *D*

*Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations.*

*For more information on Amazon Cloudfront, please refer to the* [Link](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)



<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coding  Challenge</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>


- [Check Consecutive Vowels](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/tree/master/python/coding-challenges/cc-007-check-consecutive-vowels) 



<br>



<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



- [Working with Amazon CloudFront](https://www.youtube.com/watch?v=Ideptk0sJcM)



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

- [Project-104 : Kittens Carousel Static Website deployed on AWS Cloudfront, S3 and Route 53 using Cloudformation](https://github.com/clarusway/clarusway-aws-devops-pro-3-20/tree/master/aws/projects/104-kittens-carousel-static-web-s3-cf)
<br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
