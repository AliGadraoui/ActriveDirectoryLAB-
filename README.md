# Active Directory Setup and Configuration

## Project Overview
This project involves setting up and configuring Active Directory (AD) on a Windows Server using Oracle VM VirtualBox. The goal is to create and manage users, computers, and other resources within a networked environment.

## Table of Contents
- [Introduction](#introduction)
- [Theoretical Background](#theoretical-background)
- [Experimental Setup](#experimental-setup)
- [Configuration and Management](#configuration-and-management)
- [Screenshots and Visuals](#screenshots-and-visuals)
- [Troubleshooting and Tips](#troubleshooting-and-tips)
- [Conclusion](#conclusion)
- [References](#references)
- [Contact](#contact)

## Introduction
Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks. It is a critical component for managing users and resources in a secure and organized manner.

## Theoretical Background
### What is Active Directory?
Active Directory (AD) is a directory service for Windows domain networks. It manages permissions and access to networked resources.

### Why Use Active Directory?
AD simplifies user and resource management, enhances security through policies, and provides centralized control.

### Active Directory Structure
- **Forests**: Top-level container for AD objects.
- **Domains**: Subdivisions within a forest.
- **Organizational Units (OUs)**: Containers for grouping users and resources.
- **Sites**: Physical network structure representations.

## Experimental Setup
### Prerequisites
- Windows Server 2019 (or later)
- Oracle VM VirtualBox
- A stable network connection

### Environment Setup
1. **Install Windows Server on VirtualBox**:
   - Create a new virtual machine and install Windows Server.

2. **Configure Network Settings**:
   - Ensure the virtual machine has the correct network configuration.

   ![Network Connections]https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Ethernet.png?raw=true

### Installation Process
1. **Install Active Directory Domain Services (AD DS)**:
   - Open Server Manager and add the AD DS role.

2. **Promote the Server to a Domain Controller**:
   - Configure a new forest and domain.

## Configuration and Management
### Creating and Managing Users
- **Adding Users**:
  - Use the AD Users and Computers tool to add new users.

  ![Creating Users](./assets/Users2.png)

### Setting Up Policies
- **Group Policies**:
  - Define and apply policies for users and computers.

### Managing Resources
- **Computers**:
  - Add and manage computer objects in AD.

  ![Computer Management](./assets/Client.png)

## Screenshots and Visuals
- **Active Directory Users and Computers**:
  ![AD Users and Computers](./assets/Admin account.png)

- **DHCP Configuration**:
  ![DHCP](./assets/DHCP.png)

- **Routing and Remote Access**:
  ![Routing and Remote Access](./assets/Routing and remote access.png)

- **IP Configuration on Client**:
  ![IP Configuration](./assets/Ipconfig client.png)

- **Pinging the Domain**:
  ![Pinging the Domain](./assets/Pinging the client.png)

## Troubleshooting and Tips
- **Common Issues**:
  - Tips for solving common setup and configuration problems.

## Conclusion
Setting up Active Directory helps in centralizing network management and enhancing security.

## References
- [YouTube Tutorial Series](https://www.youtube.com/watch?v=MHsI8hJmggI&list=PLqBeiU46hx1H--SNfTrohTOWeqkK-M2Y0)

## Contact
For any questions or collaboration, feel free to reach out:
- **Email**: [your.email@example.com](mailto:your.email@example.com)
- **LinkedIn**: [linkedin.com/in/ali-gadraoui](https://www.linkedin.com/in/ali-gadraoui)
