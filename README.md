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

- Configure Roles, Departments, and Teams
- Allow anyone to create tickets
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ThwHqpz.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we'll configure a Supreme Admin role. Log into osTicket, and click the Admin Panel in the top right. Once inside the Admin Panel, click "Agents" tab, and then roles. Click "Add New Role" and name it "Surpeme Admin". Then, click the Permissions tab and check everything under it, and click "Add Role" once finished.
</p>
<br />

<p>
<img src="https://i.imgur.com/gvf7wKa.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, under the same "Agents" tab, click "Deparments" and click "Add New Department". Leave everything as is, and name the department "SysAdmins", and click "Create Dept" once finished.
<br />

<p>
<img src="https://i.imgur.com/I0JBm0F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the same "Agents" tab, click "Teams" and click "Add New Team". Name the team "Online Banking", leaving everything else as is, and click "Create Team" once finished.
</p>
<br />

<p>
<img src="https://i.imgur.com/Y9NWb4z.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Switch from the "Agents" tab to the "Settings" tab, and click "Users". Under the Users Settings, make sure the "Require registration and login to create tickets" box is unchecked. This will allow anyone to create tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/BYJq7ud.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Switch from the "Settings" tab back to the "Agents" tab, and click "Add New Agent". Name the first agent "Jane Doe" and fill out the information, with "Password1" as the password. One finished, click create and repeat the process for a second agent named "John Doe".
</p>
<br />

<p>
<img src="https://i.imgur.com/Ssyjpm4.png" alt="Disk Sanitization Steps"/>
</p>
<p>
In the top right, click "Agent Panel" and go to the "Users" tab. Click "Add User" and create two users named "Karen" and "Ken" with a simple email. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bCjUy0n.png" alt="Disk Sanitization Steps"/>
</p>
<p>
In the top right, click "Admin Panel" and go to the "Manage" tab. Under this tab, click "SLA" and then "Add New SLA Plan". Name the first SLA "Sev-A", and set "Grace Period" to 1, and "Schedule" to 24/7. Leave the rest as is and click "Add Plan". Name the second SLA "Sev-B", and set "Grace Period" to 4, and "Schedule" to 24/7. Leave the rest as is and click "Add Plan". Name the third SLA "Sev-C", and set "Grace Period" to 8, and "Schedule" to "Monday - Friday 8am - 5pm with U.S. Holidays". Leave the rest as is and click "Add Plan".
</p>
<br />

<p>
<img src="https://i.imgur.com/aZeJjAe.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the same "Manage" tab, go to "Help Topics" and click "Add New Help Topic". Name the first topic "Business Critical Outage" and set "Parent Topic" to "Report a Problem". Click "Add Topic" once done. Create a second topic and name it "Personal Computer Issues". Set "Parent Topic" to "Report a Problem" and click "Add Topic" once done. Create a third topic and name it "Equipment Request". Set "Parent Topic" to "General Inquiry" and click "Add Topic" once done. Create a fourth topic and name it "Password Reset". Set "Parent Topic" to "Report a Problem" and click "Add Topic" once done. Create one last topic and name it "Other". Set "Parent Topic" to "General Inquiry" and click "Add Topic once done".
</p>
<br />

<p>
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<p>
You have now finished the post-instillation configuration of osTicket.
</p>
<br />
<p>
<img src="" alt="Disk Sanitization Steps"/>
</p>
<br />
