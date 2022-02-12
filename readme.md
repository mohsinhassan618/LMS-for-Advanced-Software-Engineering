# Fortgeschrittene Softwaretechnik

## A) Write a small pet project to get into coding again. You might want to use a language like Python which is also good for this Master! The code can be relatively simple (e.g. simple game with console output)

Created a learning management system with Lavravel and Vue js  

## B) Make sure each Person has applied the following topics on the code which have been taught in the lecture:
 #### 1) Use and understand Git!
 
Git is a type of version control system (VCS) that makes it easier to track changes to files. For example, when you edit a file, git can help you determine exactly what changed, who changed it, and why.

You can download git’s command-line interface (CLI) or can try GitHub Desktop (for Windows and Mac). This will be simpler to use, but will make it more difficult to really see what’s going on.

Common commands
 - git init
 - git clone 
 - git status
 - git branch <new-branch-name>
 - git add <files>
 - git commit


####  2) UML at least 3 good diagrams. "good" means you can pump it up artificially as written in DDD. You have 10 million $ from me! Please export the pics. I can not install all tools to view them!
I have Implemented the UML related to the project

- Activity Diagram [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Activity%20Daigram.png) 
- Use case diagram [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Usecase%20Workspace.png)
- Class Diagram [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Class%20UML.png) 


####  3) DDD If your domain is too small, invent other domains around and document these domains (as if you have 10 Mio € from EdlichInvestment!) Develop a clear strategic design with mappings/relationships with 5-0 Domains. It would be nice if these domains are derived from an Event-Storming (but not mandatory). 


#### 4) Metrics at least two. Sonarcube would be great. Other non-trivial metrics are also fine.

I have integrated SonarQube with laravel and attached the screen's below. For Quality Profiles for PHP I am using PSR2 as coding standard for PHP 
 

- [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Sonar.png)
- [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Sonar%20Project%20Overview.png) 
- [Click HEre](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Quality%20Profiles.png)


#### 5) Clean Code Development: at least 5 points you can show me with an explanation of why is this is clean code and/or what has improved+ >>10 points on your personal cheat sheet

 - Functions.
 - Formatting.
 - Objects and Data Structures.
 - Error handling.
 - Unit tests.
 - Class.


#### 6) Build Management with any Build System as Ant, Maven, Gradle, etc. (only Travis is perhaps not enough) Do e.g. generate Docs, call tests, etc. (it could be also disconnected from the project just to learn a build tool!)

For this project I am using Laravel builtin Artisan [Click Here](https://laravel.com/docs/8.x/artisan#introduction) and 
Node with webpack for Build. Maven can be integrated with Node but it does not serve any purpose here accept passing the commands to Node also I have tried it but it is generating errors while running jobs on Github Actions.   

We can run the following command on the project root to generate the build "npm run production"
Please review the screen shot [click here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/npm%20Build.png)
The command can be explored more in the following file on scripts section [click here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/package.json) 

####  7) Integrate some nice Unit-Tests in your Code to be integrated into the Build
We are using PHP unit library for running tests also redis cache needs to be enabled to successfully run the tests.
Please view the unit test stats [Click Here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/Unit%20tests.png)


####  8) Continuous Delivery: show me your pipeline using e.g. Jenkins, Travis-CI, Circle-CI, GitHub Action, GitLab CI, etc. E.g. you can also use Jenkins Pipelining or BlueOcean, etc. But at least insert more than 2 script calls as done in the lecture! (e.g. also call Ant or Gradle or something else).
I am using Github Actions and running two jobs one for build and second is for the unit tests. For more details are provided in root/.github/workflows/laravel.yml
Please review the screen shot [click here](https://github.com/mohsinhassan618/LMS-for-Advanced-Software-Engineering/blob/main/extra/CI%20CD.png) 

####  9) Use a good IDE and get fluent with it: e.g. IntelliJ. What are your favorite Key-Shortcuts?!

PHP Storm is my favorite IDE and I am using this from past five years 

Features 

-  Find in Path Directory level search of string  (ctrl + shift + F)
-  Find Declaration of any variable, function or class (ctrl+ b) 
-  Find implementations/usage of any variable, function or class in the whole project (ctrl+ b)
-  Replace in path (Ctrl + Shit+ R). you can replace a string not just in file but the complete project or directory of your choice  
-  Version Control integration 
-  Built in Terminal no need to use the OS CLI software
-  You can integrate lot of online available plugins and themes
-  The most accurate auto complete feature as compared to any other IDE
-  Spelling corrections
-  You can set the PHP coding Standards inside the IDE  

####  10) DSL Create a small DSL Demo example snippet in your code even if it does not contribute to your project (hence it can also be in another language).

#### 11) Functional Programming: prove that you have covered all functional aspects in your code as:

#
