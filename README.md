<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- A Web Server – Something that can run websites (Apache or Nginx).

- PHP Installed – This is the language osTicket is built in (Version 8.0–8.2 is best).

Also make sure some “extras” are enabled: mysqli, gd, imap, mbstring, xml, intl, json, zip.

- A Database – MySQL or MariaDB to store ticket info.

- An Email Account – So osTicket can send/receive ticket updates.

- Folder Permissions – The osTicket folders /include and /attachments need “write” access so it can save files.


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/v79FVHq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1.Delete the Setup Folder
The first image shows me deleting the setup folder via Windows File Explorer. This is step 1 in cleaning up after installation and preventing unauthorized reconfiguration<br />

<p>
<img src="https://i.imgur.com/wIRq3P9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2.Fill in Configuration Details
The second image displays the osTicket installer interface where you input system settings like URL, helpdesk name, admin account, and email crucial for the setup wizard/p>
<br />

<p>
<img src="https://i.imgur.com/GElM69x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Finalize Installation & Permissions
The third image illustrates the final installer screen confirming successful setup. It also highlights setting file permissions (e.g., modifying ost-config.php)</p>
<br />
