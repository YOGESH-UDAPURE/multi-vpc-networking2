# Multi-VPC Networking Project 🌐

## Overview
Designed and implemented a Secure Multi-VPC Architecture 
on AWS with VPC Peering and Private Networking.

## Architecture
![VPC Architecture](architecture/vpc-diagram.png)

## Services Used
- ✅ Amazon VPC
- ✅ VPC Peering
- ✅ NAT Gateway
- ✅ Internet Gateway
- ✅ Route Tables
- ✅ EC2 Instances
- ✅ Security Groups

## Architecture Details

| Component | Details |
|-----------|---------|
| Production VPC | 10.0.0.0/16 |
| Management VPC | 10.1.0.0/16 |
| Prod Public Subnet | 10.0.1.0/24 |
| Prod Private Subnet | 10.0.2.0/24 |
| Mgmt Public Subnet | 10.1.1.0/24 |
| Mgmt Private Subnet | 10.1.2.0/24 |

## Features
- 🔒 Private & Public Subnet Separation
- 🔗 Secure VPC Peering Connection
- 🌐 NAT Gateway for Private Subnet
- 🛡️ Security Groups Configuration
- ✅ Secure Cross-VPC Communication

## Project Flow
