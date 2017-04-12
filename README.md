# node
Docker slave container with AWS tools for building node applications with node, angualar or serverless

see aws cli container for usage details
https://github.com/docker-jenkins-slave/aws_cli_docker


# version check
echo "aws_cli_docker"
java -version
aws --version

echo "node"
node --version
serverless --version
ng --version
eslint --version

# versions

v0.3
openjdk version "1.8.0_91"
aws-cli/1.11.76 Python/3.5.1+ Linux/3.13.0-106-generic botocore/1.5.39
serverless 1.10.2
@angular/cli: 1.0.0
node: 6.10.2
eslint v3.19.0

v0.2
openjdk version "1.8.0_91"
aws-cli/1.11.54 Python/3.5.1+ Linux/4.4.44-39.55.amzn1.x86_64 botocore/1.5.17
serverless 1.7.0
node: 6.9.1
eslint v3.16.1