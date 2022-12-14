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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agent (worker)
- Configure SLA


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/I6j5rT5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles are configured in the Agents tab under the Admin Panel and clicking on Add New Role. Here we created the role "Supreme Admins".
  
An unlimited number of roles can be created and assigned to Agents with access to various departments. Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to.
</p>
<br />

<p>
<img src="https://i.imgur.com/K2zu6H9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A Department called "System Adminstration" was created here. Departments are configured through the Agents tab under the Admin Panel and clicking on Add New department.
  
Departments are used to route tickets in help desk. The Deparments may be private or public and they can be assigned to 1 or more agents and managers.
</p>
<br />

<p>
<img src="https://i.imgur.com/bvMmZPx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A team was created called 'level II Sypport" by locating the Agents tab, and click on Teams. Then click Add New Team on the right, and fill out the appropriate information. Then you will be able to add Agents to the team by clicking on their name from your list of Agents and checking the corresponding box next to the Team name you wish to add them at the bottom of the page.
  
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
A Team can have an appointed leader who can receive Alerts & Notices separate from other team members. In order to set a Team Leader you can choose an Agent from the Team Lead dropdown when creating a Team or Editing an existing Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/VakoRPw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents were created under the Agent panel, Add New Agent and filling out the neccessary information. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
  
Agents are given access to the help desk with the intent to respond and resolve the tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KieOg7A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans can be created by going to the Manage tab under the Admin Panel and clicking Add New SLA PlanS. SLA Plans or Service Level Agreements were created to provide a length of time in which the help desk Administrator expects tickets to be closed. . SLA plans are usually different for every orangization.
</p>
<br />
