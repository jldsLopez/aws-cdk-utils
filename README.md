# aws-cdk
Lets play with aws cdk!

Lets supose you have severals cdk projects as part of your entery cloud solution, for example, you have a cdk project to create an EKS cluster where you are thinking to deploy some microservices and other cdk project to create an API of API Gateway to consume your microservices endpoints. Lets supose than in both proyects you have duplicate code, for example, you have an utils class where you put commons functions.

Here we are goin to create an aws cdk based library with TypeScript as Language , then we are goin to publish the final library to a public repository using NPM as package manager. You can use an aws codeArtifact repository or your prefered npm repository.

## Prerequisites
* TypeScript v4.0
* AWS CDK v1.100.0
* NPM v6.14.12
