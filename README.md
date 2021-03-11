# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands
 *  resources & dependencies
  ------------- tools dependencies
 *  AWS account
 *  node installation https://nodejs.org/en/download/
 *  npm install -g aws-cdk
 *  cdk --version
 -------------- execution
 * cdk init --language typescript
   -------------- project dependencies
*  npm install @aws-cdk/aws-ec2 @aws-cdk/aws-ecs @aws-cdk/aws-ecs-patterns
 ------------- cdk commands
 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
