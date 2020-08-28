# Community::CloudFormation::Delay

## Installation using AWS CLI
``` bash
aws cloudformation register-type \
  --type-name Community::CloudFormation::Delay \
  --type RESOURCE \
  --schema-handler-package s3://community-resource-provider-catalog/community-cloudformation-delay-0.1.0.zip

aws cloudformation set-type-default-version
```