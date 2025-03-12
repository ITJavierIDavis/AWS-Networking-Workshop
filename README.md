AWS Networking Workshop

Overview

This workshop provides a hands-on experience with Amazon Virtual Private Cloud (VPC) fundamentals, connectivity options, security controls, and network monitoring within AWS. By the end of this workshop, participants will have a deep understanding of networking components, best practices, and advanced configurations in AWS.

1. VPC Fundamentals

Amazon VPC

Understanding VPCs and their components

Creating a VPC using the AWS Management Console or AWS CLI

Subnets

Configuring public and private subnets

Understanding subnet CIDR blocks and availability zones

Network ACLs

Implementing Network ACLs for stateless traffic filtering

Configuring inbound and outbound rules

Route Tables

Associating route tables with subnets

Understanding route propagation

Internet Connectivity

Configuring an Internet Gateway (IGW)

Enabling internet access for public subnets

VPC Endpoints

Configuring Interface and Gateway Endpoints

Securing private connections to AWS services

EC2 Instances

Launching EC2 instances in a VPC

Assigning Elastic IPs and private IPs

Test Connectivity

Using ping, traceroute, and telnet for testing network reachability

Clean Up

Deleting resources to avoid unnecessary costs

2. Multiple VPCs

VPC Peering

Establishing VPC peering connections

Configuring route tables for cross-VPC communication

Transit Gateway (TGW)

Understanding AWS Transit Gateway

Connecting multiple VPCs and on-premises networks

TGW Route Tables

Managing route propagation across different VPCs

Clean Up

Removing peering connections and TGW configurations

3. Security Controls

Network ACLs

Implementing additional security rules at the subnet level

Security Groups

Configuring Security Groups for instance-level security

Defining inbound and outbound rules

Endpoint Policies

Restricting access using AWS Endpoint policies

Clean Up

Deleting security configurations and rules

4. Connecting to On-Premises

Establish VPN Connection

Creating a Site-to-Site VPN connection

Configuring Customer Gateway and Virtual Private Gateway

Explore Hybrid Environment

Integrating on-premises infrastructure with AWS

Configuring hybrid network setups

Hybrid DNS

Implementing AWS Route 53 Resolver for hybrid DNS resolution

Clean Up

Terminating VPN connections and related resources

5. Network Monitoring

CloudWatch

Using Amazon CloudWatch for network monitoring

Setting up CloudWatch alarms

VPC Flow Logs

Enabling and analyzing VPC Flow Logs for traffic monitoring

Clean Up

Disabling monitoring tools and deleting logs

6. Advanced Topics

AWS Gateway Load Balancer

Understanding AWS Gateway Load Balancer

Configuring traffic flow for security appliances

AWS Transit Gateway Multicast

Exploring multicast support in AWS Transit Gateway

Conclusion

By following this workshop, participants will gain practical experience in designing, implementing, and securing AWS network architectures. They will also be able to troubleshoot connectivity issues and optimize network performance within AWS environments.

