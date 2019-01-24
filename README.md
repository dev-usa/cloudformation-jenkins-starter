# cloudformation-jenkins-starter

To setup stack via command line -

```
aws cloudformation create-stack --stack-name jenkinsStack --template-body file://jenkins.yaml --parameters ParameterKey=VpcId,ParameterValue=vpc-123 ParameterKey=EC2SubnetId,ParameterValue=subnet-123 ParameterKey=KeyName,ParameterValue=myKeyPair ParameterKey=InstanceType,ParameterValue=t2.micro --capabilities CAPABILITY_NAMED_IAM
```
