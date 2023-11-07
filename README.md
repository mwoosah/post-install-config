<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the prerequisites and post-installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- osTicket installed and ready to go
- Admin login credentials


<h2>Login URL Links</h2>

- Help desk login page: http://localhost/osTicket/scp/login.php 

- End Users osTicket URL: http://localhost/osTicket/

<h2>Configuration Steps</h2>



    *GENERAL OVERVIEW*

<p>
<img src="https://i.imgur.com/tEhuwvw.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 1:
  *Configuring roles*
1. Admin Panel -> Agents -> + Roles
2. Definition: Supreme Admin > Permissions: Check off all the boxes

</p>
<br />

<p>
<img src="https://i.imgur.com/a4uhpEU.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 2:
  *Configure Departments*
1. Admin Panel -> Agents ->  + Departments
2. Name: System Administrators > + Create Department

</p>
<br />

<p>
<img src="https://i.imgur.com/frQYvUS.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 3:
  *Configure Teams*
 1. Admin Panel -> Agents ->  + Teams
2.  Name: Level I Support > Members > Add any agent
3. Name: Level II Support > Members > Add any agent

<p>
<img src="https://i.imgur.com/fLQUUOM.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 4:
  *Allow anyone to create tickets*
  1. Admin Panel -> Settings -> User Settings
2. Registration Required: Require registration and login to create tickets (can or uncheck the box)

<p>
<img src="https://i.imgur.com/1v90xFD.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 5:
*Configure Agents (workers)*
1. admin Panel -> Agents -> + Add New
2. Name: Jane Doe > Email Address: Jane.Doe@osticket.com > Username: Jane.Doe > Password: Password1 > Set
3. Name: John Doe > Email Address: John.Doe@osticket.com > Username: John.Doe > Password: Password1 > Set

<p>
<img src="https://i.imgur.com/VDUPeiO.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 6:
  *Configure Users (customers)*
  1. Agent Panel -> Users -> + Add User (User Directory)
2. Email Address:Karen@osticket.com > Full Name: Karen Karen
3. Email Address:Ken@osticket.com > Full Name: Ken Ken

<p>
<img src="https://i.imgur.com/8EyKljs.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/cin8iMs.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 7:
  *Configure SLA*
  1. Admin Panel -> Manage -> + SLA
2. Sev-A (1 hour, 24/7)
3. Sev-B (4 hours, 24/7)
4. Sev-C (8 hours, business hours)

<p>
<img src="https://i.imgur.com/pDIVINT.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 8:
  *Configure Help Topics*
1. Admin Panel -> Manage -> + Help Topics
2. + Business Critical Outage
3. + Personal Computer Issues
4. + Equipment Request
5. + Password Reset
 
