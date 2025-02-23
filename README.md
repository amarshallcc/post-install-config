<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuring Agent Roles & Permissions
- Setting Up Departments (Ticket Visibility & Work Distribution)
- Controlling Who Can Submit Tickets
- Setting up SLA (Service Level Agreements)
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>

Understanding the Admin Panel
Location: http://localhost/osTicket/scp/login.php
Purpose: The Admin Panel is where you configure settings, roles, permissions, and workflow for the helpdesk system.

---

1. Configuring Agent Roles & Permissions
<p>
  
![image](https://github.com/user-attachments/assets/82bbf76d-5cb4-4dc0-b17d-c1827f7995d4)
  
</p>
Location: Admin Panel → Agents → Roles
Purpose:
Roles define what agents can and cannot do in the system.
Example:
Supreme Admin – Has full access to manage everything.

![image](https://github.com/user-attachments/assets/6b876b37-dfcd-490c-9981-24c98e2b3e11)

![image](https://github.com/user-attachments/assets/766562f5-44e0-4fa8-a682-2e9c61064f54)

Support Agent – Can only view and respond to tickets.



---

2. Setting Up Departments (Ticket Visibility & Work Distribution)
<p>
  
![image](https://github.com/user-attachments/assets/1f1aefee-316f-4f13-a13c-3f083a10ba23)

</p>
Location: Admin Panel → Agents → Departments
Purpose:
Departments determine who can see and work on certain tickets.
Example:
SysAdmins: Handles server and network issues.
Help Desk: Manages general IT support requests.

![image](https://github.com/user-attachments/assets/cdbbbaf1-e1d7-41eb-aae8-1f93dcd68c13)


---

3. Creating Teams for Cross-Department Work
<p>
Location: Admin Panel → Agents → Teams
Purpose:
Teams allow agents from different departments to work on specific tasks together.
Example:
Online Banking Team – Includes agents from Networking & SysAdmins to handle online banking-related issues.

![image](https://github.com/user-attachments/assets/90a5b7ad-4749-49d3-9c4a-c563dfacae5a)

---

4. Controlling Who Can Submit Tickets
<p>
  
![image](https://github.com/user-attachments/assets/7c41a571-3fea-418f-9688-dc54bd475fb1)

</p>
Location: Admin Panel → Settings → User Settings
Purpose:
Define who can create tickets and whether users must be registered.
Options:
Allow Anyone to Submit Tickets – No login required.
Require Registration – Users must register before creating a ticket.

---

5. Adding & Managing Agents (Support Workers)
<p>
  
![image](https://github.com/user-attachments/assets/1b73822a-0b59-4f0c-b15f-baaa47f823cc)

![image](https://github.com/user-attachments/assets/c34c7e1d-de70-4498-ad30-0806d8871423)

</p>
Location: Admin Panel → Agents → Add New
Purpose:
Assign agents to specific departments and roles.
Example:
Jane (Assigned to SysAdmins)
John (Assigned to Support)

---

6. Setting Up Service Level Agreements (SLAs)
<p>
  
![image](https://github.com/user-attachments/assets/33a42fe7-8240-41ee-980f-4af152a4db07)

![image](https://github.com/user-attachments/assets/476b8e6e-c536-44e3-8cba-eef2e3d8cd08)

![image](https://github.com/user-attachments/assets/d41e5ab7-c864-40e7-9329-857ddc960021)


</p>
Location: Admin Panel → Manage → SLA
Purpose:
SLAs define how quickly tickets must be resolved based on severity.
Example:
Sev-A (Critical) – Response within 1 hour (24/7).
Sev-B (High) – Response within 4 hours (24/7).
Sev-C (Low) – Response within 8 hours (Business Hours).

---

7. Configuring Help Topics for Ticket Categorization
<p>
  

 
![image](https://github.com/user-attachments/assets/87de9b99-c488-4a5c-b458-4e5b9b8b59ee)

</p>
Location: Admin Panel → Manage → Help Topics
Purpose:
Help Topics classify tickets so they go to the right department.
Example:
Business Critical Outage (Urgent company-wide issues).
Password Reset (User login problems).
Equipment Request (New hardware/software requests).

![image](https://github.com/user-attachments/assets/a1561f40-8f4c-4fdc-b6cf-0c0aa4bf9cbd)

---

By setting up these features, osTicket ensures tickets are properly categorized, assigned, and resolved efficiently.

![Screenshot 2025-02-16 183604](https://github.com/user-attachments/assets/2471e2f2-47f4-4a83-972c-00c3b2d1f30d)



---
