
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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>

We are going to use the two URL to log into the osTicket as Admin/Analyst and as End Users to see if it works.

- http://localhost/osTicket/scp/login.php
- http://localhost/osTicket
  
<img src="https://i.imgur.com/C72rtRN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 

In this lab we are going to configure some features in my osTicket.
First is ROLES (for grouping permission. Basically giving permision to a certain group of people.) In this Lab, I will  add a new role and name it "Supreme Admin."
To achieve this, i will go to Admin panel-Agents-Roles.  
</p>
<br />

<p>
<img src="https://i.imgur.com/UZrXoEH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://i.imgur.com/zKbNKnf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Next is to configure DEPARTMENT (Ticket Visibity which might be for Help Desk, SysAdmins, or Network admin) for example if a tickect get assigned to the network department it
only that department sees the ticket. To do that go to Admin Panel - Agents - departments to configure. Add a new department and name it "SysAdmins"
</p>
<br />

<p>
<img src="https://i.imgur.com/501vE8A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/GWEmRRq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Next is to configure TEAMS: Let's say you want to create awhole group of people for example, If you are working in a bank you will create online banking  that may consist of SysAdmins
who are who are responsible for the online banking system. To do that you will go to Admin Panel - Agents - Teams
</p>
<br />

<p>
<img src="https://i.imgur.com/01U31sF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Next is to allow users create ticket even if they are not allowed. i.e end users are allowed to create their own ticket without having account. so to do that, go to Admin Panel -
User Settings - Uncheck unregistered user so they can create ticket. (Registration required, Required registration and login to create ticket.)
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
