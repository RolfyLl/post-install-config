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

- Configure Roles
- Configure Departments
- Configure Agent workers
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/R7MEf4P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here i configred the Roles with Admin and named it Zeus/Admin. Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments. Any Agent/user that has this Role will have the ability to:

- Create tickets
- Delete tickets
- Edit
- Assign 
- Transfer and much more
  
</p>
<br />

<p>
<img src="https://i.imgur.com/cRyVkHM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here i configred the Department with Admin and named it Mount Olympus Administrators along with the Default Support Department and the Maintenance department. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/Sqjz32V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this section i created agents Named Hector Troy and Archilles Greek i assigned them both with Mount Olympus Admin department. Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile. 

</p>
<br />

<p>
<img src="https://i.imgur.com/VxGquSh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Here i created fake Users to be able to create tickets for later role playing issues. Users are the ticket owners of the tickets in the help desk. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk. Users can be added or deleted from the User Directory of the help desk at any time. Please note, if the user is deleted the tickets of the user must also be deleted.

</p>
<br />

<p>
<img src="https://i.imgur.com/CH7pvhC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this part of the Lab i created Three different types of Service Level Agreements, all ranging from different catogories. 


- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)
  
SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.

</p>
<br />

<p>
<img src="https://i.imgur.com/ReTgGJE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


</p>
<br />

