<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enabling information internet services(IIS)
- Install Web Platform Installer
- PHP manager configuration
- osTicket and mySQL install/configuration

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Un3G6U0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I opened the Control Panel, went to Windows features, enabled IIS, then navigated to Application Development features and enabled CGI. After that, I checked that all Common HTTP Features were enabled and clicked 'OK'. Next, I tested the setup by opening a web browser and entering '127.0.0.1', the local host of IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ovkr32Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloading and installing PHP, I run IIS as an administrator. Then, I register and enable the PHP manager. Next, I download and set up the osTicket files. Finally, I go to PHP Extensions and enable any extensions that osTicket recommends.
</p>
<br />

<p>
<img src="https://i.imgur.com/iKAo5u8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I installed and set up MySQL. After that, I created a session and an osTicket database. Then, I set up my osTicket account and installed it on the server. Finally, I logged into the new account as an admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/NuXxbkG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
