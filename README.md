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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1: Azure virtual machine 
- Item 2: osTicket

<h2>Configuration Steps</h2>
<p>
In this lab we will make configurations in osTicket for use. 
</p>
<p>
Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php  
</p>
<p>
<img src="https://imgur.com/jw3Wd5N.png"/>
</p>
<p>
  Login to osTicket using the Admin User and Password that you set.  
</p>
<br />

<h3>Configuring Roles </h3>
<p>
  We configure roles to give different layers of permissions to groups of people. 
</p>
<p>
<img src="https://imgur.com/jEFjGoh.png"/>
</p>
<p>
To set roles, make sure you are in the Admin Panel and follow these steps: Agents > Roles. 
</p>
<br />

<p>
<img src="https://imgur.com/O7Se6t9.png"/>
</p>
<p>
If you press Add New Role, you will be able to name the role and give that role any number of permissions. 
</p>
<br />

<p>
<img src="https://imgur.com/VyLNflk.png"/>
</p>
<p>
I made a Supreme Admin role that has all the permissions to demonstrate. 
</p>
<br />

<h3>Configuring Departments </h3>
<p>
  Departments are used to group different departments to restrict the kinds of tickets different employees can see.  
</p>
<p>
<img src="https://imgur.com/ahBM3dZ.png"/>
</p>
<p>
To configure departments, you need to be in the Admin Panel and go to: Agents > Departments. 
</p>
<br />

<p>
<img src="https://imgur.com/Rd5wGzm.png"/>
</p>
<p>
If you press Add New Department, you will be able to make departments and later be able to direct tickets to the specific departments. 
</p>
<br />

<p>
<img src="https://imgur.com/OEzK8Ss.png"/>
</p>
<p>
I made a System Admin department to demonstrate. 
</p>
<br />

<h3>Configuring Teams </h3>
<p>
  Teams are used to pull employees in from different Departments. 
</p>
<p>
<img src="https://imgur.com/9TJTtKV.png"/>
</p>
<p>
To configure teams, you need to be in the Admin Panel and go to: Agents > Teams. 
</p>
<br />

<p>
<img src="https://imgur.com/Vc9TlzK.png"/>
</p>
<p>
If you press Add New Team, you will be able to name a Team and assign members from different departments into the Team.  
</p>
<br />

<p>
<img src="https://imgur.com/f0haiTB.png"/>
</p>
<p>
I made an Online Banking Team to demonstrate. 
<br />

<h3> Allowing anyone to create tickets. </h3>
<p>
  We are going to allow anyone to create tickets for the End-Users. 
</p>
<p>
<img src="https://imgur.com/qdE4zv8.png"/>
</p>
<p>
In the Admin Panel, go to: Settings > Users > UNCHECK box next to Require registration and login to create tickets 
</p>
<br />

<h3>Configuring Agnets </h3>
<p>
  Agents are the employees that will work in osTicket. 
</p>
<p>
<img src="https://imgur.com/ZBVLro8.png"/>
</p>
<p>
To configure Agents, you need to be in the Admin Panel and go to: Agents. 
</p>
<br />

<p>
<img src="https://imgur.com/SX1wORX.png"/>
</p>
<p>
If you press Add New Agents, you will be able to create agents and set their login so your employees can access osTicket. This is where you also configure the Departments, Permissions, and Teams of individual Agents. 
</p>
<br />

<p>
<img src="https://imgur.com/sUy2vbm.png"/>
</p>
<p>
I made Agents Jane Doe and John Doe to demonstrate. 
<br />

<h3>Configuring SLAs (Service Level Agreement) </h3>
<p>
  It is important to configure the SLA to report how urgent a ticket is and how fast the agents need to deal with it.  
</p>
<p>
<img src="https://imgur.com/JqHg4zr.png"/>
</p>
<p>
To configure SLA, you need to be in the Admin Panel and go to: Manage > SLA. 
</p>
<br />

<p>
<img src="https://imgur.com/CS8VM83.png"/>
</p>
<p>
If you press Add New SLA Plan, you will be able to create SLAs, set the grace period, and the schedule.  
</p>
<br />

<p>
<img src="https://imgur.com/SlZk7J8.png"/>
</p>
<p>
I created three SLAs: Sev-A (Grace Period: 1 hour, Schedule: 24/7), Sev-B (Grace Period: 4 hours, Schedule: 24/7), Sev-C (Grace Period: 8 hours, Business Hours) 
<br />

<h3>Configuring Help Topics </h3>
<p>
  Help Topics are the End-Users to specify the reason for their tickets. 
</p>
<p>
<img src="https://imgur.com/h3wQIT9.png"/>
</p>
<p>
To configure Help Topics, you need to be in the Admin Panel and go to: Manage > Help Topics
</p>
<br />

<p>
<img src="https://imgur.com/VzI5Xla.png"/>
</p>
<p>
If you press Add New Help Topic, you will be able to create Help Topics, set which department it belongs to, and the ticket’s SLA plan.  
</p>
<br />

<p>
<img src="[https://imgur.com/SlZk7J8](https://imgur.com/5s1znQl).png"/>
</p>
<p>
I created five new Help Topics: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other. 
<br />
