# Week 0 — Billing and Architecture
## Required Homework
### Install AWS CLI

#### tasks:
       
            - name: aws-cli
              env:
              AWS_CLI_AUTO_PROMPT: on-partial
              init: |
              cd /workspace
              curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
We'll also run these commands indivually to perform the install manually



## Create a new User and Generate AWS Credentials
 Go to (IAM Users Console](https://us-east-1.console.aws.amazon.com/iamv2/home?region=us-east-1#/users) andrew create a new user
Enable console access for the user
Create a new Admin Group and apply AdministratorAccess
Create the user and go find and click into the user
Click on Security Credentials and Create Access Key
Choose AWS CLI Access
Download the CSV with the credentials

## Enable Billig

In Root Account go to the Billing Page
Under Billing Preferences Choose Receive Billing Alerts
Save Preferences


