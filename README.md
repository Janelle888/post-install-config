<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial we will outline the post-install configuration of the help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- ### [YouTube: Video](https://www.youtube.com)

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
  
![image](https://github.com/Janelle888/post-install-config/assets/142438143/ac4fefc3-2d54-4d5f-ad55-da9b647c3573)



</p>
<p>
<b> ROLES </b>
  <p>
   Once you are in the osTicket helpdesk portal you next want to define the roles. We are going to create a role called "Supreme Admin" and define what permissions that role will have.
    <p>
      
- We will go to Admin panel, Agent, and then Roles. Here is where we will add a new role.
      
- Name the role "Supreme Admin" or whatever you would like and assign all of the permissions to this role.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/69a163ff-3bfe-41d9-af8c-a4a9074fcb34)

  
- To finish select "Add Role" at the bottom of your screen

![image](https://github.com/Janelle888/post-install-config/assets/142438143/ff8060ff-21bf-4734-87ca-5095e255a189)

  
  </p>
<br />

<p>

</p>
<p>
<b> DEPARTMENTS </b>
<p>

![image](https://github.com/Janelle888/post-install-config/assets/142438143/2916416f-7381-4ce6-b688-72050633c262)

  
 Tickets are filtered through departments so we must set up at least one for our enviroment.
 <p>

 - We will go to Admin panel, Agents, and then Departments. Here we will add a new department.

 - We will name this Department " System Admin", We have not created any "SLAs" so we will leave this as defaultfor now.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/9890b4c9-167f-4a1e-a520-3c6ff28a6f83)


 - Now select create department at the bottom of the screen

![image](https://github.com/Janelle888/post-install-config/assets/142438143/3f4ab176-03ee-4f34-8295-9e1e42d6a358)
  

</p>
<br />

<p>

</p>
<p>
<b> TEAMS </b>

![image](https://github.com/Janelle888/post-install-config/assets/142438143/5a4f73a6-9bac-4ef7-841a-80b10e118a26)

  
  <p>
  Teams allow you to organize agents in a way that is most beneficial to the task.
    <p>

- We are going to go to Admin panel, Agents, and then Teams. Here is where we will create our team.

- Name your team what you would like and then select the members of this team. We are currently the only agent so we will select ourself.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/5e09e559-5ab8-498a-9f0c-045e92cb3b14)


- Select create team at the bottom of the screen.
</p>
<br />

</p>
<br />

<p>

</p>
<p>
<b> AGENTS </b>

![image](https://github.com/Janelle888/post-install-config/assets/142438143/401eab12-6e18-4c97-a009-74fd95556b7a)
 
<p>
Agents are the ones that respond to and resolve tickets.
<p>

- We are going to go to Admin panel, Agents, Add New. Here is where we will create our new agents.

- Create as many agents as you need, Make sure you name them.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/9e569402-2195-48e5-bded-9bfacfd759c2)

- Assign your agent to a department, select their role, and the team that you want them to be on. Then create your agent. 
  
</p>
<br />

</p>
<br />

<p>
</p>
<p>
<b> USERS </b>

![image](https://github.com/Janelle888/post-install-config/assets/142438143/b041bcc4-37ba-41f3-9157-ec42cf8e238a)

<p>
Users are the people that we are providing support to.
<p>

  - We are going to go to Agent panel, Users, and then add new. Here is where we will create our user.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/27b18f0e-b426-4545-956e-abe5ba73baa0)
 
  - Create your user, then select add user.

</p>
<br />

</p>
<br />

<p>
  
</p>
<p>
<b> SLA </b>

![image](https://github.com/Janelle888/post-install-config/assets/142438143/5e50bfeb-6e52-40e3-a564-548ef348bedf)

  
<p>
An SLA is a target for how long it should take you to resolve a specific ticket.
<p>

  - We are going to go to Admon panel, Manage, and then SLA. Here we will create 3 different levels of SLA.

![image](https://github.com/Janelle888/post-install-config/assets/142438143/dde3dbd4-7c93-4bbb-992a-b82597353415)

  -Select 3 different levels of SLA to use for osTicket. Then select add paln.
</p>
<br />

<p>
  
  Great! We can now create tickets as a user and solve them as an agent to see how the process works.
</p>
