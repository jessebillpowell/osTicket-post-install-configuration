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

- Configure Roles (For Grouping Permissions)
- Configure Departments 
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA (Service Level Agreement)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Lnobqn4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/A6y0nPM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Departments is a specific subsection of the agents description, when granting access by an adminsitrator. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/VXNMERH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. 
</p>
<br />
