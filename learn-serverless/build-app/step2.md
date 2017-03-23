Let's get to the interesting part. We will create our first serverless application.

We will use the boilerplate templates provided by Serverless, to create a serverless Node.js application.

We will generate the application scaffolding, which will in turn generate an AWS Lambda function in Node.js.

`serverless create --template aws-nodejs --path hello-node`{{execute}}

Let's see what code was automatically generated for us.

`cd hello-node && ls`{{execute}}

We see that two files, `serverless.yml` and `handler.js` files were created.

`serverless.yml`: It's a YAML file, where you define your Functions, the Events that trigger them, and the Resources your Functions use.

`handler.js`: It's an application language specific file. Since we are creating a Node.js application, we have a JS file with our function defined here.

Okay, so we have our boilerplate code.

In the next section, we will inspect these files and change them a bit according to our needs.