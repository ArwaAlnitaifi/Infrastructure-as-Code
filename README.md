# InfrastructureAsCode
In this project infrastructre as code for high-availability web app was designed and deployed using AWS CloudFormation, YAML, and JSON. 


## How to Run
Download InfrastructureAsCode.yml and InfrastructureAsCodeParameters.json files then run the following command in the terminal to create a stack in CloudFormation: 
```
aws cloudformation create-stack --stack-name InfrastructureAsCodeUdacity --template-body file://InfrastructureAsCode.yml --parameters file://InfrastructureAsCodeParameters.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-west-2
```

