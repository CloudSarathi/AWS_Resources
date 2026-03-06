# AWS

<img width="1400" height="691" alt="image" src="https://github.com/user-attachments/assets/e457f0af-8d16-40c7-9093-abc295851cba" />

**Note**: Some of the exercises <b>cost $$$</b> and can't be performed using the free tier/resources

**2nd Note**: The provided solutions use the AWS console. It's recommended you'll use IaC technologies to solve the exercises (e.g. Terraform, Pulumi).<br>

- [AWS](#aws) 
  - [Exercises](#exercises) 
    - [IAM](#iam) 
    - [EC2](#ec2)
    - [S3](#s3)
    - [ELB](#elb)
    - [Auto Scaling Groups](#auto-scaling-groups)
    - [VPC](#vpc)
    - [Databases](#databases)
    - [DNS](#dns)
    - [Containers](#containers)
    - [Lambda](#lambda)
    - [Elastic Beanstalk](#elastic-beanstalk)
    - [CodePipeline](#codepipeline)
    - [CDK](#cdk)
    - [Misc](#misc)
  - [Questions](#questions)
    - [Global Infrastructure](#global-infrastructure)
    - [IAM](#iam-1)
    - [EC2](#ec2-1)
      - [AMI](#ami)
      - [EBS](#ebs)
      - [Instance Store](#instance-store)
      - [EFS](#efs)
      - [Pricing Models](#pricing-models)
      - [Launch Template](#launch-template)
      - [ENI](#eni)
      - [Placement Groups](#placement-groups)
    - [VPC](#vpc-1)
      - [Default VPC](#default-vpc)
    - [Lambda](#lambda-1)
    - [Containers](#containers-1)
      - [ECS](#ecs)
      - [Fargate](#fargate)
    - [S3](#s3-1)
      - [Basics](#basics)
      - [Buckets 101](#buckets-101)
      - [Objects](#objects)
      - [S3 Security](#s3-security)
      - [Misc](#misc-1)
    - [Disaster Recovery](#disaster-recovery)
    - [CloudFront](#cloudfront)
    - [ELB](#elb-1)
      - [NLB](#nlb)
      - [ALB](#alb)
    - [Auto Scaling Group](#auto-scaling-group)
    - [Security](#security)
    - [Databases](#databases-1)
      - [RDS](#rds)
      - [Aurora](#aurora)
      - [DynamoDB](#dynamodb)
      - [ElastiCache](#elasticache)
      - [RedShift](#redshift)
    - [Identify the Service](#identify-the-service)
    - [DNS (Route 53)](#dns-route-53)
    - [SQS](#sqs)
    - [SNS](#sns)
    - [Monitoring and Logging](#monitoring-and-logging)
    - [Billing and Support](#billing-and-support)
      - [AWS Organizations](#aws-organizations)
    - [Automation](#automation)
    - [Misc](#misc-2)
    - [High Availability](#high-availability)
    - [Production Operations and Migrations](#production-operations-and-migrations)
    - [Scenarios](#scenarios)
    - [Architecture Design](#architecture-design)
    - [Misc](#misc-3)
   
## Exercises

### IAM

|Name|Topic|Objective & Instructions|Solution|Comments|
|--------|--------|------|----|----|
| Create a User | IAM | [Exercise](exercises/create_user/exercise.md) | [Solution](exercises/create_user/solution.md) | |
| Password Policy | IAM | [Exercise](exercises/password_policy_and_mfa/exercise.md) | [Solution](exercises/password_policy_and_mfa/solution.md) | |
| Create a role | IAM | [Exercise](exercises/create_role/exercise.md) | [Solution](exercises/create_role/solution.md) | |
| Credential Report | IAM | [Exercise](exercises/credential_report/exercise.md) | [Solution](exercises/credential_report/solution.md) | |
| Access Advisor | IAM | [Exercise](exercises/access_advisor/exercise.md) | [Solution](exercises/access_advisor/solution.md) | |

### EC2

|Name|Topic|Objective & Instructions|Solution|Comments|
|--------|--------|------|----|----|
| Launch EC2 web instance | EC2 | [Exercise](exercises/launch_ec2_web_instance/exercise.md) | [Solution](exercises/launch_ec2_web_instance/solution.md) | |
| Security Groups | EC2 | [Exercise](exercises/security_groups/exercise.md) | [Solution](exercises/security_groups/solution.md) | |
| IAM Roles | EC2, IAM | [Exercise](exercises/ec2_iam_roles/exercise.md) | [Solution](exercises/ec2_iam_roles/solution.md) | |
| Spot Instances | EC2 | [Exercise](exercises/create_spot_instances/exercise.md) | [Solution](exercises/create_spot_instances/solution.md) | |
| Elastic IP | EC2, Networking | [Exercise](exercises/elastic_ip/exercise.md) | [Solution](exercises/elastic_ip/solution.md) | |
| Placement Groups Creation | EC2, Placement Groups | [Exercise](exercises/placement_groups/exercise.md) | [Solution](exercises/placement_groups/solution.md) | |
| Elastic Network Interfaces | EC2, ENI | [Exercise](exercises/elastic_network_interfaces/exercise.md) | [Solution](exercises/elastic_network_interfaces/solution.md) | |
| Hibernate an Instance | EC2 | [Exercise](exercises/hibernate_instance.md) | [Solution](exercises/hibernate_instance/solution.md) | |
| Volume Creation | EC2, EBS | [Exercise](exercises/ebs_volume_creation/exercise.md) | [Solution](exercises/ebs_volume_creation/solution.md) | |
| Snapshots | EC2, EBS | [Exercise](exercises/snapshots/exercise.md) | [Solution](exercises/snapshots/solution.md) | |
| Create an AMI | EC2, AMI | [Exercise](exercises/create_ami/exercise.md) | [Solution](exercises/create_ami/solution.md) | |
| Create EFS | EC2, EFS | [Exercise](exercises/create_efs/exercise.md) | [Solution](exercises/create_efs/solution.md) | |
