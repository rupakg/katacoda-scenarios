In this section, we will deploy our application to AWS Lambda, and then run it.

To deploy your application, click on the code block below to execute the command in your work environment.

`serverless deploy`{{execute}}

The output shows the details about the deployment.

Now, let's run our application, by invoking the `hello` function that we created.

`serverless invoke -f hello`{{execute}}

The output shows what we expected from the function.