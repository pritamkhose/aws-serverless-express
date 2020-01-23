# Express REST API on AWS Serverless Lambda
Sample project to depoly Node JS Express app REST API on AWS Lambda.

Getting Started
---------------
* Clone this repo (if you have not already):

  `git clone https://github.com/pritamkhose/aws-serverless-express.git`
  
  `cd aws-serverless-express`
  
  `npm install`
  
Important command
------------
* To config AWS Serverless (one time requirement):

  `serverless config credentials --provider aws --key {AWSAccesskeyID} --secret {AWSSecretAccessKey}`
  
* To create AWS Lambda Serverless project app on local folder:
  
  `serverless create -t aws-nodejs`
  
* To deploy Serverless app on AWS Lambda:

  `serverless deploy`
  
  `serverless deploy --stage production`

* To remove Serverless app from AWS Lambda:

  `serverless remove`

