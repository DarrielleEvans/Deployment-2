# Deployment 2.0
* This application is a url-shortner. I will build and test the application on a Jenkins Server and I will deploy it in an AWS Elastic Beanstalk EC2.
* 
<img width="1308" alt="Screenshot 2023-08-26 at 8 48 47 AM" src="https://github.com/DarrielleEvans/Deployment-2/assets/89504317/8b3144d5-2164-4190-bb10-73f56b7b8d0a">

## Step 1
* I planned out my process to highlight how I will automate the build, test, and deployment process of my application.
* ![Deployment2 drawio](https://github.com/DarrielleEvans/Deployment-2/assets/89504317/e121a74d-cb79-4fd1-9d8e-43b490f6c2b8)

* I uploaded my application files to my repository on GitHub.
* I setup the Jenkins pipeline by inputting my Github Repository link and configuring the settings. After ensuring the settings were correct, I built the Pipeline.

*The pipeline paused after the testing stage. After resuming it manually, the stage and test were successful .
<img width="1205" alt="Screenshot 2023-08-25 at 10 05 58 PM" src="https://github.com/DarrielleEvans/Deployment-2/assets/89504317/f2aa2b86-d1cf-4515-8bcc-63f9c39d926f">

## Step 2
* I setup the appropriate Roles in IAM on AWS to deploy the application in Elastic Beanstalk.
<img width="1287" alt="Deployment 1 1 Degraded" src="https://github.com/DarrielleEvans/AWS-Deployment-1.1/assets/89504317/af2b6f46-8c98-4f78-a87f-b3e81c925dbd">
* The health status says pending but the website did deploy.


## Technologies Used
* AWS Beanstalk
* EC@
* Jenkins Server
* Github
  
