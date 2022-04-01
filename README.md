# Project2 Setting Up Terraform Remote State Management

### PROJECT DESCRIPTION

> In this project, I have demonstrated a general approach which is followed when there are multiple users working on the  same shared terraform resources

> The script will first create a S3 bucket with versioning enabled for storing the tfstate file for a particular terraform project

> Then it will setup a DynamoDB table for users lock setup on that file

> For the shared resource we have to change the default backend plugin with s3 bucket confiugrations. 


https://user-images.githubusercontent.com/64367344/161304299-de7f3be6-6f54-43b8-a5a0-c5413dfc0b43.mp4

