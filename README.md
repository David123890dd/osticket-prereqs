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



<h2>Installation Steps</h2>

<p>
 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/97996bcc-4910-4c5b-842a-5351e5d8adee)

</p>
<p><h3>After running the VM(virtual machine), go to Control Panel inside the VM -> Programs -> Turn Windows features on or off, and check "Internet Information Services" box.</h3>
</p>
<br />

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/126eedfb-8008-4a8f-bec8-a503d6a0f14b)

<p>

</p>
<p>
<h3>Under "Internet Information Services", Check the "World Wide Web Services" box then click ok.</h3>
</p>
<br />

<p>

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/ad1b6936-45f6-454b-82e8-3ec86eb9b013)
<br/>
</p>
<p>
<h3>Under "Common HTTP features", Check all the boxes inside it.</h3>

 
 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/5c59f4b9-9aef-4d6f-a031-4aee6a730d38)
 
<h3>Check CGI under Application Development Features</h3>
</p>
<br />

<p>


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/3f9f5520-9bf6-4b0b-a6e1-ccf1aa99385b)


</p>

<p>
 <br/>
<h3>To check if ISS is working, Go to a search engine and type "127.0.0.1" and you should have a web that looks like this.</h3>
</p>
<br />


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/398cc3bb-6ff0-403c-b100-8846f51e4ca5)

<p>
<h3>Create a new folder named "PHP"</h3>

</p>
<p>
 
 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/f43ef26d-7dc6-4d0b-bdcd-c8c3786b571d)

<h3>Go to this <a href="https://docs.google.com/document/d/1zauJKAndmBDyZ0eXRvAOSF9e0xWSQmLket6CgvUPITc/edit">link</a> and you will see downloadable links</h3>
</p>
<br />

</p>
<p>

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/c534f7f6-5535-4dc9-9083-aa996b96e99e)
 


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/7a2a955f-958b-4c7a-875f-6e185e62170c)

<h3>Download the first link and click "Download anyway"</h3>


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a7762efb-fa8f-4dbe-a307-84b3dda8e1b8)


<h3>Open file, and go through the setup. Download the second link, same way as the first link. Go through the setup. For the third download, after the download, take all the contents and put it inside the PHP folder that was created.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/03f5e7ac-f889-47ba-b50d-be9de9ba3968) 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/b85372fd-b096-4fee-83b1-e9803bcb1f43)

<h3> Download the fourth and the fith link. For the fifth choose a typical install</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/33aedb94-f02c-4cb9-ba92-dfdc97adddc7)
<h3>standard config.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/d6664479-a427-48b9-99d9-6924475edf46)




![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/d12a0038-f491-466b-9ed4-bc55b3fc2018)

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a06893d7-2450-4711-bb16-11c9b6f66e7a)

<h3> Setup your password and remember it because you will need to use it later.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/7bf2b25f-62d0-4025-b7ba-4b1eeac80fcc)

<h3>open Internet Information Service Manager</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/5d144664-e818-417b-8a1b-3d360e092cc4)

<h3>Double click PHP manager</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/69753cd8-249a-4442-8963-a9d26e7d47c8)

<h3>select the "php-cgi" under the PHP folder as the path and click "ok"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/69c03e55-01fa-4d59-b44f-bbaf82a9b99e)
<h3>hit the "home" icon</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a679600a-a307-4ba3-adcd-3d34359921ae)


<h3> click "Restart"</h3>
 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9402fcc2-663a-4b42-8cca-67b88b452d56)

<h3>Download the sixth link </h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/4bf5e296-01bb-4436-b077-31e21b9a64a2)

<h3>open the folder and extract the "upload" folder to wwwroot under inetpub </h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/fb2cb808-1372-43e3-babe-091b079ad726)

<h3>rename the "upload" folder to **EXACTLY** "osTicket"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9ec040dc-03ff-46fe-9dad-3b240346a013)

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/648b3d6b-6780-4a45-bfdd-ef39771521a5)

<h3>Restart ISS again</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9402fcc2-663a-4b42-8cca-67b88b452d56)

