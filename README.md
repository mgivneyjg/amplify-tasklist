# WAR WEEK 2022 - Todo MVC Amplified

This project is a progression through building a React app and deploying it to AWS using the Amazon Amplify toolkit.

As part of the program will take a React baseline application. Add hosting, user authentication, data persistence, add a custom resource and enable a CI/CD pipeline to support ongoing changes.... in about an hour.


## Branches

Each checkpoint in the session will be captured by a branch. The branches will be as follows:

|Branch Name|Description|
|-----------|-----------|
|01-baseline-app|this is the base TODO app we will "Amplify"|
|02-add-auth|adds Cognito authentication to the app|
|03-add-persistence|adds Dynamo persistence and a GraphQL API|
|04-add-custom-resource|shows you how to override Amplify behavior with CDK|
|05-hosting|deploys the app so it is hosted in the cloud|
|06-ci-cd|adds a Continuous Integration/Continuous Deploy pipeline|

## Technologies

__Front End__: React using React Hooks and the Laco state management library.

__Back End__: Cognito for auth, AppSync for GraphQL, DynamoDB for database, Lambda for Compute, Cloudwatch for Monitoring and Alarms.
