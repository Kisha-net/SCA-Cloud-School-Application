<html>
   <body>
      <div class="myWrapper" markdown="1">
        <h1 align="center">SCA-Cloud-School-Application</h1> 
         <h2 align="center">Solution to Exercise 1</h1>
           <p>
Enlisted below are some of the steps I used in order to accomplish and be able to solve the first challenge for the Cloud Application challenge.
   1. I installed Jenkins in my PC and ensured it was running on port 8080. After that I created my account and I was able to access Jenkins services.
   
   2. On the github repo created ```https://github.com/kisha-net/SCA-Cloud-School-Application ``` I connected jenkins with my repo by navigating to the Settings option, and then to the webhooks section and added this ```http://kisha.com:8080/github-webhook``` payload url in order to connect my Jenkins server to my GitHub repository.
   
   3. I opened the Jenkins dashboard, clicked on create a new job option, enter my project name as ``` Python project ```, opted for the freestyle project and clicked ok to continue to the configuration section.
   
   4. I clicked on git under source control management and input the github repo url
   
   5. Under credentials, select Jenkins and input username and password you want to use and clicked on add to continue
   
   6. Under build triggers, check github hook trigger with GITScm polling
   
   7. Under build, select execute windows batch command and input what you have in the github repo i.e
           - i used Python for my submission so i had to execute the ``` python main.py ``` command so as to be able to run my Python script and I saved the settings of the project.
   
   8. I then built my project and it was able to run without any failure.
   
   9. After building, I clicked on ```#2 build option```(because the build job was the second build in my server) so as to view the console output of the build that was executed and it was able to print ``` Hello this is Antoinette working with python. ``` which was the text of my mini program that is in this repository.

- That is how I was able to handle the challange.
            </p>
         <h2 align="center">Login details(to access my jenkins server)</h2>
Username:```kisha```
Password:```kisha@254```
         
   <p align="center">Made with ❤️ from Kenya.</p>
         </div>
   </body>
</html>
