
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

-16. Set up your osTicket in your browser. Steps 18 and 19 are on the same page. 
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
<img src="https://i.imgur.com/rJmaadl.png" height="80%" width="80%" alt="Step 1"/>
</p>
Step 1
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224501153-f2015b7c-163b-4a00-bec9-d54d53bd7d29.png" height="80%" width="80%" alt="Step 1"/>
</p>
Step 2
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224501486-f2142ab7-6a65-4199-8339-8383abffc6a4.png" height="80%" width="80%" alt="Step 3"/>
</p>
Step 3
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224501584-9ae2ea0f-47ab-4275-a865-0c5a20838cb5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 4
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224501699-e2e5c860-efa7-4cb7-a914-92d51f06c122.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 5
</p>

<p>
<img src="https://user-images.githubusercontent.com/126700220/224502135-9a9f9ff3-5682-46b4-9115-2bb69040852b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 6
</p>



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502157-fead8fa4-ea0d-4721-9369-4c95928e34da.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502174-0db640a1-eee5-4f50-8ec4-7e6adcf5956d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 8
</p>



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502200-f74c71cd-8e3b-43c7-9d84-ea7f833c68ab.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 9
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/224502221-49f76209-a33c-4efa-a172-3f204b86ca1f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 10
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/224502241-4fed2d28-8605-41c2-9bde-ff674942a75f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 11
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502264-73b5ab38-8e46-4fa6-a5ae-84c5de73b970.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 12
</p>

<p>
<img src="https://user-images.githubusercontent.com/126700220/224502282-7c85492f-9fad-4b43-8431-6ba8cb381034.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 13
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502301-41dd2139-85aa-474e-aa75-42bb21e6083b.png"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 14
</p>

<p>
<img src="https://i.imgur.com/oC4kaPR.png" alt="Disk Sanitization Steps"/>
</p>
Step 15
</p>
<br />



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502339-7cd7a5b7-3117-4e9b-856d-90e8951e1c47.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 16.  Set up your osTicket in your browser. Steps 18 and 19 are also on the same page.
</p>



<p>
<img src="https://user-images.githubusercontent.com/126700220/224502462-bfdde141-12bf-49ae-933b-0a11dd07d290.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 17
</p>



<p>
<img src="https://user-images.githubusercontent.com/126700220/225052564-6db1230b-9740-4959-9101-4d5c5f4fc926.png" width="80%" alt="Disk Sanitization Steps"/>
<p>
Step 18
</p>
<br />


<p>
<img src="https://user-images.githubusercontent.com/126700220/225053801-2d54545a-3af5-45d7-9380-58b6bd83f794.png"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 19. This step is on the same page as step 16 and 18. Click "INSTALL".
</p>
<br />


<p>
<img src="https://user-images.githubusercontent.com/126700220/224502540-d5fe63e0-edb1-49d1-aa13-1ce19a818a6d.png"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Good job you did it!
</p>
<br />
