
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
First is ROLES: (for grouping permission. Basically giving permision to a certain group of people.) In this Lab, I will  add a new role and name it "Supreme Admin."
To achieve this, i will go to Admin panel-Agents-Roles.  
</p>
<br />

<p>
<img src="https://i.imgur.com/UZrXoEH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://i.imgur.com/zKbNKnf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Next is to configure DEPARTMENT: (Ticket Visibity which might be for Help Desk, SysAdmins, or Network admin) for example if a tickect get assigned to the network department it
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
<img src="https://i.imgur.com/DahC3sK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next is to configure AGENTS/ WORKERS: For example if  John and Jane is hired to work in helpdesk , we will create Agent account for them and set their passwords each as "Password1". To actually do that we will go to
Admin Panel - Agents -Add New.    We are going to add Jane(Dept- SysAdmin.)  and John(Dept- Support.) 
<img src="https://i.imgur.com/LQhFVZt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/Uv3UESR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/9rkUiet.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next is to configure USERS/ CUSTOMERS: I'm just going to add one user "Karen" to make it simple. To do that am just going to go to Agent Panel - Users - Add New.
<p>
<img src="https://i.imgur.com/ixxrmb5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next is to configure SLA(Service Level Agreement): It simply means a level of understanding between help desk team and customers. For example, It's basically 
how much time it took you or it's going to take you to  respond or resolve a ticket problem. To do that we going to Admin Panel - Manage - SLA.

<h2>We are going to set it as follows:</h2> 
  
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)

<p>
<img src="https://i.imgur.com/I6ezxaY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Lastly, we are going to configure "Help Topics" for when users create a ticket. To do that, go to Admin Panel - Manage - Help Topics.

<h2>Add these new topics:</h2>

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other

<p>
<img src="https://i.imgur.com/VDQJoiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/4jpUl4R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/N9e2MBz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/aXWdBkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/P6aah06.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