<h3>In ISS, go to Sites -> Default Web Site, and select osTicket. </h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/89124610-bbeb-410f-a104-20157d50a4df)

<h3>Click "Browse *:80(http)"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/814431bc-c66b-4463-a296-fe43d585e191)

<h3>If everything is working you should see this:</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/70ca63f8-75d3-4db2-8c8a-68c2b13f9cd6)


<h3>go back to PHP Manager in ISS and click Enable or disable an extension</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/91a44b73-edfd-48fd-ad99-de2dfb4b2b31)

<h3>Enable: php_imap.dll <br/>
Enable: php_intl.dll <br/>
Enable: php_opcache.dll <br/></h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/25d279be-4fcf-43b4-8c06-ed11ee7e0c5d)

<h3>Refresh the osTicket website and you will see someof the red X go away</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/e6173ff8-c2ee-40b1-97b0-1c413600eeb7)

<h3>go to "ost-sampleconfig.php" and rename it to "ost-config.php"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/8d80187d-12bd-4ceb-814c-e3abdb4e8ebc)

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/cc225e3f-07ba-47ea-ad06-3bb3d434c662)

<h3>right click "ost-config.php" and go to properties --> Security --> Advanced --> Disable Inheritance --> Remove all Inherited Permissions from this object.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/526b9eb3-4ed7-45a3-896a-ed6b2825041d)

<h3>Click Add</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/f9e06433-5f22-435f-b0c0-acdf706e9a3f)

<h3>select a principal and type "Everyone" in the box</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/8dbbb463-9282-4d8e-861e-7d63191e8f27)

<h3>Check full control</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/61310230-c628-429c-b710-0bcf72f29356)

<h3>click Ok --> "Apply" and "Ok"</h3>

<h3>go back to the osTicket browser and click "Continue". Choose a Helpdesk Name and a Default Email(it does not have to be an actual Email). The default email can't be the same as the email in the admin section</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/ca40bc8f-eb61-42d1-801f-6b3a84171979)


<h3>go to the "Admin" section and setup everything. The email will be used to login.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/39aaedc8-e4f2-40c4-a857-97ae1f30286c)

<h3>Download the seventh link and go through the setup.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/5230586a-b330-45d3-9228-ea660c546812)

<br/>
<h3>click "New" and type the password for the root that was setup earlier.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/cfbc7667-37f9-4ae9-b7b7-ffdec0c25238)

<h3>After typing in the password click "open"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/ff066650-5084-4a30-b07b-0d8f7efc3d1b)


<h3>Go to the osTicket website and in the "Database Settings" and enter "root" for the username and the password for the root.</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/eac0f000-3a07-4c6c-99af-ffab05afbc94)

<h3>Right click "Unnamed" and select "create new" and select "Database"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/db176aaa-5af4-4574-9fe4-9cfabb634cc4)

<h3>Type in "osTicket" and lick "Ok"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/700136e8-27a7-40ca-a36a-7f4da49b8d8f)

<h3>type in "osTicket" in MySQL Database on the osTicket website</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/18d07d03-10ce-43de-a166-d2927445eef3)

<h3>When you click Install it should look like this:</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/82ff339b-5366-49d1-b141-52fd69140fa2)

<h3>And to clean up everything, go to files and delete the "setup" file</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/49f8dd40-357d-4880-b67e-b97f71834956)

<h3>in the "ost.config.php", set the permission to "Read only" by right clicking it --> Properties --> Security --> Advanced</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/81a6721e-c3de-46d9-b5f5-c4533fd0b2cb)

<h3>select "Everyone" and click "Edit"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/3a0d30af-0ac5-430e-bcac-8e172740c5b1)

<h3>select "Read & execute" and "Read"</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/60d8ac21-c0bc-4839-9c8f-2a754c80fd2f)

 <h3>click "apply" and "close"</h3>

<h3>The 8th link is for admin login and the 9th is for end-users</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/3738adef-5b4c-4296-b210-21702f8fed0f)

<h3>and that is it for the osTicket installation</h3>

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/ed0ea8be-c243-4ea9-a5fe-a90017b541b3)


</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />

</p>
<p>

</p>
<br />
