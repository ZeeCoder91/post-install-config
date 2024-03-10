<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!---<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) --->

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
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>First, we'll create a role named 'Supreme Admin.' In osTicket, roles define the permissions assigned to Agents, determining their access level within each Department they are part of. This foundational step ensures structured access control from the outset.</p>
<img src="https://i.imgur.com/lhuRBrG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Ensure you are in the Admin Panel, where you can access essential configuration and management settings.</p>
<p>
<img src="https://i.imgur.com/89Ws8i4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Navigate to 'Agents' > 'Roles' > 'Add New Role' to proceed.</p>
<p>
<img src="https://i.imgur.com/NnpxLCH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Type 'Supreme Admin' into the name field, then click on 'Permissions.</p>
<p>
<img src="https://i.imgur.com/C7J6g8j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Select all permission boxes for the 'Supreme Admin' role to grant full access.</p>
<p>
<img src="https://i.imgur.com/2IfIWgO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Under 'Tickets' > 'Tasks', check all boxes to enable complete access.</p>
<p>
<img src="https://i.imgur.com/058QTsk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
In the 'Tickets' > 'Tasks' > 'Knowledgebase' section, ensure all boxes are checked for full privileges.</p>
<p>
<img src="https://i.imgur.com/jNqtmL7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Confirm that the new role has been successfully added to the panel.</p>
<p>
<img src="https://i.imgur.com/0elZtnW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
To add a new department, navigate to 'Agents' > 'Departments' > 'Add New Department'.
</p>
<p>
<img src="https://i.imgur.com/cjiPJOO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Tickets are directed through various departments within the help desk, each of which can be customized with its own set of settings
</p>
<p>
<img src="https://i.imgur.com/jj8Dfub.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
A new department named 'System Administrators' has been added.</p>
<p>
<img src="https://i.imgur.com/HirGRt3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Teams enable grouping of Agents from various Departments to address specific issues or users, organized through Help Topics or Ticket Filters. Navigate to 'Agents' > 'Teams' > 'Add New Team' to create one.</p>
<p>
<img src="https://i.imgur.com/cXAdRac.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Enter the necessary details for the team.</p>
<p>
<img src="https://i.imgur.com/I1zQPbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
To add Agents to the team, click on their names from the Agent list and then click on 'Create Team'.</p>
<p>
<img src="https://i.imgur.com/YhNNTkm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now, we will allow anyone to create tickets by clicking on Settings > Users</p>
<p>
<img src="https://i.imgur.com/NLJkcDB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We want to make sure 'Require registration and login to create tickets' is unchecked.</p>
<p>
<img src="https://i.imgur.com/xtczToC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now, we'll create our agents who are given access to the help desk with the intent to respond and resolve tickets.</p>
</p>
<p>
<img src="https://i.imgur.com/yCoKXqL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>Click on Agents > Add New Agent
</p>
<p>
<img src="https://i.imgur.com/nORAqaN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Let's create an agent named "Jane Doe" and set the password.<p>
<img src="https://i.imgur.com/IDGIqAB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<img src="https://i.imgur.com/ya0dQoF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We can assign access to agents by department and role.</p>
<p>
<img src="https://i.imgur.com/EeIzwD5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We can also assign the agent to a team that we created earlier.</p>
<img src="https://i.imgur.com/PQnuiAN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/nprHnpt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We also created another agent named John Doe.</p>
<p>
<img src="https://i.imgur.com/HsxSEOF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We'll now create some users for our user directory. Users can create an account and login to create tickets or to check on it's status.</p>
<p>
<img src="https://i.imgur.com/PhHCtqh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/5hobfZn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
This is our new user successfully added to the user directory.</p>
<p>
<img src="https://i.imgur.com/5zjSeyX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now it's time to configure the SLA or Service Level Agreement:</p>
<p>
<img src="https://i.imgur.com/T2d02Kp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p> Click Admin Panel > Manage > Add New SLA Plan
</p>
<p>
<img src="https://i.imgur.com/Fuwxibl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.</p>
<p>
<img src="https://i.imgur.com/3P4jOEu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We have created 3 SLA's of various severity and response times. 
</p>
<p>
<img src="https://i.imgur.com/pIH3ULS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>Next, we'll configure the help topics. In the Admin Panel go to Manage > Add New Help Topic.
</p>
<p>
<img src="https://i.imgur.com/4FXCmkp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/NJkC8wN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
<img src=https://i.imgur.com/dIbrzLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/UDawVdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
