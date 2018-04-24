# CustomResource_CloudFormation

Simple example of a custom resource with CloudFormation that triggers a Lambda function

## Launch the prototype

* Create the Lambda function from LambdaCustomResource.js 
  * The Lambda handler name must be "index.handler"
  * The Lambda Timeout should be set at 10 sec
* Create a CloudFormation stack from customResource.yaml

> Tested with Node.js 4.3 for the Lambda function

