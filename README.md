# serverless-cop
# Serverless-CDK-Environment-Setup
This repository is created to help developers who want to use CDK+AWS Serverless tech stack to develop microservice based application for their backend.
In this tutorial/repository, you will learn to setup your development environment. Since I am a Mac user, most of the commands are compatible with Mac/Linux. 


## Hardware Requirements
- Macbook Pro/Air/iMac, Linux, Windows, etc
- Desk, Chair
- Internet
- Cloud9 or your terminal

## Services
- AWS Account for development which I call it Dev account
- Github Account

## Software Requirements
- iTerm2
- Node.js > V16 + npm | yarn
- AWSCli
- Python >V3.0 + pip
- typescript
- AWS CDK > V2.5
- VS Code
- Git

## Let's start and Setup your development environment
After installing the software mentioned above, let's start setting up your terminal to use AWS account and github account you have created.
- Setup your AWSCli and setup your secret & access keys as stated below:
```
aws configure
> AWS Access Key : 
> AWS Secret Access Key: 
> Default region: us-e-1
> default output: json
```
- Setup your gitcli
```
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
$ cat ~/.ssh/id_rsa.pub
```
Copy paste the public key into your github account -> settings -> ssh key


# Create a CDK App
- Create an empty folder in your workspace call it `hello-app`
- `cd hello-app`
- Run the cdk command to create a new cdk app
```
$ cdk init app --language typescript
```

