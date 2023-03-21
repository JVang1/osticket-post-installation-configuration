<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Anyone to Create Tickets
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure Service Level Agreements (SLA)
- Configure Help Topics

<h2>Configuration Steps</h2>


<p>
1. Configure Roles
</p>
<p>
<img src="https://imgur.com/ZLRqU3h.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Agents", then "Roles", then "Add New Role". 
</p>
<p>
<img src="https://imgur.com/yiCA586.png" height="60%" width="60%">
</p>
<p>
Name the role, "Supreme Admin", then click on "Add Role". 
</p>
<p>
<img src="https://imgur.com/T6I5tni.png" height="60%" width="60%">
</p>
<p>
Click on "Permissions", under "Tickets", "Tasks", and "Knowledgebase" check mark all boxes, then "Save Changes".   
</p>
<br />


<p>
2. Configure Departments
</p>
<p>
<img src="https://imgur.com/q8WBFLf.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Agents", then "Departments", then "Add New Department". 
</p>
<p>
<img src="https://imgur.com/wQW5v1E.png" height="60%" width="60%">
</p>
<p>
Name the deparment, "System Administrators", then scroll down and click on "Create Dept".  
</p>
<br />


<p>
3. Configure Teams
</p>
<img src="https://imgur.com/sGPZq0W.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Agents", then "Teams", then "Add New Team". 
</p>
<p>
<img src="https://imgur.com/vL7TJHv.png" height="60%" width="60%">
</p>
<p>
Name the team, "Level I Support", then click on "Create Team". Repeat above steps and create another team called "Level II Support".    
</p>
<br />


<p>
4. Allow Anyone to Create Tickets
</p>
<img src="https://imgur.com/IFC33lt.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Settings", then "Users". Under Authentication Settings, ensure the Registration Required box is unchecked.  
</p>
<br />


<p>
5. Configure Agents (Workers)
</p>
<img src="https://imgur.com/Edldjgp.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Agents", then "Agents", then "Add New Agent".
</p>
<p>
<img src="https://imgur.com/LSKCsJb.png" height="60%" width="60%">
</p>
<p>
Name the agent, "Jane Doe", then give the agent an email address and username, then click on "Create". Repeat above steps and create another agent called "John Doe".   
</p>
<br />


<p>
6. Configure Users (Customers)
</p>
<img src="https://imgur.com/brEl9Ma.png" height="60%" width="60%">
</p>
<p>
From the Agent Panel, click on "Users", then "User Directory", then "Add User".
</p>
<p>
<img src="https://imgur.com/Nv0w7V8.png" height="60%" width="60%">
</p>
<p>
Name the user, "Karen Karen", then give the user an email address, then click on "Add User". Repeat above steps and create another user called "Ken Ken".   
</p>
<br />


<p>
7. Configure SLA
</p>
<img src="https://imgur.com/fCgnL46.png" height="60%" width="60%">
</p>
<p>
From the Admin Panel, click on "Manage", then "SLA", then "Add New SLA Plan". 
</p>
<img src="https://imgur.com/lkAoTW0.png" height="60%" width="60%">
</p>
<p>
Name the SLA Plan, "SEV-A", set it as "Active", give it a Grace Period of "1" hour, set the schedule "24/7", then click on "Add Plan".  
</p>
<br />


<p>
8. Configure Help Topics
</p>
<img src=".png" height="60%" width="60%">
</p>
<p>

</p>
<img src=".png" height="60%" width="60%">
</p>
<p>

</p>
<br />


