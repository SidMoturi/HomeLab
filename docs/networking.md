# Networking Configuration

## Overview
Designed a secure network for my home lab using AWS VPC and Security Groups, with OpenVPN and Snort for enhanced security.

## Network Setup
- **AWS VPC**: Configured a VPC with subnets to segment traffic across t2.micro instances (Windows Server 2019, Ubuntu Server 22.04, Amazon Linux 2023).
- **Security Groups**: Defined rules allowing SSH (port 22) and OpenVPN (port 1194) from my local machine.
- **OpenVPN**: Set up on Ubuntu Server 22.04 to enable secure remote access.
- **Snort**: Deployed on Amazon Linux 2023 to monitor and detect intrusions.

## Technical Achievements
- Implemented VLAN-like segmentation using AWS VPC.
- Secured network access with custom Security Group rules.
- Established encrypted connections with OpenVPN.
