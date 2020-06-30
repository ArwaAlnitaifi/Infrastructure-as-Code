# InfrastructureAsCode
In this project infrastructure as code for high-availability web app was designed and deployed using AWS CloudFormation, YAML, and JSON.


## How to Run
Run the following command in the terminal to create a stack in CloudFormation: 
```
./create.sh InfrastructureAsCodeUdacity file://InfrastructureAsCode.yml file://InfrastructureAsCodeParameters.json
```
OR alternative:
```
aws cloudformation create-stack --stack-name InfrastructureAsCodeUdacity --template-body file://InfrastructureAsCode.yml --parameters file://InfrastructureAsCodeParameters.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-west-2
```

