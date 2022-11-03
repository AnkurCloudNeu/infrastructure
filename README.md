# AWS CloudFormation

AWS CLI: https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html

aws cloudformation create-stack --stack-name myvpc --template-body file://infrastructure.yaml --profile "User Name" --capabilities CAPABILITY_NAMED_IAM
 
aws cloudformation update-stack --stack-name myvpc --template-body file://infrastructure.yaml --profile "User Name"