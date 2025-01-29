<p><img src="https://imgur.com/n839Ura.png"/></p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. 
We've already created a Virtual Machine and launched a remote desktop. We also turn the Virtual Machine into a webserver allowing osTicket to operate on it. To follow these stips, click link. https://github.com/mmtroyinfotech/osticket-prereqs<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

After installation enter link in URL:
(http://localhost/osTicket/scp/login.php) into osTicket VM.

Login with username and login created during Installation.

<img src="https://imgur.com/ZlNPUQy.png"/>

Configure Roles (for grouping permissions)
- Admin Panel
- Agents
- Roles
- Supreme Admin
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

### [Youtube: How to Configure roles and other in osTicket](https://www.youtube.com/watch?v=0Cy6FPgIfEc)

<h2>Admin Panel</h2>
<p>
<img src="https://imgur.com/Gabs5fx.png"/>
</p>
<h2>Agent Panel</h2>
<p>
<img src="https://imgur.com/SD7UABR.png"/>
</p>
<br />

