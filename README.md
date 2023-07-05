<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS(Internet Information Services)
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/97996bcc-4910-4c5b-842a-5351e5d8adee)

</p>
<p>After running the VM(virtual machine), go to Control Panel inside the VM -> Programs -> Turn Windows features on or off, and check "Internet Information Services" box.
</p>
<br />

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/126eedfb-8008-4a8f-bec8-a503d6a0f14b)

<p>

</p>
<p>
Under "Internet Information Services", Check the "World Wide Web Services" box then click ok.
</p>
<br />

<p>

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/ad1b6936-45f6-454b-82e8-3ec86eb9b013)
<br/>
</p>
<p>
Under "Common HTTP features", Check all the boxes inside it.

 
 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/5c59f4b9-9aef-4d6f-a031-4aee6a730d38)
 
Check CGI under Application Development Features
</p>
<br />

<p>


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/3f9f5520-9bf6-4b0b-a6e1-ccf1aa99385b)


</p>

<p>
 <br/>
To check if ISS is working, Go to a search engine and type "127.0.0.1" and you should have a web that looks like this.
</p>
<br />


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/398cc3bb-6ff0-403c-b100-8846f51e4ca5)

<p>
Create a new folder named "PHP"

</p>
<p>
 
 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/f43ef26d-7dc6-4d0b-bdcd-c8c3786b571d)

Go to this <a href="https://docs.google.com/document/d/1zauJKAndmBDyZ0eXRvAOSF9e0xWSQmLket6CgvUPITc/edit">link</a> and you will see downloadable links
</p>
<br />

</p>
<p>

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/c534f7f6-5535-4dc9-9083-aa996b96e99e)
 


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/7a2a955f-958b-4c7a-875f-6e185e62170c)

Download the first link and click "Download anyway"


![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a7762efb-fa8f-4dbe-a307-84b3dda8e1b8)


Open file, and go through the setup. Download the second link, same way as the first link. Go through the setup. For the third download, after the download, take all the contents and put it inside the PHP folder that was created.

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/03f5e7ac-f889-47ba-b50d-be9de9ba3968) 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/b85372fd-b096-4fee-83b1-e9803bcb1f43)

 Download the fourth and the fith link. For the fifth choose a typical install

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/33aedb94-f02c-4cb9-ba92-dfdc97adddc7)
standard config.
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/d6664479-a427-48b9-99d9-6924475edf46)



![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/d12a0038-f491-466b-9ed4-bc55b3fc2018)

 ![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a06893d7-2450-4711-bb16-11c9b6f66e7a)

 Setup your password.

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/7bf2b25f-62d0-4025-b7ba-4b1eeac80fcc)

open Internet Information Service Manager

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/5d144664-e818-417b-8a1b-3d360e092cc4)

Double click PHP manager

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/69753cd8-249a-4442-8963-a9d26e7d47c8)

select the "php-cgi" under the PHP folder as the path and click "ok"

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/69c03e55-01fa-4d59-b44f-bbaf82a9b99e)
hit the "home" icon
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/a679600a-a307-4ba3-adcd-3d34359921ae)

 click "Restart"
 
![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9402fcc2-663a-4b42-8cca-67b88b452d56)

Download the sixth link 

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/4bf5e296-01bb-4436-b077-31e21b9a64a2)

open the folder and extract the "upload" folder to wwwroot under inetpub 

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/fb2cb808-1372-43e3-babe-091b079ad726)

rename the "upload" folder to **EXACTLY** "osTicket"

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9ec040dc-03ff-46fe-9dad-3b240346a013)

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/648b3d6b-6780-4a45-bfdd-ef39771521a5)

Restart ISS again

![image](https://github.com/David123890dd/osticket-prereqs/assets/138183500/9402fcc2-663a-4b42-8cca-67b88b452d56)

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
