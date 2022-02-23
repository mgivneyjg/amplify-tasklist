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

If you navigate to each branch, this README doc will progressively explain how to build each step. 

## Technologies

__Front End__

* Facebook's [React](https://reactjs.org/) using React Hooks
* [Laco](https://www.npmjs.com/package/laco): a simplified state management library, with a react wrapper
* [PropTypes](https://www.npmjs.com/package/prop-types) a runtime type checking library for React props released by Facebook
* [Classnames](https://www.npmjs.com/package/classnames) A simple JavaScript utility for conditionally joining classNames together.
* [todomvc-app-css](https://www.npmjs.com/package/todomvc-app-css) CSS for TodoMVC apps


__Back End__: 

* [Amazon Amplify](https://docs.amplify.aws/) - An opinionated toolset to speed time to market with AWS serverless apps
* [AWS Cognito](https://docs.amplify.aws/lib/auth/getting-started/q/platform/js/) for user authentication
* [AWS AppSync](https://docs.amplify.aws/lib/graphqlapi/getting-started/q/platform/js/) for managed GraphQL services
* [AWS DynamoDB](https://docs.amplify.aws/lib/datastore/getting-started/q/platform/js/) for data storage
* [AWS CloudFront](https://docs.aws.amazon.com/amplify/latest/userguide/getting-started.html) for Content Delivery Network

