<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Setup </h1>
This tutorial outlines the post-installation setup of osTicket. This setup includes creating agents, users, departments, teams, and roles. Different types of SLA's will be configured as well that outlines the ranges in severity of the tickets we will be creating.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (version 22H2)

<h2>List of Prerequisites</h2>

- Microsoft Web Platform Installer
- OsTicket V1.15.8
- HeidiSQL

<h2>Installation Steps</h2>


<p>  
<img src = "https://i.imgur.com/FoDQra2.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>Overview</p>
                                                                                                     
<p>
 <img src = "https://imgur.com/6NREZBJ.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>

 
</p>                                                                                                  
<p>1. Sign into osTicket as a agent. 
                                                                                                
</p>

<p>
<img src =  "https://imgur.com/aX4MTpb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

 <p>
2. Configure roles within osTicket: Admin Panel -> Agents -> Roles and Supreme Admin

</p>                                                                                                    
                                                                                                     
<p>
<img src= "https://imgur.com/q0GnMIU.png" " height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

<p>
                                                                                                 
                                                                                                 
                                                                                                 
3. Configure Departments:
Admin Panel -> Agents -> Departments
                                                                                                
</p>
<br />

<p>
<img src="https://imgur.com/0phoHoR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
                                                                                                                                                                                            
                                                                                               
<p>

4. Configure Teams:
Admin Panel -> Agents -> Teams

</p>
<br />

 <p>
<img src="https://imgur.com/0gEN48I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>                                                                                              
                                                                                               
                                                                                               
<p> 5. Allow anyone to create tickets: Make sure "Registration Required" section remains unchecked.
Admin Panel -> Settings -> User Settings

</p>
<br />

<p>
<img src="https://imgur.com/9uBbnwf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
<p>
<img src="https://imgur.com/kjmoNRP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>                                                                                                 
                                                                                               
                                                                                               
<p>
6. Configure Agents (workers):
Admin Panel -> Agents -> Add New

</p>
<br />

<p>
<img src="https://imgur.com/443AMLK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Configure Users (customers):
Agent Panel -> Users -> Add New

</p>
<br />

<p>
<img src="https://imgur.com/ZZAtNLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
                                                                                               
<p>
<img src="https://imgur.com/GFE54nV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>                                                                                               
                                                                                               
<p>
8. Configure SLA:
Admin Panel -> Manage -> SLA

</p>
<br />

<p>
<img src="https://imgur.com/n9CjduH.png"
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src="https://imgur.com/yYxg95n.png"
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
9. Configure Help Topics:
Admin Panel -> Manage -> Help Topics

</p>
<br />

<p>
10. Congratulations! Now you have learned how to create both users, departments, and tickets on osTicket.
</p>
<br />
