<h1>osTicket Lab</h1>


<h2>Description</h2>
Hands-on labs from my osTicket Fundamentals training. Includes screenshots, steps, and lessons learned.
<br />


<h2>Utilities Used</h2>

- <b>osTicket Platform</b>
- <b>Remote Desktop Connection</b>

<h2>Environments Used </h2>

- <b>Virtual Machines (Windows)</b>
- <b>Microsoft Azure</b>

<h2>Program walk-through: Installing osTicket</h2>

<p align="center">
Creating VM via Microsoft for running osTicket: <br/>
<img src="https://i.imgur.com/VKdSeBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enabeling IIS (Internet Information Services) in windows with CGI. 1/2: <br/>
<img src=https://i.imgur.com/zL9vVR9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Page displayed now that services are enabled. 2/2: <br/>
<img src=https://i.imgur.com/KC8kMkw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enabeling needed PHP extentions to enhance performance of software (osTicket): <br/>
<img src=https://i.imgur.com/qFOOq3y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Removing all inherited permissions: <br/>
<img src=https://i.imgur.com/tsSXexW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enabeling permissions for "Everyone" 1/2: <br/>
<img src="https://i.imgur.com/y943E8O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2/2: <br/>
<img src="https://i.imgur.com/d2x9YzJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a database via Heidi SQL: <br/>
<img src="https://i.imgur.com/kkguyRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
osTicket successfully installed: <br/>
<img src="https://i.imgur.com/8Us7xaX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful creation of database *Foundation files on back-end*: <br/>
<img src="https://i.imgur.com/8NBY4yF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful log-in: <br/>
<img src="https://i.imgur.com/ElWuLH3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2/2: <br/>
<img src="https://i.imgur.com/tEfmLg0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Post-Installation Set-up</h2>
<p align="center">
Configuring roles: <br/>
<img src="https://i.imgur.com/FLKv9Jq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding new role: <br/>
<img src="https://i.imgur.com/cuDzt3Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Granting Permissions: <br/>
<img src="https://i.imgur.com/Nv86Mcm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Role has been added successfully: <br/>
<img src="https://i.imgur.com/17FCfsj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring departments: <br/>
<img src="https://i.imgur.com/oGE7I7l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding new department (Sys Admins): <br/>
<img src="https://i.imgur.com/dgPofZR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Department successfully added: <br/>
<img src="https://i.imgur.com/HnQCFTw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring teams: <br/>
<img src="https://i.imgur.com/Vpni4QK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring set-up to allow anyone to be able to submit a ticket. *Confirming "Registration Required" setting is off: <br/>
<img src="https://i.imgur.com/kFpkj6A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirming agents: <br/>
<img src="https://i.imgur.com/T1BCrjq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a user (John Doe): <br/>
<img src="https://i.imgur.com/LWd7F9M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ensuring proper access is granted to the new user: 1/2 <br/>
<img src="https://i.imgur.com/ygyK8tp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2/2: <br/>
<img src="https://i.imgur.com/H7wnN8x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Employees successfully added to system: <br/>
<img src="https://i.imgur.com/T7RGFNp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring Users (Customers): 1/2 <br/>
<img src="https://i.imgur.com/x30kq0G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Users created successfully: 2/2 <br/>
<img src="https://i.imgur.com/SOTULBT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring SLA plans: <br/>
<img src="https://i.imgur.com/xMVKFYL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a new SLA plan: <br/>
<img src="https://i.imgur.com/zFbfTeb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Completed configured SLAs: <br/>
<img src="https://i.imgur.com/Lr0IWAJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring help topics: <br/>
<img src="https://i.imgur.com/NQ2RhVX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating new help topic: <br/>
<img src="https://i.imgur.com/kD1q3KO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successfully added 4 new topics: <br/>
<img src="https://i.imgur.com/wLYInVG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

















