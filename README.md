

🖥️ Active Directory Homelab

This is a home lab I created to learn and demonstrate skills in Windows Server administration, Active Directory, and networking.

🔧 Lab Tools

    VirtualBox

    Windows Server 2022 (Domain Controller)

    Windows 10 Enterprise (Domain-Joined Client)

🏗️ What I Set Up

    Configured AD DS and created a domain: lucaslab.local

    Created Organizational Units (IT, HR, Sales)

    Added users and security groups

    Applied Group Policy Objects (GPOs) to control user access (e.g., hide Control Panel)

    Scoped GPOs by security group membership to target policies precisely and avoid unwanted application

    Set up DHCP to automatically assign IP and DNS

    Verified domain join and policy application on the client

📸 Screenshots

### Users and Groups  
[![Users and Groups](screenshots/Users%20and%20Groups.png)](screenshots/Users%20and%20Groups.png)

### GPO with Security Filtered Group  
[![GPO with Security Filtered Group](screenshots/GPO%20with%20Security%20Filtered%20Group.png)](screenshots/GPO%20with%20Security%20Filtered%20Group.png)

### Restricted Access due to GPO  
[![Restricted Access due to GPO](screenshots/Restricted%20Access%20due%20to%20GPO.png)](screenshots/Restricted%20Access%20due%20to%20GPO.png)

### Verifying Domain Connection via DHCP  
[![Verifying Domain Connection via DHCP](screenshots/Verifying%20Domain%20Connection%20via%20DHCP.png)](screenshots/Verifying%20Domain%20Connection%20via%20DHCP.png)




💡 What I Learned

    Core concepts of Active Directory and DNS

    Group Policy creation, security filtering by groups, and troubleshooting non-application issues

    DHCP configuration and scope management

    IP and DNS troubleshooting with ipconfig and ping
