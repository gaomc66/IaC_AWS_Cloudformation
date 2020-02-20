# infrastructure

## Based on AWS CLI and CLoudFormation 

```shell

    aws cloudformation create-stack \
    --stack-name csye6225demo \
    --parameters ParameterKey=InstanceTypeParameter,ParameterValue=t2.micro \
    --template-body file://template.json
```