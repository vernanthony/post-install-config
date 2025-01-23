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

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


<h2>Configuration Steps</h2>

![Screenshot 2025-01-22 140727](https://github.com/user-attachments/assets/c334569b-9f0e-455e-8652-f37f8ef152bc)

![Screenshot 2025-01-22 140826](https://github.com/user-attachments/assets/1d6adf15-b2a1-49ad-98df-0184b2f06a99)

<p>
</p>
<p>
The Images above shows where I configured roles to group permissions effectively.</p>
<br />

![Screenshot 2025-01-22 140912](https://github.com/user-attachments/assets/8d5778fd-6723-4976-aca0-f71cb62cdc87)


<p>
</p>
<p>
During the post-installation setup of osTicket, I configured departments to organize ticket visibility and streamline operations. Departments like Help Desk, SysAdmins, and Networking were set up to ensure tickets are directed to the right teams.

  
  ![Screenshot 2025-01-22 141039](https://github.com/user-attachments/assets/035168ad-a2c5-485d-8a42-86586309f66a)


<p>
</p>
<p>
In osTicket's Admin Panel, I configured Teams to assign specific groups of agents to handle tickets collaboratively. This setup ensures tasks are distributed efficiently and critical issues can be addressed by the appropriate team members.</p>
<br />

![Screenshot 2025-01-22 141234](https://github.com/user-attachments/assets/cdb3e9aa-b557-4f35-b8f2-54aa52d99634)


In osTicket's Admin Panel, I configured SLAs (Service Level Agreements) to define response and resolution times for tickets. This helps ensure timely support and aligns ticket handling with priority and business requirements.

![Screenshot 2025-01-22 141430](https://github.com/user-attachments/assets/6960c17a-2547-48e5-ad3b-2736256edb67)


I configured Help Topics in osTicket to streamline ticket creation and categorize support requests effectively. By setting up topics specific to common issues, I made it easier for users to select the right category and ensure tickets are routed to the appropriate teams.
