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

- Microsoft Azure
- Remote desktop capable device
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create virtual machine to run osTicket
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install OsTicket on target device
  connect target device to webserver be enabeling IIS and CGI located in windows features - IIS - world wide web services - CGi
  install PHP manager located in the os ticket folder we extracted and double click phpManagerforIIS install rewrite_AMD64 aswell
  extract the newly created php zip folder into the PHP folder located in the root directory
  install VC_redist.x86.exe
  install MySQL-WIN32 make sure to make the root password somthing you will remeber you will need this when you
  now that all your instalations are complete launch IIS most easaly found in the search bar as an administator
  register PHP so the webserver knows where php is located by selecting php manager ans selecting php-chi located in the php folder on the computer
  restart the IIS by selecting restart in the right corner of IIS Manager
  install osticket be extrakting the osticket zip file, copy and paste the upload folder to C:inetpub\wwwroot then rename uplod to "osTicket"
  reload IIS in the IIS manager to confirm changes
  the osTicket site will now be created on the IIS open it from the IIS manager by clicking the sites dropdown and selecting Browse*80 (http) on the right of IIS Manager
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
