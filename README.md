# SCA-Cloud-School-Application

## Solution to Exercise 1

Enlisted below are some of the steps I used in order to accomplish and be able to solve the first challenge for the Cloud Application challenge.
   1. I installed Jenkins in my PC and ensured it was running on port 8080. After that I created my account and I was able to access Jenkins services.
   2. On the github repo created ```https://github.com/kisha-net/SCA-Cloud-School-Application ```, 
         - I connect jenkins with my repo by navigating to the Settings option, and then to the webhooks section and I input 
         ```http://kisha.com:8080/github-webhook``` payload url in order to connect my Jenkins server to my GitHub repository.
   3. I opened the Jenkins dashboard, clicked on create a new job option, enter my project name as ``` Python project ```, opted for the freestyle project and clicked ok to continue to the configuration section.
   4. Check github project and input the github repo url in the space provided
   5. Click on git under source control management and input the github repo url
   6. Under credentials, select jenkins and input username and password you want to use, click add to continue
   7. Under build triggers, check github hook trigger with GITScm polling
   8. Under build, select execute windows batch command and input what you have in the github repo e.g i used python so i have print('hello world) and saved the configuration            settings of the project.
   9. I then built my project and it was able to run without any failure.
   10. After building, I clicked on #2 to view the console output of the build that was executed and it was able to print the text of my mini program that is in this repository.

#### Login details(to access my jenkins server)
Username:
```
kisha
```
Password:
```
kisha@254
```
   Made with ❤️ from Kenya.
