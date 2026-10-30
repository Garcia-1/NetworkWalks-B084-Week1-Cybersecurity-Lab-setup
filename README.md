# NetworkWalks-B084-Week1-Cybersecurity-Lab-setup


## Overview
This repository documents the successful completion of Week 1: Cybersecurity Lab Setup as part of the Networkwalks Cybersecurity Internship Program (Batch B084).
The objective of this project was to build a secure and functional cybersecurity lab environment using Kali Linux and Oracle VirtualBox. This environment will serve as the foundation for future cybersecurity exercises and hands-on security training throughout the internship program.

## Project Information
**Program:** Networkwalks Cybersecurity Internship Program
**Batch:** B084
**Project:** Week 1 - Cybersecurity Lab Setup
**Operating System:** Kali Linux 2026.3
**Virtualization Platform:** Oracle VirtualBox

### Technologies Used
* Kali Linux 2026.3
* Oracle VirtualBox
* NAT Networking
* Linux Networking Utilities

## Objectives 
* Install and configure Oracle VirtualBox
* Create and configure a private NAT Network
* Deploy a Kali Linux virtual machine
* Configure shared file access between host and guest systems
* Establish network connectivity and DNS functionality
* Create a consistent IP for the Kali VM
* Create a clean recovery point for future lab activities
* Document the setup process

## Purpose of the Lab
The purpose of this cybersecurity lab is to establish a secure, isolated, and fully functional virtual environment for hands-on cybersecurity training and practical learning. By deploying a Kali Linux virtual machine within Oracle VirtualBox on the Windows 11 host system, it provides a controlled environment for performing security-related tasks without impacting the host operating system.

This lab will serve as the foundational environment for experimenting with Linux administration, network configuration, penetration testing techniques and conducting vulnerability assessments and hands-on cybersecurity activities throughout the Networkwalks Cybersecurity Internship Program.


## Lab Architecture

<img width="830" height="451" alt="Lab-Architecture-Diagram" src="https://github.com/user-attachments/assets/221c6819-b84f-4706-acc5-c86b907cfb89" />


## Lab Setup Steps
#### Step 1: Download Required Software

VirtualBox and Kali Linux Setup Files were downloaded from their official websites.

<img width="297" height="75" alt="VirtualBox and Kali Linux Setup Files" src="https://github.com/user-attachments/assets/2d5cf9cb-b781-41eb-96a5-e245403c8ff9" />

#### Step 2: Install VirtualBox
Oracle VirtualBox was installed as the hypervisor.

<img width="1897" height="1008" alt="VirtualBox Installation" src="https://github.com/user-attachments/assets/b95a8a40-2952-4f26-b61c-6267d50af1ea" />

#### Step 3: Create the NAT Network
An isolated NAT Network was created in VirtualBox to allow multiple machines to communicate with each other in the lab environment. The configuration details can be viewed in the image below.

<img width="1897" height="1008" alt="Screenshot 2026-10-30 061156" src="https://github.com/user-attachments/assets/961d21b3-e2d6-4319-b6ac-76b3ba80ac31" />

#### Step 4: Deploy Kali Linux
Successfully imported Kali Linux and verified that the deployment was completed without errors.

<img width="1292" height="807" alt="Imported Kali Linux" src="https://github.com/user-attachments/assets/58e79c4c-b251-4c13-9584-61327897cd0a" />

A shared folder was configured between the host machine and guest (Kali Linux VM) and accessibility was verified.

The Adapter configurations can be seen in the image below.

<img width="1281" height="797" alt="Adapter Configuration" src="https://github.com/user-attachments/assets/6a55199a-3c44-461f-acdf-939957b7fad2" />

#### Step 5: Create a consistent IP for the Kali VM
The Kali Linux network configuration was checked and confirmed with a consistent IPv4 address as shown in the image below.

<img width="1282" height="797" alt="IP Address Configuration" src="https://github.com/user-attachments/assets/20bebdc1-4eb9-4973-b2a7-e1daf5c4ab6c" />

#### Step 6: Create a Clean VM Snapshot
After the initial setup and verification checks, a VirtualBox snapshot was created to establish a baseline recovery point in the event of configuration errors or unintended changes druring future lab activities.

<img width="491" height="446" alt="Snapshot Details" src="https://github.com/user-attachments/assets/771dc294-463a-423d-b5e1-57ac22f66b68" />

### Lab Verification

| Validation Item | Validation Method/Command Used| Status | 
| -------- | -------- |  -------- |
| VirtualBox Installed  | Launched Oracle VirtualBox and verified successful startup of the application. | :ballot_box_with_check:  |
| Kali Linux Imported  | Imported Kali Linux into VirtualBox and confirmed the VM appeared in the VirtualBox Manager. | :ballot_box_with_check:  |
| VM Deployment  | Powered on the VM and successfully logged in to the Kali Linux desktop environment. | :ballot_box_with_check:  |
| NAT Network Configured  | Reviewed VirtualBox Network Settings and confirmed attachment to the custom NAT Network (10.0.0.0/24). | :ballot_box_with_check:  |
| IP Configuration  | ``` ip addr show ``` | :ballot_box_with_check:  |
| Default Gateway  | ``` ip route ``` | :ballot_box_with_check:  |
| Network Interface Status | ``` ip link show ``` | :ballot_box_with_check:  |
| Internet Connectivity  | ``` ping -c 3 10.0.0.1 ``` | :ballot_box_with_check:  |
| DNS Resolution Working  | ``` ping -c 3 google.com ``` | :ballot_box_with_check:  |
| Website Connectivity  | Accessed websites using Firefox and confirmed successful page loading. | :ballot_box_with_check:  |
| Shared Founder Mounted  | ```ls /media/ ``` and verified access to the shared folder from Kali Linux. | :ballot_box_with_check:  |
| File Transfer Functionality  | Created and accessed test files between the Windows host and Kali Linux guest. | :ballot_box_with_check:  |
| Clean Snapshot Created | Confirmed the clean snapshot was successfully created within VirtualBox Snapshot Manager. | :ballot_box_with_check:  |

<img width="1266" height="682" alt="Screenshot 2026-10-30 133828" src="https://github.com/user-attachments/assets/2f7eda5c-1c08-4fcd-9757-eda212d0cdb1" />
<img width="1237" height="240" alt="Validation-Check" src="https://github.com/user-attachments/assets/161196b4-6e3a-44a2-a02f-ccea0f0c5294" />



### Learning Outcomes
Throughout this project, I gained practical experience in:

* Virtual machine deployment and management
* Linux operating system configuration
* Virtual networking concepts
* NAT network implementation
* DNS validation
* Shared folder configuration
* System backup and recovery using snapshots
* Documenting the process

### Next Steps
* Continue with Week 2 internship project activities
* Expand the cybersecurity lab environment
* Perform network analysis and security assessments
* Develop hands-on experience with cybersecurity tools and methodologies

### Ethical Use & Disclaimer
This cybersecurity lab was created solely for educational, training, and research purposes. The lab is intended to support legitimate learning objectives, including network configuration, security testing, vulnerability assessment methodologies, and cybersecurity best practices.

**Disclaimer:** This project is intended exclusively for educational and professional development purposes. All demonstrations, configurations, and exercises are performed within a controlled virtual environment and should only be replicated on systems and networks for which proper authorization has been obtained.

### Author
**Garcia Forrest**
Cybersecurity Student (CC) B084

LinkedIn: www.linkedin.com/in/garcia-forrest
