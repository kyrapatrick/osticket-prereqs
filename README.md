<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Outline prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Installation of Internet Information Services (IIS) in Windows.
- Open IIS as an administrator and register PHP manager from within IIS.
- Install osTicket with additional extensions enabled.
- Reload IIS with osTicket created as the MySQL Database.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/F2CnIN6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of Internet Information Services, allowing osTicket to run out of a website.
</p>
<br />

<p>
<img src="https://i.imgur.com/VVNbMv0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IIS installation continued with PHP manager, a generalized scriting language used by osTicket, registered within IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/Wsxjrw6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A database named "osTicket" is created within HeidiSQL, allowing connection to SQL server & establish a database used by osTicket.
</p>
<br />
<p>
<img src="https://i.imgur.com/rVhcB0Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Installation of osTicket completed along with completion of SQL Database.
</p>
<br />
