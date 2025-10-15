
# 💻 Note 1: AWS Foundations │ Servers/ EC2 / SSH / RDP

To complement my studies, I created a diagram that represents how users (it can be a human being or another software) connect with the VPC.

![Diagram](Server_AWS_Study_Notes.png)

## 😗 Key Concept: VPC 
VPC (Virtual Private Cloud) is a virtual network within a public cloud (for example, AWS 🙂). The VPC contains computer resources that work for a specific reason (for a company or a person).

VPC components:
1. Security groups (traffic control)
2. EC2 (the machine)
3. Ports (allows users access with RDP and SSH)
4. Public key (connects with private key)


[link of VPC documentation on AWS website](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)

*Quick correction: on the diagram, Remote Desktop is RDP, not RDK*

## SSH and RDP

SSH and RDP are understood to be a protocol that allow users to access the computer resourses. Alongside the public and private key, the SSH and RDP are ways to access VPC.



