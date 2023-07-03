<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration - COMING SOON!</h2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequistes</h2>
- Resource Group
- Virtual Machine
- Remote Desktop Connection
- Internet Information Services (IIS) Setup
- osTicket Configured

<h2>Post-Install Configuration Objectives</h2>

- Create and configure the osTicket environment
- Setup configurations as an admin
- Create roles, departments, teams, agents, and users
- Set up SLAs and create help topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/2dd7d4bc-f582-46fc-b8e9-a318364a05af" height="80%" width="80%" alt="Step #1"/>
</p>
<p>
Log into the osTicket as an admin. A role is a permission granted to the agents (help desk personnel) in the department they are in. Each role has a different set of permission that can be checked or not. We are going to create a role called supreme admin and will all the permissions will be checked. Go to Admin Panel (top right) -> agents -> roles -> add new role -> supreme admin. <br/> Then go to the permissions tab, and check all of the boxes.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/f8474313-a537-4987-b7b2-ca6c6542be07" height="80%" width="80%" alt="Step #2"/>
</p>
<p>
Now, we will create a new department called system administrators. Go to the department's tab -> add a new department.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/eb33271a-1616-40bc-8397-d1466c6df5b8" height="80%" width="80%" alt="Step #3"/>
</p>
<p>
Now create a new team. Go to agents -> teams -> add a new team. Name it Level 11 Support and add yourself as a member.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/f29bbca0-0be4-4ad2-9b6e-a9cd6e6f69b8" height="80%" width="80%" alt="Step #4"/>
</p>
<p>
Go to settings -> user settings and click require registration and login to create tickets.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/0645a631-ecc1-4c66-a81d-71e745eae5d2" height="80%" width="80%" alt="Step #5"/>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/3b45f320-9330-466f-9269-54234aee0ccc" height="80%" width="80%" alt="Step #6"/>
</p>
<p>
Now, it's time to add some agents. I added two agents Jane and John Doe. I set both of them as System Administrators and extended Jane role's to the support team.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/02d6ca3c-b12a-431e-aa3a-5dafa309c22a" height="80%" width="80%" alt="Step #7"/>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/d90e2adf-3810-49fc-b1c3-b628cb5d9ac2" height="80%" width="80%" alt="Step #8"/>
</p>
<p>
Now, it's time to add end users. End users (customers) are the people who can create tickets. Go to agent panel -> users -> add new and create whatever users you want. In my case, I added Ken and Karen Smith.
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/e2791e2a-fecd-4e41-9f2c-fd9305c045e3" height="80%" width="80%" alt="Step #9"/>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/466b3b89-bd8d-40ba-a29a-c497f24953b3" height="80%" width="80%" alt="Step #10"/>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/03c86d26-e813-4a51-bc75-3162f38aeaee" height="80%" width="80%" alt="Step #11"/>
</p>
<p>
Now, add SLAs! Go to manage -> SLA -> add new SLA plan. I added three <br/> Sev-A (1 hour, 24/7 <br/> Sev-B (4 hours, 24/7) <br/> Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://github.com/whitneydawson123/osTicket-post/assets/94804621/eb4ec2e3-2d3c-41c0-8fa8-7fa31c157da9" height="80%" width="80%" alt="Step #12"/>
</p>
<p>
End users can also choose the problem they need help with. Go to manage -> help topics -> add a new help topic. I added: <br/> 
  
  - Business Critical Outage <br/> 
  - Personal Computer Issues <br/> 
  - Equipment Request <br/> 
  - Password Reset <br/>
  
This is it for this part. In the <a href="https://github.com/whitneydawson123/osTicket-lifecycle">next part</a>, we will finish the osTicket project focusing on the ticket lifecycle.
</p>
<br />
