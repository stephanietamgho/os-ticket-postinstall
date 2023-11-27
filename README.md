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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure new Roles
- Configure new Departments
- Configure new Teams
- Allow anyone to create tickets
- Configure new Agents
- Configure new Users
- Configure new SLAs
- Configure new Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/UoBOnJv.png" height="80%" width="80%" alt="osticket-loginpage"/>
</p>
<p>
Log in to your Help Desk portal with the credentials you created during the installation phase.
</p>
<br />

<p>
<img src="https://i.imgur.com/racELsD.png" height="80%" width="80%" alt="osticket main page"/>
</p>
<p>
On your portal ensure you run as the Administrator. If "Agent Panel" is displayed, you are, in fact, running as the Admin. Otherwise, click on Admin Panel to see the Admin portal from which we are going to set up new configurations.
</p>
<br />

<p><h2>1. CONFIGURE NEW ROLES </p></h2>
<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role.
</p>
<br />


<p>
<img src="https://i.imgur.com/gCBupbm.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/uDq4oqM.png" height="80%" width="80%" alt="New roles configuration"/>
<img src="https://i.imgur.com/dxo957R.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
You may edit its permission tickets settings: Permissions > Tickets and,  permission tasks settings: Permissions > Tasks.
</p>
<br />



<p><h2>2. CONFIGURE NEW DEPARTMENTS </p></h2>
<p>
<img src="https://i.imgur.com/lyYvdzn.png" height="80%" width="80%" alt="New Department configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Departments > Add New Role.  
</p>
<br />


<p>
<img src="https://i.imgur.com/oCHbCAW.png" height="80%" width="80%" alt="New department configuration"/>
</p>
<p>
Name it :System Administrators" and keep its default settings.
</p>
<br />


<p><h2>3. CONFIGURE NEW TEAMS </p></h2>
<p>
<img src="https://i.imgur.com/uJcVeIm.png" height="80%" width="80%" alt="New Teams configuration"/>
</p>
<p>
Still on the Admin Panel, go to Agents > Teams > Add New Teams. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/eCYNKoV.png" height="80%" width="80%" alt="New Teams configuration"/>
</p>
<p>
Name it however you like. I named mine "Level II Support", that'll handle more important matters.
</p>
<br />


<p>
<img src="https://i.imgur.com/wfALegn.png" height="80%" width="80%" alt="New Team configuration"/>
</p>
<p>
I also set myself as a memeber of the Level II support department. Go to the neighboring tab " Member", clicked on my name and "Add".
</p>
<br />


<p><h2>4. ALLOW ANYONE TO CREATE A TICKET </p></h2>
<p>
<img src="https://i.imgur.com/asOFNcN.png" height="80%" width="80%" alt="New tickets creation"/>
</p>
<p>
On the Admin Panel, go to Agents > Settings > User, and allow anyone to create tickets. Make sure you also check that registration is required. 
</p>
<br />

<p><h2>5. CONFIGURE NEW AGENTS (WORKERS) </p></h2>
<p>
<img src="https://i.imgur.com/IbjdNJz.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Add New Agent. We will create two agents: John Clear and Jane Doe.
</p>
<br />


<p>
<img src="https://i.imgur.com/1g8ucDv.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
Register John's full name and email address where users may reach him. Then set his login credentials by setting a new password. Click "password".
</p>
<br />


<p>
<img src="https://i.imgur.com/QeWFnwi.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
When setting John's or an agent's password, uncheck the email confirmation prompt.
</p>
<br />


<p>
<img src="https://i.imgur.com/O5f5Isb.png" height="80%" width="80%" alt="New agents configuration"/>
<img src="https://i.imgur.com/HUQa0fJ.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
You may configure your agent's permissions, assign your agent a department, a role as well, using the neighborings tabs.
</p>
<br />


<p>
<img src="https://i.imgur.com/gpYZczx.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
The new agents' list.
</p>
<br />


<p><h2>6. CONFIGURE NEW USERS (CUSTOMERS) </p></h2>
<p>
<img src="https://i.imgur.com/racELsD.png" height="80%" width="80%" alt="New USERS configuration"/>
</p>
<p>
Switch to Agent Panel by clicking on it. 
</p>
<br />


<p>
<img src="https://i.imgur.com/lxX7CXC.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
I will create two users but you can create as many as you want. 
</p>
<br />


<p>
<img src="https://i.imgur.com/5iFr2GM.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
On the Agent Panel, go to Users > Add New User. 
</p>
<br />


<p>
<img src="https://i.imgur.com/0xxTZom.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
I created Teddy's profile and followed the same procedure with Suszy's. Then I click on "Add User".
</p>
<br />

<p><h2>7. CONFIGURE NEW SLA </p></h2>
<p>
<img src="https://i.imgur.com/gUqOYzp.png" height="80%" width="80%" alt="New SLA configuration"/>
</p>
<p>
Back to the Admin Panel, go to Manage > SLA > Add SLA plan
</p>
<br />


<p>
<img src="https://i.imgur.com/jY4Ybid.png" height="80%" width="80%" alt="New SLA configuration"/>
</p>
<p>
I created 3 SLAs (SEV-A, SEV-B, SEV-C) with varying severity and deadlines to solving issues. SEV-A is considered the most pressent issues that may severely impact the business operations. Thus I set its SLA to 1 hour. 
</p>
<br />


<p>
<img src="https://i.imgur.com/IGKhC2K.png" height="80%" width="80%" alt="New SLA configuration"/>
</p>
<p>
I set SEV-B and SEV-C of decreasing importance and with a more generous SLA, as shown. 4 hours on a 24/7 schedule for SEV-B and 8 hours on business hours for SEV-C matters.
</p>
<br />


<p><h2>8. CONFIGURE HELP TOPICS </p></h2>
<p>
<img src="https://i.imgur.com/LiGTa8B.png" height="80%" width="80%" alt="New Help Topics configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Manage > Help Topics > Add New Help Topic. 
</p>
<br />


<p>
<img src="https://i.imgur.com/ddXJ1Fi.png" height="80%" width="80%" alt="New Help Topics configuration"/>
</p>
<p>
I named mine "Business Critical Outage" which is the most pressing issue. Name yours.
</p>
<br />


<p>
<img src="https://i.imgur.com/mnDqfpT.png" height="80%" width="80%" alt="New Help Topics configuration"/>
</p>
<p>
Click the "New Ticket Options" the tab next to the "Help Topic information" tab you've entered your help topic's name. Assign it a SLA group. Due to the severity of a business outage, I assigned it to SEV-A thus has 1 hour to be addressed and solved.
</p>
<br />


<p>
<img src="https://i.imgur.com/fGVORyP.png" height="80%" width="80%" alt="New Help Topics configuration"/>
</p>
<p>
I also assigned this type of issue to a particular worker (here John).
</p>
<br />
<br />
<br />
<br />

<p><h2>VOILÀ 😃</h2>

