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
We created two users just for demonstration, one with administrator privileges and a normal user. <br/>
<br/>
<p align="center">
  Installed Active Directory Tools:<br/>
<img width="753" height="516" alt="image" src="https://github.com/user-attachments/assets/9220c758-f50f-4f7d-b02a-ddd4a1c489a5" />


<br />
<br />
 
## Domain Joining

This is to Join the windows system of the client with the domain we created.<br/>

<br/>
<p align="center">
 Step 1: Go to network settings on the client's computer<br/>
<img width="1023" height="721" alt="image" src="https://github.com/user-attachments/assets/73dd6a47-bdbd-4c34-9169-ef8716973ac8" />



<br />
<br />

<p align="center">
  Step 2:<br/>
<img width="796" height="635" alt="image" src="https://github.com/user-attachments/assets/908a5da2-6e57-4e75-980b-8840ceee5942" />



<br />
<br />

<p align="center">
  Step 3:<br/>
<img width="1005" height="696" alt="image" src="https://github.com/user-attachments/assets/6b935afd-68ed-48fa-bc82-4047a7a469e0" />




<br />
<br />

<p align="center">
  Step 4: change it to manual ip address<br/>
<img width="482" height="211" alt="image" src="https://github.com/user-attachments/assets/c1ad5dad-852d-4279-8a3b-5eb2c26a56bc" />



<br />
<br />

<p align="center">
  Step 5: Set a static ip address that belongs to your network's range<br/>
<img width="1028" height="725" alt="image" src="https://github.com/user-attachments/assets/158f3faa-5617-4065-b0ba-ea96f6010a55" />




<br />
<br />

<p align="center">
  Step 6: <br/>
<img width="996" height="592" alt="image" src="https://github.com/user-attachments/assets/c4ae5a33-0b6a-434e-b731-df2ffd6ae4a6" />




<br />
<br />

<p align="center">
  Step 7: Click on "connect" <br/>
<img width="1017" height="552" alt="image" src="https://github.com/user-attachments/assets/3ae0a8fa-e7cb-44f3-a28e-3ba0639e2d92" />




<br />
<br />

<p align="center">
  Step 8: Click on "Join this device to a local Active Directory Domain" <br/>
<img width="643" height="632" alt="image" src="https://github.com/user-attachments/assets/ce2e57e6-6abd-4575-874c-f71cdd13b1db" />




<br />
<br />

<p align="center">
  Step 9: Insert your domain's name <br/>
<img width="1012" height="713" alt="image" src="https://github.com/user-attachments/assets/5520f3f7-16b0-4430-8ca5-dc2965b564bc" />




<br />
<br />

<p align="center">
  Step 10: Insert the admin's PC login credentials <br/>
<img width="447" height="360" alt="image" src="https://github.com/user-attachments/assets/a7cbb663-50de-48a3-86e7-425c18eeda80" />




<br />
<br />

<p align="center">
  Step 11: Choose administrator <br/>
<img width="635" height="392" alt="image" src="https://github.com/user-attachments/assets/9492a193-712a-4dc3-a143-9a073bc15a02" />



<br />
<br />

<p align="center">
  Step 12: Restart PC <br/>
<img width="636" height="202" alt="image" src="https://github.com/user-attachments/assets/4bfc1ff5-4fa1-482b-8088-37229fcac765" />



<br />
<br />

<p align="center">
  Step 13: Go to Tools > Active Directory Users and Groups <br/>
<img width="1287" height="717" alt="image" src="https://github.com/user-attachments/assets/7917c536-51de-444d-9ab3-346818ab9d60" />


<br />
<br />

<p align="center">
  Step 14: Go to computers to see if device was successfully enrolled <br/>
<img width="747" height="515" alt="image" src="https://github.com/user-attachments/assets/2ce5d08b-d582-4f80-ab58-19370a9cf1b8" />


<br />
<br />



## Conclusion
This project successfully implemented a functional Domain Controller using Active Directory on Windows Server, simulating a real-world enterprise environment.<br/>

It demonstrates practical experience in identity management, network configuration, policy enforcement, and centralized administration — foundational components of modern IT infrastructure and cybersecurity operations.

