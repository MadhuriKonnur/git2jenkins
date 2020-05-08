# git2jenkins
E2E conf of git to jenkins  and here  docker envs used for test  and prod (web server)

Problem Statement: Automation framework that github and jenkins to look for changes made to dev branch needs to be locally deployed and verified, parallelly tested by QA team seperately and only after the verification it has to be deployed to Production.

Assumptions: Some of the assumptions are made in this entire solution:
There are only 2 branches to compare and are availble readily
Git repo has a file like .html which can be easily deployed to apache and verified quickly
A simple httpd docker is used to deploy this html file 
Verification of the application is to navigate to the html from the specific docker IP:80 and makig sure changes are reflecting

For more details and creens shots refer  below link:
https://medium.com/@magicwordsmadhu/mlops-git-jenkins-integration-8f6286d55927
