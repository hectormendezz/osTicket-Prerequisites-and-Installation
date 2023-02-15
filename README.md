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

- Microsoft Azure subscription
- Microsoft Remote Desktop application
- osTicket installation files

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/gGPecTA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we open up our Azure subscription and start off by creating our resource group (RG), this works as a file to store all of our resources on Azure. You want to call it "osTicket" since this is the project we are doing, make sure to keep note of the location you set this resource group in because it is important for later.
</p>
<br />

<p>
<img src="https://i.imgur.com/WvDZIiV.png" height="80%" width="80%" 
</p>
<p>
Now we will create our virtual machine (VM), this will allow us to use a fabricated computer within your own computer. I named my VM, "VMosTicket", this also requires you to create a username and password. I kept my username simple with "LabUser" and password "Password1". This is being created within the same RG (osTicket) you created before in step 1. Now locate the virtual machine's IP address for the next step.
</p>
<br />

<p>
<img src="https://i.imgur.com/dmr7d8i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you are on this page, you can see the IP address on the bottom right corner of the picture. Your IP address might look a little different but don't worry, all of them are different. Copy that address and open up Microsoft Remote Desktop, this will allow us to actually use our VM, select create new pc and paste your IP address into the space it gives you. Then Remote Desktop will ask you to login to the VM, this is the same username and password that you created when you made the virtual machine. 
</p>
<br />

[<p>
<img src="https://i.imgur.com/osTPi7F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you should be looking at a Windows desktop, here you will download Internet Information Services (IIS). This is a Microsoft web server used to exchange static and dynamic web content with internet users. IIS can be used to host, deploy, and manage web applications using technologies such as ASP.NET and PHP.
When you have it download follow these steps in order, go to Start Menu > Windows Feature > Internet Information Services > World Wide Web Services > Application Development Features > CGI. We needed to enable these settings for the downloading of osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
