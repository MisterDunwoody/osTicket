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

- Configure Departments
- Configure Agent (worker)
- Configure Roles
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/HYP9JKs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents and managers can be assigned to one or more departments through the Admin Panel's Agents tab. These departments, which can be either private or public, are used to route tickets in the help desk system. To configure departments, go to the Admin Panel's Agents tab.
<br />

<p>
<img src="https://i.imgur.com/OSUYPM7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are configured and granted access to the help desk in order to respond to and resolve tickets. When adding an agent, you can assign them to a primary department and assign them a primary role for the tickets/tasks routed to that department. Additionally, agents can be granted extended access to additional departments of the help desk and assigned different roles for those departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/nvnfqbJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are granted permissions, or roles, for each department they have access to. These roles consist of a set of permissions that can be enabled or disabled for agents with that role in a particular department. An unlimited number of roles can be created and assigned to agents with access to various departments. Roles are configured in the Agents tab of the Admin Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/DNggjKW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Service Level Agreements, or SLA Plans, are used to specify the amount of time that the help desk administrator expects tickets to be closed. These plans can be created by going to the Manage tab in the Admin Panel and clicking the "Add New SLA Plans" button." 


</p>
<br />
