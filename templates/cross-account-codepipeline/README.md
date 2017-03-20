# Cross-account CodePipeline

 - Client setup multi account for security reasons, conways law, blast radius ...

## Concepts

 - KMS
 - 3 Accounts: Infra, Staging, Prod
 - CodePipeline
 - CloudFormation (but can be every other account)

## Files

### pipeline.yaml

 - CloudFormation template which describes the delivery pipeline
 

### staging.yaml

TBD

### prod.yaml

TBD

## References

 - [AWS: Create a Pipeline in AWS CodePipeline That Uses Resources from Another AWS Account](http://docs.aws.amazon.com/codepipeline/latest/userguide/pipelines-create-cross-account.html)