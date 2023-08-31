<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial we will outline the post-install configuration of the help desk ticketing system osTicket.<br />


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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> ROLES </b>
  <p>
   Once you are in the osTicket helpdesk portal you next want to define the roles. We are going to create a role called "Supreme Admin" and define what permissions that role will have.
    <p>
      
- We will go to Admin panel, Agent, and then Roles. Here is where we will add a new role.
      
- Name the role "Supreme Admin" or whatever you would like and assign all of the permissions to this role.
  
- To finish select "Add Role" at the bottom of your screen
  </p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> DEPARTMENTS </b>
<p>
 Tickets are filtered through departments so we must set up at least one for our enviroment.
 <p>

 - We will go to Admin panel, Agents, and then Departments. Here we will add a new department.

 - We will name this Department " System Admin", We have not created any "SLAs" so we will leave this as defaultfor now.

 - Now select create department at the bottom of the screen

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> TEAMS </b>
  <p>
  Teams allow you to organize agents in a way that is most beneficial to the task.
    <p>

- We are going to go to Admin panel, Agents, and then Teams. Here is where we will create our team.

- Name your team what you would like and then select the members of this team. We are currently the only agent so we will select ourself.

- Select create team at the bottom of the screen.
</p>
<br />

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> AGENTS </b>
<p>
Agents are the ones that respond to and resolve tickets.
<p>

- We are going to go to Admin panel, Agents, Add New. Here is where we will create our new agents.

- Create as many agents as you need, Make sure you name them.

- Assign your agent to a department, select their role, and the team that you want them to be on. Then create your agent. 
  
</p>
<br />

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> USERS </b>
<p>
User description
<p>

  -

  -

  -
</p>
<br />

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> SLA </b>
<p>
sla description
<p>

  -

  -

  -
</p>
<br />
