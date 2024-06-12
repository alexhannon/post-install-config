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

- Configure Roles, Departments, and teams through the Admin panel
- Give Access to Allow Anyone to create tickets through the Admin panel
- Configure Agents (workers), Users (customers), and SLA through the Admin Panel
- Configure Help Topics through the Admin Panel
- Install Files and set up osTicket in the browser/clean up

<h2>Configuration Steps</h2>
</p>
<p>
First, I wanted to configure roles through Osticket. To do this I went to Admin Panel --> Agents --> Roles. I then made a role called Supreme Admin, which could do anything.

![image](https://github.com/alexhannon/post-install-config/assets/168659572/cd885e2d-3fcf-4dc9-a934-50bfe3147a83)

![image](https://github.com/alexhannon/post-install-config/assets/168659572/b5002ac0-06e0-4809-a79c-8561091db81e)

</p>
After I did this, I wanted to configure departments. To do this I went to Admin Panel --> Departments. I then made a department called System Administrators

![image](https://github.com/alexhannon/post-install-config/assets/168659572/d5455b1f-4cba-4010-b201-89c5d1c56344)

</p>
Once I did this, I configured Teams. To do this I went to Admin Panel --> Agents --> Teams. I then made two teams, I named one Level I support and the other Level II Support.

![image](https://github.com/alexhannon/post-install-config/assets/168659572/f46e0651-9b5f-4266-bcf2-93abbbfe98d1)


</p>
<br />

<p>
</p>
<p>
After I assigned Roles, Departments, and Teams, I needed to allow anyone to create tickets. To do this, I did Admin Panel --> Settings --> User Settings. Once I got to User Settings. I ensured that "Require registration and login to create tickets" was unchecked. This is so people can submit tickets anonymously.
 
![image](https://github.com/alexhannon/post-install-config/assets/168659572/2b347a83-2f15-4591-a01e-eb550e782247)
 
</p>
<br />

<p>
</p>
<p>
Once I did that, I needed to configure Agents (workers). I went from the Admin panel --> Agents --> Add New to do this. I added two new Agents: Jane and John. I also made it so that they were in different departments as well.

![image](https://github.com/alexhannon/post-install-config/assets/168659572/d5053ebc-9362-4c80-95e3-22d3af47d8cb)
 </p>
 After creating Agents, I created Users (customers). To do this I had to switch to the Agent Panel. From the Agent Panel --> Users --> Add New. I added two customers: Karen and Ken.

 ![image](https://github.com/alexhannon/post-install-config/assets/168659572/5011bd13-a8c6-4c0b-9091-f173b7dc1301)

 </p>
Once I was finished with that. I needed to configure the SLA. To do this, I returned to the Admin Panel --> Manage --> SLA. I then made three different severities of SLA: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, M-F business hours).

![image](https://github.com/alexhannon/post-install-config/assets/168659572/937fd4df-d733-41ec-aacb-9d9df6440cbd)

</p>
Once configuring SLA, I went ahead and configured Help Topics as well. From the Admin Panel --> Manage --> Help Topics. Once there I made four common help topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.

![image](https://github.com/alexhannon/post-install-config/assets/168659572/b536fa84-ad77-4d82-811d-2481370aebaf)

</p>
<br />
