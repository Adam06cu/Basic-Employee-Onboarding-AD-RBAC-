# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

North Star Mdeical Group had a very outdated Identity Lifecycle Workflow. Users had to be added and removed manualy. This became a problem when the company grew to 200 employees, making it almost impossible to tell who had access to what, since there was no Audit trails. This caused severe HIPAA riks since information could easely be leaked by someone having access to something they are not supposed to

## Solution Overview
[Provide 4 to 6 sentences describing what you built and how it solved the problem. Cover the new domain creation, the structural OU design, the security groups, the flat RBAC model, and how user provisioning was secured.]

I created an Active Directory using a virtaul machine. With-in it I created a basic employee onboarding pipeline. I made sure employees only had acess to the resources needed for their jobs and nothing else. I used a mock ticket to simulate a user being in the wrong OU and security group and documented the process of fixing it.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
