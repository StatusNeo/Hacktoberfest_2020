<h1 align="center"><b>Getting Started With Jenkins</b></h1>

<p align="center">
  <img src="img/Installation of Jenkins & Simple job/jenkins.png" height=300 width=500>
</p>

<p><b><h2>Jenkins</h2> It is a DevOps tool for Continous Integration and Delivery. It is written in Java with its plugins built for Integration purposes. It is Open Source and so available to all the developers they can collaborate easily. </p>

<p><h2>Features:</h2>
<ul>
<li>Easy Configuration</li>
<li>Easy Installation</li>
<li>Available Plugins</li>
<li>Extensible</li>
<li>Easy Distribution</li>
<li>Free Open Source</li>
</ul>

<p>Let’s get started by installing Jenkins.
In this tutorial, I will be using Windows OS.

As Jenkins is written in Java, we need to install Java. Go to this link and install JDK for your system: https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/1jdk.PNG" height=300></p><br><br>


Let’s copy the location of our JDK as we will need this to set environments variables.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/2 jdk in folder.PNG" height=300></p><br><br>

We will add variable as JAVA_HOME and the provide location of the JDK folder.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/3 java home env setup.PNG" height=300></p><br><br> 	 


We will check if java is available by typing the command: “java -version” 
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/4 cmd java installed.PNG" height=300></p><br><br>

Now, let’s move and download Jenkins
https://www.jenkins.io/download/ I have downloaded jenkins.war file
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/5 download jenkins.PNG" height=300></p><br><br>



Now, you can see that jenkins.war file has been downloaded.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/6 jenkinswar file.PNG" height=100></p><br><br>






Now, we will run Jenkins by command: “java -jar jenkins.war”
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/7 java start using cli.PNG" height=300></p><br><br>





Move to your browser and type “localhost:8080”. You will see a screen like this. Here, the password asked is available in the location provided in your local machine.
Just go to that location and paste the password here. 
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/8 passowrd required.PNG" height=300></p><br><br>








Click on install suggested Plugins
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/9 cusomize jenkins.PNG" height=300></p><br><br>




Jenkins will download all required plugins.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/9.1 plugins.PNG" height=300></p><br><br>





Reset your credentials.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/9.2 id pass.PNG" height=300></p><br><br>




Now, you are ready to play with Jenkins.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/9.3 ready jenkins.PNG" height=300></p><br><br>


Enter Your credentials here to console.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/10 pass id.PNG" height=300></p><br><br>





You will be having no projects for the first time.
On the left side you can see various features of Jenkins, eg; New Item, People, Build History, Manage Jenkins, etc.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/11 manage jenkins.PNG" height=300></p><br><br>







Let’s have a walkthrough Jenkins and its features.
In new items, you can see various type of projects can be made in Jenkins.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/13.PNG" height=300></p><br><br>




Inside people, you can see all the members you have created and edit their accessibility.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/14.PNG" height=300></p><br><br>









Inside Build History, you can check all the build done by you and their sta
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/15.PNG" height=300></p><br><br>





Inside, Manage Jenkins you can check for System Configuration and security
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/16.PNG" height=300></p><br><br>


In system configuration, inside plugins, you can check for various plugins
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/16.1.PNG" height=300></p><br><br>

Status Information, Troubleshooting, and Tools and Actions.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/17.PNG" height=300></p><br><br>









Simple Project

In this project, we will just make Jenkins open cmd and run an echo command with the message of Simple Project 1 and build it.







Click on New Item >> Name the project as “Simple Project 1”  >> take the project as Freestyle Project. 
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/18.1.PNG" height=300></p><br><br>









You can configure the project: 
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/Simple Project 1 Config [Jenkins]-1.jpg" height=700></p><br><br>
<p align="center"><img src="img/Installation of Jenkins & Simple job/Simple Project 1 Config [Jenkins]-2.jpg" height=700></p><br><br>

You can build the project by clicking the Build Now and then it will start building the project automatically.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/18.2.PNG" height=300></p><br><br>

You can see that project has built easily.
<br><p align="center"><img src="img/Installation of Jenkins & Simple job/18.3.PNG" height=300></p><br><br>

That’s all! For this module. We will continue learning more cool features of Jenkins in next module.

</p>