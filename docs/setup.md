# Hardware and Software Setup

## Hardware Configuration
- **Primary Control Machine**: Local machine equipped with an AMD Ryzen 5 9600X 6-Core Processor (3.90 GHz), 64.0 GB RAM (61.6 GB usable), and 932 GB storage (371 GB used). Configured as the local management hub for overseeing AWS EC2 instances.

## Software Setup
- **AWS EC2 Instances**: Launched and configured multiple instances including Windows Server 2019, Ubuntu Server 22.04, and Amazon Linux 2023. Utilized AWS Management Console to provision resources, leveraging EC2 for virtualization.
- **OpenVPN**: Installed and customized on an Ubuntu Server 22.04 instance to establish secure remote access to the lab environment.
- **Snort**: Deployed on an Amazon Linux 2023 instance as an intrusion detection system, showcasing network security expertise.

## Technical Achievements
- Successfully enabled virtualization support in local machine BIOS (VT-x/AMD-V) to support future local testing scenarios.
- Optimized EC2 instance performance by selecting appropriate instance types (e.g., t2.medium) based on workload requirements.
- Managed storage allocation, utilizing the local machine’s 932 GB capacity for backups and logs.
