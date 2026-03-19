# Setting a Domain Controller

## Description
A hands-on Active Directory Domain Controller lab project focused on user management, Group Policy configuration, authentication, and enterprise network administration.
<br />


## Utilities Used

- <b>Windows Server 2022</b>
- <b>pfSense</b>


## Environments Used

- <b>Virtual Box</b>

<h2>Program walk-through:</h2>
<h3>Why this was Implimented.</h3><br/>
The Domain Controller project was implemented to simulate a real-world enterprise environment where centralized identity and access management is required. By deploying Active Directory on Windows Server, the goal was to understand how organizations manage users, computers, authentication, and security policies within a domain infrastructure.<br/>

<strong>This lab environment allows:</strong><br/>

- Centralized user and group management<br/>
- Policy enforcement using Group Policy Objects (GPOs)<br/>
- Authentication and authorization testing (Kerberos & NTLM)<br/>
- DNS and domain services configuration<br/>
- Simulating enterprise-level administrative tasks<br/>
<br/>

<!-- ACTIVE DIRECTORY INSTALLATION SERVICES -->

## Active Directory Services Installation

The server was configured with Active Directory on Windows Server to simulate an enterprise identity and access management environment.<br/>

<strong>The following core components were installed and configured:</strong><br/>

- Active Directory Domain Services (AD DS) to manage domain-based authentication and authorization.<br/>
- Active Directory Certificate Services. <br/>
- DNS Server to support domain name resolution within the network.<br/>
- Group Policy Management tools to enforce security and configuration policies.<br/>
- Active Directory Users and Computers (ADUC) for centralized user, group, and OU management.<br/>

These services were implemented to create a fully functional Domain Controller capable of handling centralized authentication, policy enforcement, access control, and enterprise-level administration within a controlled lab environment.

<p align="center">
  Installed Active Directory Tools:<br/>
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/aecd2c46-ae9c-421f-af94-104edd6ed4a3" />

<br />
<br />
## Network Configuration

After completing the installation of Active Directory on Windows Server, the server was configured with a static IP address, subnet mask, and default gateway.<br/>

Assigning a static IP ensures consistent network identification and reliable domain services, which is critical for DNS resolution, authentication processes, and overall domain stability within an enterprise environment.<br/>
<br/>

## Users and Groups



## Conclusion
This project successfully implemented a functional Domain Controller using Active Directory on Windows Server, simulating a real-world enterprise environment.<br/>

It demonstrates practical experience in identity management, network configuration, policy enforcement, and centralized administration — foundational components of modern IT infrastructure and cybersecurity operations.

