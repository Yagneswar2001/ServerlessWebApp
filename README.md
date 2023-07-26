# ServerlessWebApp

# Description:
The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

# Steps of building Serverless Web Application 

# Host a Static Website: 
Configure AWS Amplify to host the static resources for your web application with continuous deployment built in

# Manage Users: 
Create an Amazon Cognito user pool to manage your users' accounts
# Build a Serverless Backend: 
Build a backend process for handling requests for your web application
# Deploy a RESTful API: 
Use Amazon API Gateway to expose the Lambda function you built in the previous module as a RESTful API
