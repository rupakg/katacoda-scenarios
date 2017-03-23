In this section, we will inspect the files for our applications and change them a bit according to our needs.



Now, that we have our changes in, it is time that we deploy our application to AWS Lambda.

But, before we do that, we need to configure [Serverless with the AWS credentials](https://serverless.com/framework/docs/providers/aws/guide/credentials/). 

Simply, set the AWS credentials like so:

`serverless config credentials --provider aws --key yourkey --secret your secret`{{execute}}

Once, we are done with setting the AWS credentails, we can now deploy our application.