# Udacity - Deploy a high-availability web app using CloudFormation
# uocnh1

## Spin up instructions
The project included are:
-   diagram: diagram image
-   template: cloudformation templates for deployment
-   script files

## Tear down instructions
Create network-template: ./create.sh <name-network> network.yml  network-parameters.json
Create webapp-template: ./create.sh <name-webapp> udagram.yml  udagram-parameters.json

Update network-template: ./update.sh <name-network> network.yml  network-parameters.json
Update webapp-template: ./update.sh <name-webapp> udagram.yml  udagram-parameters.json

Delete network-template: ./delete.sh
Delete webapp-template: ./delete.sh
# Test
Load Balancer URL: http://projec-webap-syn4opzkkj3x-1349088147.us-east-1.elb.amazonaws.com/
