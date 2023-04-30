# VPN
This tutorial outlines the process of setting up a VPN using Proton VPN.<br />
<p align="center">
<img src="https://i.imgur.com/1hAdqUZ.png"/>
</p>

<h1>VPN Setup and Usage




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

For this project, I created a virtual machine via Microsoft Azure using Windows 10 as the operating system. I setup the location of my virtual machine in Brazil for the sake of this project. 

<p>
<img src="https://i.imgur.com/Hu5vQ2S.png")"/>                                            
</p>
<p>
First, I went to www.whatismyipaddress.com to compare the IP address after I setup the VPN to check if the setup was a success.

</p>
<br />
<p>
<img src="https://i.imgur.com/owW8VEo.png")"/>  
</p>
<p>
Since our virtual machine is in another language, we will create an account at www.protonvpn.com in our own machine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/vrU1uFr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating an account, we will get to the download page, copy the URL, and paste the URL into the browser of our virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/nfQ2YNc.png" 
</p>
<p>
Once we login and download Proton VPN, we should be in this page above. We will try to connect to a server in Japan by clicking on "connect" on the "Japan" line.
</p>
<br />

<p>
<img src="https://i.imgur.com/o2iWRbP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
While our virtual machine is connecting to the Japanese sever, our RDP connection might drop while it's establishing a connection with a server in Japan. This will only happen for a brief moment. Once we get our connection back, our Proton VPN will look like this to let us know that we are connected.
</p>
<br />

<p>
<img src="https://i.imgur.com/AbingiA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we connect, we can go back to www.whatismyipaddress.com and compare the location and address number to the one that was previously shown.

</p>
<br />

<p>
<img src="https://i.imgur.com/4uZHq8k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Our final VPN mapping should look like this.
