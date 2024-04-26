# Commands used

- Initialize the project `cdk init app --language typescript`
- npm run build && cdk synth
- cdk bootstrap -- profile [accountName]

# Useful links

- website: https://cdkworkshop.com/20-typescript.html
- https://www.youtube.com/watch?v=T-H4nJQyMig&ab_channel=freeCodeCamp.org
- https://www.youtube.com/watch?v=TXXtiM8DUZc&list=PLp0uiiYgT8KxOAP_U7moyUPnTqY6KKTGY&ab_channel=JonathanMoo

# Welcome to your CDK TypeScript project

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkWorkshopStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template
