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

- Enable Internet Information Systems / IIS
- Install Web Platform Installer
- Install MySQL / Setup username and password
- Install C++ Redistributable
- Configure permissions and install OS ticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/1z7mofI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create an Azure Virtual Machine with the appropriate credentials and log into Remote Desktop
</p>
<br />

<p>
<img src="https://i.imgur.com/t3D87iN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
  >
</p>
<p>
Using the osticket virtual machine you can download the files needed for the installation of osTicket and then unzip them onto your desktop. As a general rule, the folder should be named "osTicket-Installation-Files". Within World Wide Web Services and Application Development Features, install and enable IIS (Internet Information Systems) with CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/FYi1Dbj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can find and download the following files within the "osTicket-Installation-Files" folder: PHP Manager, Rewrite Module, and then you need to create the directory C:/PHP in order to unzip PHP 7.3.8 into it. Please continue downloading from the folder: VC_redist and MySQL 5.5.62. Once the setup is complete, create a username and password on the system. .
</p>
<br />
