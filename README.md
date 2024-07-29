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

## Introduction
Active Directory (AD) is a vital directory service developed by Microsoft for Windows domain networks. It serves as a centralized hub for managing permissions, access, and resources within a network, thereby streamlining administrative tasks and enhancing security. AD enables administrators to manage and store information about network resources and application data, making it easier to maintain, secure, and organize a network infrastructure. This project showcases the setup and configuration of Active Directory using Windows Server and Oracle VM VirtualBox, illustrating the creation and management of users, computers, and other network resources.

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

   ![Network Connections](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Ethernet.png?raw=true)

### Installation Process
1. **Install Active Directory Domain Services (AD DS)**:
   - Open Server Manager and add the AD DS role.

2. **Promote the Server to a Domain Controller**:
   - Configure a new forest and domain.

## Configuration and Management
### Creating and Managing Users
- **Adding Users**:
  - Use the AD Users and Computers tool to add new users.

  ![Creating Users](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Users2.png?raw=true)

### Setting Up Policies
- **Group Policies**:
  - Define and apply policies for users and computers.

### Managing Resources
- **Computers**:
  - Add and manage computer objects in AD.

  ![Computer Management](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Client.png?raw=true)

## Screenshots and Visuals
- **Active Directory Users and Computers**:
  ![AD Users and Computers](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Admin%20account.png?raw=true)

- **DHCP Configuration**:
  ![DHCP](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/DHCP.png?raw=true)

- **Routing and Remote Access**:
  ![Routing and Remote Access](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Routing%20and%20remote%20access.png?raw=true)

- **IP Configuration on Client**:
  ![IP Configuration](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Ipconfig%20client.png?raw=true)

- **Pinging the Domain**:
  ![Pinging the Domain](https://github.com/AliGadraoui/ActriveDirectoryLAB-/blob/main/Pinging%20the%20client.png?raw=true)

<h2>Troubleshooting and Tips</h2>

<h3>Common Issues:</h3>
<ul>
  <li><strong>Installation Failures:</strong>
    <ul>
      <li>Ensure all system requirements are met and that you have a stable internet connection during installation.</li>
      <li>Verify that the Windows Server installation media is not corrupted.</li>
    </ul>
  </li>
  <li><strong>DNS Configuration Errors:</strong>
    <ul>
      <li>Double-check the DNS settings and ensure that the server’s IP address is correctly configured.</li>
      <li>Use the <code>nslookup</code> command to verify DNS resolution.</li>
    </ul>
  </li>
  <li><strong>User and Group Management Problems:</strong>
    <ul>
      <li>Confirm that you have the necessary permissions to create and manage users and groups.</li>
      <li>Ensure that the Active Directory Users and Computers (ADUC) tool is properly installed and configured.</li>
    </ul>
  </li>
  <li><strong>Network Connectivity Issues:</strong>
    <ul>
      <li>Verify that all network settings are correctly configured and that the virtual machines are connected to the correct network.</li>
      <li>Use the <code>ping</code> command to check connectivity between the client and the server.</li>
    </ul>
  </li>
</ul>

<h3>Tips:</h3>
<ul>
  <li><strong>Regular Backups:</strong>
    <ul>
      <li>Regularly back up the AD database to prevent data loss and ensure quick recovery in case of failures.</li>
    </ul>
  </li>
  <li><strong>Use Group Policies Wisely:</strong>
    <ul>
      <li>Implement Group Policies to enforce security settings and streamline management tasks across the network.</li>
    </ul>
  </li>
  <li><strong>Documentation:</strong>
    <ul>
      <li>Keep detailed documentation of your AD setup and configurations. This helps in troubleshooting and future upgrades.</li>
    </ul>
  </li>
  <li><strong>Monitoring and Maintenance:</strong>
    <ul>
      <li>Regularly monitor the AD environment for any unusual activities and perform routine maintenance to keep the system running smoothly.</li>
    </ul>
  </li>
</ul>


## Conclusion
Setting up Active Directory is crucial for organizations that require centralized management of their network resources. Through this project, we have explored the installation, configuration, and management of AD, demonstrating how it simplifies user and resource management, enhances security through policies, and provides centralized control over the network. By following this guide, administrators can efficiently manage their network infrastructure, ensuring it is secure, organized, and scalable. The hands-on experience gained from this project lays a strong foundation for further exploration and mastery of Active Directory and its advanced features.
