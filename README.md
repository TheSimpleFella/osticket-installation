
# osticket-installation
19 Simple steps to install osTicket successfully.
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Easy Installation without the stress.</h1>
Easy steps to install the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Steps to install osTicket successfully.</h2>

-1.Enable Internet Information Services (IIS) in your Windows OS using CGI.
-Open Control Panel
-Select "Programs"
-Select "Turn Windows Features ON/Off."
-Select and Open Internet Information Services.
-Open "World Wide Services"
-Open "Application Developlement Features."
-Select "CGI" then select "OK."

-2.Install PHP Manager for IIS.

-3.Install Rewrite module.

-4.Create a PHP folder in your C: directory.

-5.Install PHP 7.3.8.

-6.Unzip PHP 7.3.8. onto your PHP folder.

-7.Install VC redist.x86.exe

-8.Install MySQL 5.5.62.
-Typical Setup
-Launch Config. Wizard after you install.
-Standard configuration.
-Set password to Password1 or create your own.
-"Execute"

-9.Register PHP from within IIS.

-10.Stop and start the IIS server to update.

-11.Install current version of osTicket.
-Extract and xopy "upload" folder to C:\inetpub\wwwroot.
-Within C:\inetpub\wwwroot change "upload" to "osTicket".

-12.Go to sites, Default, osTicket.
-Look on the right side of the IIS screen. Click "Browse*80". 

-13.Open PHP Manager.
-Enable: php_imap.dll, php_intl.dll, php_opcache.dll
-Refresh the osTicket on your browser to see the changes.

-14.Open C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
-Change ost-sampleconfig.php to ost-config.php.

-15.Right click ost-config then select Properties.
-Disable inheritance then remove all.
-New permissions, give to "Everyone", select all.

-16. Set up you osTicket in your browser. Steps 18 and 19 are on the same page. I accidentally closed out both virtual machines before taking the screen shots. Scroll to the bottom of the osTicket page in your browser and fill in the remaining boxes.

-17.Open Heidi SQL
-Create new session, root/Password1.
-Connect to session.
-Create a database called "osTicket".

-18.Continue setting up osTicket in the browser.
-Enter MYSQL information.

-19.Select continue.
-A "Congratulations" message should show on your screen.

<h2>Screenshots of Steps</h2>

<p>
<img src="https://i.imgur.com/rJmaadl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2
</p>
<br />

<p>
<img src="https://i.imgur.com/SbvfVLA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2
</p>
<br />

<p>
<img src="https://i.imgur.com/dValxQb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3
</p>

<p>
<img src="https://i.imgur.com/ZW6TR1G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4
</p>

<p>
<img src="https://i.imgur.com/UWltMeS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5
</p>

<p>
<img src="https://i.imgur.com/vYrEmbS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6
</p>

<p>
<img src="https://i.imgur.com/SH293WK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7
</p>

<p>
<img src="https://i.imgur.com/JY7orDQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8
</p>

<p>
<img src="https://i.imgur.com/kdR3pHV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9
</p>

<p>
<img src="https://i.imgur.com/4sqK953.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 10
</p>

<p>
<img src="https://i.imgur.com/lGZjW2t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 11
</p>

<p>
<img src="https://i.imgur.com/S6TVgB8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 12
</p>

<p>
<img src="https://i.imgur.com/DYSaLpX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 13
</p>

<p>
<img src="(https://i.imgur.com/RJODXpg.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 14
</p>

<p>
<img src="https://i.imgur.com/oC4kaPR.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 15
</p>

<p>
<img src="https://i.imgur.com/mIVPTfA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 16
</p>

<p>
<img src="https://i.imgur.com/pMSVBKI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 17
</p>

<p>
<img src="https://i.imgur.com/mIVPTfA.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 18
</p>

<p>
<img src="https://i.imgur.com/pp8Plyi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 19. This step is on the same page as step 18.
</p>

<p>
<img src="https://i.imgur.com/oeZI4GD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Good job you did it!
</p>
<br />
