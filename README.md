<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!--<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)-->

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
- Configure Agents(workers)
- Configure Users(customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
<p>
Glad to see you got through the grueling process of installing osTicket! Now we can configure some roles and other details for usability. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/75d5bd36-2c67-475e-b0a5-fffadc75b0fa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the view for the Admin Panel. Here, you can add/remove agents, departments, teams, and roles. 
</p>
<p>
<img src="https://github.com/user-attachments/assets/b248ebfa-0611-49a9-a623-f65b74d0961a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Let's show how to configure roles. First, click Roles (physically located under the Settings tab). We'll add a new role called "Supreme Admin" that has access to everything.
</p>
<p>
<img src="https://github.com/user-attachments/assets/d2d4287f-108a-457f-8cbe-b3f8689fd0cc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/ed49f7de-74b2-4e41-a86e-032183e2e3bf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you give your new role a name, go to the "Permissions" tab. There, you'll check every box. For future purposes, when you add a different role, you'll have to check and uncheck certain boxes depending on their accessibility and role in the company. Finish by clicking "Add Role" near the bottom.
</p>
<p>
You would essentially follow this same process when adding a new Team, a new Department, or even a new Agent. 
</p>
<p>
<img src="https://github.com/user-attachments/assets/0a2a986f-568f-48a0-9c06-b317ceb71f49" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
One thing you can do is allow any user to create tickets, whether they are registered or not. Go to Settings, and then Users. In this case, I have the box unchecked, thus allowing anyone to create a ticket. It's less work for me now, sure, but this is not good practice. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/bdca7f4f-2f68-441a-8ba0-390f13f5bbec" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure users, you must be in the Agent Panel, then click Users, then click Add User. Follow the on-screen instructions to add the user, including their email address. 
</p>
<br />

<p>
<img src="![OS Ticket 7](https://github.com/user-attachments/assets/c177900e-d1d1-4fe6-b55c-d50170dd0156)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring SLA is as simple as going to the Admin Panel, clicking Manage, then clicking SLA, then clicking Add New SLA Plan.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5ad4c809-3743-4e02-bc8a-9f12a83f196c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, for configuring Help Topics, simply click on Help Topics under the same Manage tab, and click Add New Help Topic.
</p>
<br />
