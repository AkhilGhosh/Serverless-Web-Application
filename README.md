# Serverless-Web-Application
A simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet.

######################

The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.


Application architecture:
-------------------------

1. Static Web Hosting: AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the 
                       user's browser.
2. User Management: Amazon Cognito provides user management and authentication functions to secure the backend API.
3. Serverless Backend: Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.
4. RESTful API: JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.


#######################

AWS Services Using :
--------------------

1. AWS Lambda
2. Amazon API Gateway
3. Amazon DynamoDB
4. Amazon Cognito
5. AWS Amplify Console
6. Amazon Simple Email Service


* Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files 
  which are loaded in the user's browser.
* JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.
* Amazon Cognito provides user management and authentication functions to secure the backend API.
* DynamoDB provides a persistence layer where data can be stored by the API's Lambda function
