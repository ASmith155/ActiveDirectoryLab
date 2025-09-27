<h1>ActiveDirectoryHomeLab</h1>



<h2>Description</h2>
In this project im going to walk through how to create an Active Directory home lab Environment using Oracle Virtual Box. Configuring and running this lab developed and strengthened my understanding of how active directory and windows networking works.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>OracleVM</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>
<h2>Program walk-through:</h2>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <p>The first thing I did was download and install Oracle VirtualBox. This is what I will use to run my virtual machines. The second thing I did was download and install Windows 10 ISO and Server 2019 ISO, which I used to install the two operating systems on two different virtual machines.

After installing everything, I created my first virtual machine, which is going to house the Active Directory and serve as my Domain Controller. I gave this machine two network adapters: one to connect to the external internet, while the other was used to connect to the VirtualBox private network for the clients.

Once the virtual machines were created, I installed Server 2019 and then assigned IP addresses for the internal network. The external network automatically received internet from my home network.

I then named the server, installed Active Directory, and created a domain.

Next, I configured NAT and routing so that clients on the private network could access the internet through the Domain Controller.

I then set up DHCP on the Domain Controller so that when I created my Windows 10 machine, it automatically received an IP address. The last thing I did on the Domain Controller before creating the client virtual machine was run a PowerShell script that automatically created a thousand users in Active Directory.

After creating the users, I created another virtual machine and installed Windows 10 on it. This virtual machine was connected to the private VirtualBox network. I named the machine Client 1 and joined it to the domain. Then, I logged into it using one of the domain accounts.

After setting up this homelab, I now have a Windows networking environment with Active Directory and several networking services..</p>

  



<h2>My Image</h2>
    <img src="https://i.imgur.com/U4tNDoC.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>



<h2>My Image</h2>
    <img src="https://i.imgur.com/To1pmsu.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


 <h2>My Image</h2>
    <img src="https://i.imgur.com/oerqtKb.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


<h2>My Image</h2>
    <img src="https://i.imgur.com/bYb8dY7.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>



<h2>My Image</h2>
    <img src="https://i.imgur.com/wrlBm9T.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>



<h2>My Image</h2>
    <img src="https://i.imgur.com/DmQFvHx.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


<h2>My Image</h2>
    <img src="https://i.imgur.com/UYh7BOH.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


<h2>My Image</h2>
    <img src="https://i.imgur.com/FV8VGAR.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


<h2>My Image</h2>
    <img src="https://i.imgur.com/CJlVyJm.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>



<h2>My Image</h2>
    <img src="https://i.imgur.com/UdF2JSG.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>


<h2>My Image</h2>
    <img src="https://i.imgur.com/3dSJkvZ.jpeg" alt="Image" style="max-width:100%; height:auto;">
</body>
</html>
