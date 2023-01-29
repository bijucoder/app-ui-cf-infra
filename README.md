# app-ui-cf-infra

## How to deploy

This repo has cloudfront and s3 repor related infra which is common to ui projects as a pre-requisite deploy step.

Below command can be used to deploy this to an aws profile name abmadev for example

```
 aws cloudformation deploy --template-file template.json --stack-name abma-app-cloudfront --profile abmadev --capabilities CAPABILITY_NAMED_IAM
```
