# ECS Web Server on Fargate

The quick tutorial found: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/tutorial-ecs-web-server-cdk.html

This simple example creates a large list of resources with a simple construct.

## Resources
* AWS::ElasticLoadBalancingV2::LoadBalancer
* AWS::EC2::SecurityGroup
* AWS::EC2::SecurityGroupEgress
* AWS::ElasticLoadBalancingV2::Listener
* AWS::ElasticLoadBalancingV2::TargetGroup
* AWS::IAM::Role
* AWS::ECS::TaskDefinition
* AWS::Logs::LogGroup
* AWS::IAM::Role
* AWS::IAM::Policy
* AWS::ECS::Service
* AWS::EC2::SecurityGroup
* AWS::EC2::SecurityGroupIngress
* AWS::ECS::Cluster
* AWS::EC2::VPC
* AWS::EC2::Subnet
* AWS::EC2::RouteTable
* AWS::EC2::SubnetRouteTableAssociation
* AWS::EC2::Route
* AWS::EC2::EIP
* AWS::EC2::NatGateway
* AWS::EC2::Subnet
* AWS::EC2::RouteTable
* AWS::EC2::SubnetRouteTableAssociation
* AWS::EC2::Route
* AWS::EC2::EIP
* AWS::EC2::NatGateway
* AWS::EC2::Subnet
* AWS::EC2::RouteTable
* AWS::EC2::SubnetRouteTableAssociation
* AWS::EC2::Route
* AWS::EC2::Subnet
* AWS::EC2::RouteTable
* AWS::EC2::SubnetRouteTableAssociation
* AWS::EC2::Route
* AWS::EC2::InternetGateway
* AWS::EC2::VPCGatewayAttachment
* Custom::VpcRestrictDefaultSG
* AWS::IAM::Role
* AWS::Lambda::Function
* AWS::CDK::Metadata


The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template
