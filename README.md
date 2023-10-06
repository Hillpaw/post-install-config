# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket and is a follow-up from the <a href="https://github.com/Hillpaw/osticket-prereqs/"> previous preqreuisite setup.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuring Roles
- Configuring Departments and Teams
- Configuring Agents
- Configuring SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/bNMytwg.png" alt="Admin Panel"/>
</p>
<p>
To begin, first make sure that you are on the Admin Panel. At the top-right, click on the words "Admin Panel" to swap over.
</p>
<br />

<p>
<img src="https://i.imgur.com/CVZNIpg.png" alt="Roles"/>
</p>
<p>
Next we are going to look at how to configure Roles.
After being on the Admin Panel, towards the top you will go to Agents, and then select Roles.
Once you have done that, you will then click "Add New Role"
This is where you will be able to name and assign permissions to the role.
</p>
<br />

<p>
<img src="https://i.imgur.com/pzkt9Vl.png" alt="Departments"/>
</p>
<p>
Next we are going to look at how to configure Departments.
Admin Panel -> Agents -> Departments 
You will then Add New Department. You will be greeted with a handful of options to define the department you wish to setup, as well as which Agents have access to the Department. After all is done, click Create Dept. to get it running!
</p>
<br />

<p>
<img src="https://i.imgur.com/uM4ghq5.png" alt="Teams"/>
</p>
<p>
Next we are going to look into Teams. Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or suer vis a Help Topic or Ticket Filter.
Admin Panel -> Agents -> Teams
You will then Add New Team. In here you can name the team, set its status, Team Leader, and select any Agents you wish to assign to the team. Once all is done, click Create Team to get it going.
</p>
<br />

<p>
<img src="https://i.imgur.com/duuPqYX.png" alt="Agents"/>
</p>
<p>
Next we are going to look into Agents. 
Admin Panel -> Agents -> Add New

Agents are given access to the help desk with the intent to respond and resolve the tickets. You will be able to make the account for the Agent, give them access to a Department and Primary Role, permissions, and assign them to a team.
</p>
<br />

<p>
<img src="https://i.imgur.com/8MSXFjk.png" alt="SLA"/>
</p>
<p>
Next we are going to look into SLA. SLA is short for Service Level Agreements, and it provides a length of time in which the help desk Administrator expects tickets to be close.
Admin Panel -> Manage -> SLA

Adding a new SLA Plan lets you assign the Grace Period (in hours), Schedule (24/7 or 24/5), etc. 

Once all is done, create your SLA plan so you're able to assign them to your incoming tickets!

</p>
<br />
<p>
<img src="https://i.imgur.com/oneR6AY.png" alt="Help Topics"/>
</p>
<p>
Next we are going to look into Help Topics. 
Admin Panel -> Manage -> Help Topics

Help Topics will help streamline your end-user's help desk experience to ensure proper assignment and prompt response to the ticket. Feel free to create as many as needed.
<br />
