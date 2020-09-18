<h1><strong><span style="color: #77C8D5;">TEAM LEAD VERSION (Week-26)</strong></span>

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

**1. Which file is used to define dependency in Maven?**

<strong>A.</strong> build.xml  <br>
<strong>B.</strong> pom.xml <br>
<strong>C.</strong> dependency.xml <br> 
<strong>D.</strong> version.xml  <br>



**Answer:** B

<br>

**2. What is the requirement for using Jenkins? (Choose 2 answers from the options given below)**

<strong>A.</strong> A source code repository which is accessible, for instance, a Git repository  <br>
<strong>B.</strong> A working build script, e.g., a Maven script, checked into the repository   <br>
<strong>C.</strong> Installed Docker <br> 
<strong>D.</strong> None <br>


**Answer:** A and B


<br>

**3. Which of the following commands runs Jenkins from the command line?**


<strong>A.</strong> java -jar jenkins.war  <br>
<strong>B.</strong> java -war jenkins.jar   <br>
<strong>C.</strong> java -jar jenkins.jar <br> 
<strong>D.</strong> java -war jenkins.war  <br>


**Answer:** A

<br>

**4. How can we setup Jenkins jobs?**

<strong>A.</strong> Select new item from the menu  <br>
<strong>B.</strong> After that enter a name for the job and select free-style job   <br>
<strong>C.</strong> Then click OK to create new job in Jenkins <br> 
<strong>D.</strong> The next page enables you to configure your job  <br>
<strong>E.</strong> All of these <br>


**Answer:** E


<br>




**5. Containers include the application and all of its dependencies, but share the kernel with other containers. They run as an isolated process in userspace on the host operating system. They're also not tied to any specific infrastructure – Docker containers run on any computer, on any infrastructure, and in any cloud.**

<strong>A.</strong> True <br>
<strong>B.</strong> False <br>

**Answer:** A

<br>


<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview/Certification Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

**1. What is the default Docker network driver, and how can you change it when running a Docker image?**

**Answer:** <br>

*Docker provides different network drivers like bridge, host, overlay, and macvlan. bridge is the default.*

*Sometimes you might want to use Docker Swarm or connect your containers to your host network directly. In these cases, you’ll need to change your default network driver.*

*First, you have to create a new network with the new network driver by using the --driver or -d parameter with your docker network create command. Then you’ll need to run your Docker image with the --network parameter to use your newly-created network.*

<br>

**2. How will you monitor Docker in production?**


**Answer:** 

*Docker provides functionalities like `docker stats` and `docker events` to monitor docker in production. `docker stats` provides CPU and memory usage of the container. `docker events` provide information about the activities taking place in the docker daemon.* 

<br>

**3. What is Docker Compose? What can it be used for?**


**Answer:**  <br>
*Docker Compose is a tool that lets you define multiple containers and their configurations via a YAML or JSON file.*

*The most common use for Docker Compose is when your application has one or more dependencies, e.g., MySQL or Redis. Normally, during development, these dependencies are installed locally—a step that then needs re-doing when moving to a production setup. You can avoid these installation and configuration parts by using Docker Compose.*

*Once set up, you can bring all of these containers/dependencies up and running with a single docker-compose up command.*

<br>





**4. What is Maven? What is the benefit of integrating Maven with Jenkins?**


**Answer:** 

*Maven is a build management tool. It uses a simple pom.xml to configure all the dependencies needed to build, test and run the code. Maven manages the full lifecycle of a test project. Once integrated with Jenkins, the maven Webdriver will build the project and execute all tests efficiently.*



<br>

**5.What are the advantages of Jenkins?**


**Answer:**

*Advantage of Jenkins includes:*

- *Bugs tracking are easy at early stage in development environment.*<br>
- *Provides a large numbers of plugin support.* <br>
- *Iterative improvement to the code.* <br>
- *Build failures are cached at integration stage.* <br>
- *For each code commit changes an automatic build report notification generates.* <br>
- *To notify developers about build report success or failure, it is integrated with LDAP mail server.* <br>
- *Achieves continuous integration agile development and test driven development.*<br>
- *With simple steps, maven release project is automated.*  <br>




<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>




- [What is Continuous Integration?](https://www.youtube.com/watch?v=1er2cjUq1UI)


<br> <br> <br>

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


![POW](POW26.png)
**Answer:** *KAPLINSKY*

**Solution:** [Link](https://www.youtube.com/watch?v=8Uj9M-6LGgQ&list=PLhQjrBD2T3800qy4mK16nSThBr-_8J1Bb&index=6)



**Computational thinking:**

**Pattern Recognition:** The quote is talking about Scrabble. Also, the scratched letters and the uncompleted looking like words are associated with the game of Scrabble. So we should continue on repeating the pattern and playing the game of Scrabble.

Also on the last part of the puzzle by recognizing that quote and all the words that you have found are associated with dancing. So in the final part, you have to google dancing and the word you have found in order to find the related answer.

**Decomposition:** Try to find each word and work on them separately. Also, there is a second part of the problem in which you have to figure out the letters that you need. After you figure that out you have to google the word that you have found by combining those letters. 

**Algorithm Design:** <br>
**Part 1:**<br>
- Find the word by placing the letters from below. 
- If you find another word with letters that were used previously, change the letter or look for another word.
- Repeat 1-2 until all of the words found without duplicate letters. 

**Part 2:**<br>
- Pick the letters that are indicated by the number next to the words.
- Repeat 2 until you find all the letters.

**Part3:** <br> 
- Google the word and other associated words you found. 


 <br> 

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


- [Coding Challenge: Security Questions](/https://github.com/clarusway/clarusway-aws-devops-1-20/tree/master/python/coding-challenges/cc-008-validate-customers-with-security-questions) 

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



<br><br><br>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

-Next week’s plan

-QA Session 

<hr>
