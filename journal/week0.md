# Week 0 — Billing and Architecture
## Required Homework
### Install AWS CLI

## tasks:
       
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
