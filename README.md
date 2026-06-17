1. What is Jenkins mainly used for?
 ans. B) Continuous Integration and Continuous Delivery

2. Which type of job allows you to define build steps using code
in Jenkins?
ans. A)pipeline project

3.  Which file is used to define a pipeline in Jenkins?
 ans. C)jenkinsfile

4. What is the purpose of a Jenkins Agent (Node)?
 ans. B)To execute jobs assigned by the Jenkins controller

5. Which plugin is required to connect Jenkins with GitHub?
ans. B) Git Plugin

6. What is the purpose of a Webhook in Jenkins CI/CD?
ans. B) To trigger build automatically on code push

7. Which command is used inside Jenkins Pipeline to execute
shell commands?
ans. C) sh

8. What is the purpose of post block in Jenkins Pipeline?
ans. B) Execute steps after pipeline stages

9. What is the use of sshagent in Jenkins Pipeline?
ans. C) Use stored SSH credentials during execution

10.  What happens if a stage fails in Jenkins Pipeline (by default)?
ans. C)the pipeline stop execution


Jenkins CI/CD Practical Test

Project Overview

This project demonstrates how to automate the deployment of a static website using Jenkins CI/CD Pipeline. Whenever changes are pushed to the GitHub repository, Jenkins automatically pulls the latest code and deploys the website to the target server.

Automated CI/CD pipeline using Jenkins
Source code management with GitHub
Automatic deployment after code changes
Easy and fast website updates
Continuous Integration and Continuous Deployment

Application Repositories

Application 1: FoodHub Restaurant Website
[repository]
(https://github.com/pramodzinjade/Food-Hub-Restaurant-website.git)

Application 2: ShopEase Website
[repository]
(https://github.com/pramodzinjade/shopEase-website-deployment.git)

Infrastructure Setup

create two server jenkins master and target server

Jenkins Server
install jenkins
install java
nstall required plugins
Configure SSH credentials
Verify Jenkins is accessible via browser

Target Server
Install nginx
Open port 80
Ensure websites are accessible from browser