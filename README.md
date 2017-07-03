# serverless-notes-api
An example of CRUD APIs utilising serverless architecture.

# setup:
-Create AWSaccount

-Create IAM user

-Install AWS CLI
 >install python with pip
 >via pip, run : "pip install awscli"
 >run : "aws configure"
 >insert access key & secret access key
 
-Create DynamoDB table
 >create table "notes" with primary keys "userId" & noteId
 
-Create S3 bucket

-Create cognito user pool & identity pool

-install nodejs/npm

-in serverless.yml, replace <SERVICE_NAME>, <AWS_REGION> and <COGNITO_POOL_ARN> with your own settings

-deploy APIs
 >run "serverles deploy"
