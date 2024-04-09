# Configuring-On-premises-Active-Directory-With-Azure-VMs<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
My instructions outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup Resources in Azure
- Ensure Connectivity between the Client & Domain Controller 
- Install Active Directory 
- Create an admin and normal User Account in (AD)
- Join Client 1 to your domain (mydomain.com)
- Setup Remote Desktop for non-administrative users on client-1
- Create as many additional users as you would like and attempt to log into client -1 with one of the user's profile 

<h2>Deployment and Configuration Steps</h2>

- SETUP RESOURCES IN AZURE 
![image](https://github.com/Llave254/configure-ad/assets/166266714/a2658c73-bbfe-497d-8b7e-b019065550c5)

- ENSURE CONNECTIVITY BETWEEN THE CLIENT & DOMAIN CONTROLLER
![Screenshot 2024-04-09 065941](https://github.com/Llave254/configure-ad/assets/166266714/e0f881ec-a403-4511-af85-1c19bcd3f148)

- INSTALL ACTIVE DIRECTORY  
![image](https://github.com/Llave254/configure-ad/assets/166266714/4b531c8b-7533-4d41-b67d-218fe602998b)

- CREATE AN ADMIN & NORMAL USER ACCOUNT 
![image](https://github.com/Llave254/configure-ad/assets/166266714/d61d7a38-b849-470d-bb2d-071f25a13e5c)

- JOIN CLIENT-1 TO YOUR DOMAIN (mydomain.com)
![image](https://github.com/Llave254/configure-ad/assets/166266714/265a64bc-ea68-46de-82a3-1723e852fa44)

- SETUP REMOTE DESKTOP FOR NON-ADMINSTRATIVE USERS ON CLIENT-1
  ![image](https://github.com/Llave254/configure-ad/assets/166266714/d86ac674-5b21-4199-959d-864e4df38f55)

  - CREATE AS MANY ADDITIONAL USERS AS YOU WOULD LIKE AND ATTEMPT TO LOG INTO CLIENT-1 WITH ONE OF THE USER'S PROFILE
   ![image](https://github.com/Llave254/configure-ad/assets/166266714/4ea39c4f-c89d-480e-9442-d5a6275261a2)

  ![image](https://github.com/Llave254/configure-ad/assets/166266714/fff18953-7153-484d-b57d-873ca9570a36)

 




