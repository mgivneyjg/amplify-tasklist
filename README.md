# WAR WEEK 2022 - Todo MVC Amplified

Welcome to the War Week 2022 tech session on AWS Amplify. Amplify is a set of purpose-built tools and features that lets frontend web and mobile developers quickly and easily build full-stack applications on AWS, with the flexibility to leverage the breadth of AWS services as your use cases evolve.

To accomplish this training, we are going to take an existing React app and deploy it, with the features you'd expect to have in a production grade application, to the Amazon Cloud. Along the way we will add user authentication with Amazon Cognito, data persistence with AWS AppSync and DynamoDB and deploy it to a content delivery network within the Amplify service. In addition, we will add a CI/CD pipeline so any future changes to the application will automatically build and deploy to the environment. Lastly, we will make a customization of the default Amplify behavior, so we can demonstrate that the framework (while opinionated) is very customizable.

## How this course is organized

Each of the lessons will be captured in a README document in a separate numbered branch. This course is meant to be progressive and as you should navigate through each of the branches __in order__, completing the steps, deploy the changes to your account and commiting your source code to the `main` branch in your own repository. If you get stuck, please contact [Matt Givney](mailto:mgivney@jahnelgroup.com) and I will be happy to jump on Slack and help you.

## Branches

As mentioned, each set of instructions will be captured by a branch. The branches will be as follows:

|Branch Name|Description|
|-----------|-----------|
|01-baseline-app|this is the base TODO app we will "Amplify"|
|02-add-auth|adds Cognito authentication to the app|
|03-add-persistence|adds Dynamo persistence and a GraphQL API|
|04-add-custom-resource|shows you how to override Amplify behavior with CDK|
|05-hosting|deploys the app so it is hosted in the cloud|
|06-ci-cd|adds a Continuous Integration/Continuous Deploy pipeline|

If you navigate to each branch, this README doc will progressively explain how to build each step. 

### Technologies

Amplify is not specifically a technology for React, it can also be used with Vue, Angular, Vanilla JS as well as other UI frameworks and Mobile toolkits. We are using React in this project, as it is the most common framework for web development projects at JG.

Here is an overview of all the tech being used in this project.

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

## How this course is intended to be used

We will start off with a React app as the baseline of our product. You will setup the Amplify toolset on your local machine, fork the repository and then begin walking through the branches (in order) in order to get to the final deliverable.

Each branch will consist of a set of incremental steps to add backend capabilities to your application, "productionizing" it as we go. At the end, you will have written a fully functioning application with CI/CD pipeline running in the AWS cloud.

Get your tools installed and account configured and let's get started!

---

__IMPORTANT!__
> Prior to starting this course, you should have Node/NPM (12.x +) and the AWS Amplify CLI installed. These are all very straight-forward to  setup, so they are omitted for the sake of brevity. 
>
> The documentation provides a walkthrough of how to install and configure the [AWS Amplify CLI](https://docs.amplify.aws/cli/start/install/), please have your software installed, CLI configured against your account _prior_ to attempting this course.

---

If you are ready to start, navigate to the branch `01-baseline-app` and get ready to dominate!
