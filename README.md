<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

1. Understanding the Admin Panel
Location: http://localhost/osTicket/scp/login.php
Purpose: The Admin Panel is where you configure settings, roles, permissions, and workflow for the helpdesk system.


3. Configuring Agent Roles & Permissions
Location: Admin Panel → Agents → Roles
Purpose:
Roles define what agents can and cannot do in the system.
Example:
Supreme Admin – Has full access to manage everything.
Support Agent – Can only view and respond to tickets.


4. Setting Up Departments (Ticket Visibility & Work Distribution)
Location: Admin Panel → Agents → Departments
Purpose:
Departments determine who can see and work on certain tickets.
Example:
SysAdmins: Handles server and network issues.
Help Desk: Manages general IT support requests.


6. Creating Teams for Cross-Department Work
Location: Admin Panel → Agents → Teams
Purpose:
Teams allow agents from different departments to work on specific tasks together.
Example:
Online Banking Team – Includes agents from Networking & SysAdmins to handle online banking-related issues.

8. Controlling Who Can Submit Tickets
Location: Admin Panel → Settings → User Settings
Purpose:
Define who can create tickets and whether users must be registered.
Options:
Allow Anyone to Submit Tickets – No login required.
Require Registration – Users must register before creating a ticket.

10. Adding & Managing Agents (Support Workers)
Location: Admin Panel → Agents → Add New
Purpose:
Assign agents to specific departments and roles.
Example:
Jane (Assigned to SysAdmins)
John (Assigned to Support)

12. Setting Up Service Level Agreements (SLAs)
Location: Admin Panel → Manage → SLA
Purpose:
SLAs define how quickly tickets must be resolved based on severity.
Example:
Sev-A (Critical) – Response within 1 hour (24/7).
Sev-B (High) – Response within 4 hours (24/7).
Sev-C (Low) – Response within 8 hours (Business Hours).

14. Configuring Help Topics for Ticket Categorization
Location: Admin Panel → Manage → Help Topics
Purpose:
Help Topics classify tickets so they go to the right department.
Example:
Business Critical Outage (Urgent company-wide issues).
Password Reset (User login problems).
Equipment Request (New hardware/software requests).


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

By setting up these features, osTicket ensures tickets are properly categorized, assigned, and resolved efficiently.
