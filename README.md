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
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

We are going to create a role called Supreme Admin. Roles are the permissions granted to Agents per Department that they have access to.
<p>
<img src="https://i.imgur.com/lhuRBrG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
First make sure you're in the Admin Panel.</p>
<p>
<img src="https://i.imgur.com/89Ws8i4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We want to click on Agents > Roles > Add New Role.
</p>
<p>
<img src="https://i.imgur.com/NnpxLCH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Enter Supreme Admin into the name field > Click on Permissions.</p>
<p>
<img src="https://i.imgur.com/C7J6g8j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We will check all of the permission boxes for the Supreme Admin role, so that they have full access.</p>
<p>
<img src="https://i.imgur.com/2IfIWgO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
From Tickets > Tasks check all of the boxes.</p>
<p>
<img src="https://i.imgur.com/058QTsk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
From Tickets > Tasks > Knowledgebase check all of the boxes </p>
<p>
<img src="https://i.imgur.com/jNqtmL7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We see our new role was successfully added to the panel.</p>
<p>
<img src="https://i.imgur.com/0elZtnW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we'll add a new department. Click on Agents > Departments> Add New Department.
</p>
<p>
<img src="https://i.imgur.com/cjiPJOO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
</p>
<p>
<img src="https://i.imgur.com/jj8Dfub.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
A new department was added called System Adminstrators.</p>
<p>
<img src="https://i.imgur.com/HirGRt3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Teams will allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. Go to Agents > Team > Add New Team
</p>
<p>
<img src="https://i.imgur.com/cXAdRac.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Fill out the appropriate information.</p>
<p>
<img src="https://i.imgur.com/I1zQPbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Then you will be able to add Agents to the team by clicking on their name from the list of Agents and checking the corresponding box next to the Team name you wish to add them at the bottom of the page.</p>
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
<img src="https://i.imgur.com/PhHCtqh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/5hobfZn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/5zjSeyX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/T2d02Kp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/Fuwxibl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/3P4jOEu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/pIH3ULS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/4FXCmkp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/NJkC8wN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src=https://i.imgur.com/dIbrzLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/UDawVdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
