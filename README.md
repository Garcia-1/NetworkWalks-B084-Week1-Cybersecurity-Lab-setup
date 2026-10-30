# NetworkWalks-B084-Week1-Cybersecurity-Lab-setup


## Overview
This repository documents the successful completion of Week 1: Cybersecurity Lab Setup as part of the Networkwalks Cybersecurity Internship Program (Batch B084).
The objective of this project was to build a secure and functional cybersecurity lab environment using Kali Linux and Oracle VirtualBox. This environment will serve as the foundation for future cybersecurity exercises and hands-on security training throughout the internship program.

## Objectives 
* Install and configure Oracle VirtualBox
* Create and configure a private NAT Network
* Deploy a Kali Linux virtual machine
* Configure shared file access between host and guest systems
* Establish network connectivity and DNS functionality
* Create a consistent IP for the Kali VM
* Create a clean recovery point for future lab activities
* Document the setup process

## Lab Setup Steps
#### Step 1: Download Required Software

VirtualBox and Kali Linux Setup Files were downloaded from their official websites.

<img width="297" height="75" alt="VirtualBox and Kali Linux Setup Files" src="https://github.com/user-attachments/assets/2d5cf9cb-b781-41eb-96a5-e245403c8ff9" />

#### Step 2: Install VirtualBox
Oracle VirtualBox was installed as the hypervisor.

<img width="1897" height="1008" alt="VirtualBox Installation" src="https://github.com/user-attachments/assets/b95a8a40-2952-4f26-b61c-6267d50af1ea" />

#### Step 3: Create the NAT Network
An isolated NAT Network was created in VirtualBox to allow multiple machines to communicate with each other in the lab environment. The configurations can be viewed in the image below.

<img width="1897" height="1008" alt="Screenshot 2026-10-30 061156" src="https://github.com/user-attachments/assets/961d21b3-e2d6-4319-b6ac-76b3ba80ac31" />

#### Step 4: Deploy Kali Linux
Kali Linux was imported and successfully verified that the deployment was completed without errors.

<img width="1292" height="807" alt="Imported Kali Linux" src="https://github.com/user-attachments/assets/58e79c4c-b251-4c13-9584-61327897cd0a" />

A shared folder was configured between the host machine and Kali Linux VM and accessibility was verified.

#### Step 5: Create a consistent IP for the Kali VM
The Kali Linux network configuration was checked and confired with a consistent IPv4 address

<img width="1282" height="797" alt="IP Address Configuration" src="https://github.com/user-attachments/assets/20bebdc1-4eb9-4973-b2a7-e1daf5c4ab6c" />

#### Step 6: Create a clean recovery point for future lab activities
After the initial setup and verification checks, a VirtualBox snapshot was created to establish a baseline recovery point for future projects.

### Technologies Used
* Kali Linux 2026.3
* Oracle VirtualBox
* NAT Networking
* Linux Networking Utilities

### Learning Outcomes
Throughout this project, I gained practical experience in:

* Virtual machine deployment and management
* Linux operating system configuration
* Virtual networking concepts
* NAT network implementation
* DNS validation
* Shared folder configuration
* System backup and recovery using snapshots

### Next Steps
* Continue with Week 2 internship project activities
* Expand the cybersecurity lab environment
* Perform network analysis and security assessments
* Develop hands-on experience with cybersecurity tools and methodologies
