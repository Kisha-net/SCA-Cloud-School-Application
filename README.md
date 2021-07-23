# SCA-Cloud-School-Application

## Solution to Exercise 1

Indicated below are some of the steps I used to be able to solve the first exercise of the Cloud Application challenge.
   1. I created an account with jenkins and i'm able to run my server on port 8080.
   2. On the github repo created, i connect jenkins with my repo by navigating to the settings, webhooks and i input my ipaddress:8080/webhook-github
   3. I opened the jenkins dashboard, click on new item, enter a project name, click on freestyle project and ok to continue
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
