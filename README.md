# Windows-Server-AD-DS-
Active Directory Domain Services (AD DS) is Microsoft's directory service that manages users, computers, and resources in a network. It provides authentication, authorization, and centralized management of networked devices within a domain.

To install Active Directory Domain Services (AD DS)

1- **First Configure a static IP address**

Before configuring AD on your server, you should ensure that the server’s network adapter has been assigned a valid static IP address on your local network.

![ad-2](https://github.com/user-attachments/assets/084e6a0f-85d8-46d2-8bf7-c877a7e6cec1)

2- **In the Internet Protocol Version 4 (TCP/IPv4) Properties dialog,**

check Use the following IP address. You’ll need to fill out the following three fields: IP address, Subnet mask, Default gateway

![ad-3](https://github.com/user-attachments/assets/7c1e74c0-5bd0-49d3-bf62-cf4cd1d092e6)

3- **Name your server**

Make sure you assign a name to your server that reflects its new role. Something like Test-DC16 might be good

![ad-4](https://github.com/user-attachments/assets/af490b90-e0fb-4334-b680-76fa5029680d)

4- **Now: Install the Active Directory Domain Services role**

Log in to Windows Server 2019 with a local administrator account.
Server Manager should open by default. If it doesn’t, click the Start menu and find Server Manager in the list of installed apps and click it.

In Server Manager, click the Manage menu in the top-right corner and select Add Roles and Features from the menu.

![ad-1](https://github.com/user-attachments/assets/d513b56b-437c-4e8e-9980-f22671dc400e)

5- **In the Add Roles and Features Wizard**

On the Installation Type screen, make sure that Role-based or feature-based installation is selected and click Next.
Select your server
![ad-6](https://github.com/user-attachments/assets/7be63f0d-3ab8-421b-b234-c5307e0b250d)


**Select Next**

6- **In the Add Roles and Features Wizard**

Make sure that Include management tools (if applicable) is checked then click Add Features

![ad-7](https://github.com/user-attachments/assets/551c03ca-bfad-448e-bdee-a3b521ad6dc9)

2-  select "Active Directory Domain Services"

![ad-8](https://github.com/user-attachments/assets/36d5c432-c930-482c-ac18-367ac7f9da37)

**Select Next**
**Now click Install on the Confirmation screen**
When the installation is complete, click Close in the Add Roles and Features Wizard.**




























