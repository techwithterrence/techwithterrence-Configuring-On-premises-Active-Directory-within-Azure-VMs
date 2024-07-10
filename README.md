# Configuring-On-premises-Active-Directory-within-Azure-VMs

![ws-2016-ad-ds-console-active-directory-users-and-computers](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/24855568-ee52-49fc-a82b-569f5f93d26e)

<h1>Project Scope - Using Active Directory w/Azure</h1>
This tutorial outlines the way a computer user can utilize Active Directory inside of the 
Microsoft Azure cloud enviornment.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Watch Professor Messer's Active Directory Overview ](https://youtu.be/VLWt0-8BOV4?si=cbRf0qVTuvaHEolI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Active Directory Users and Computers

<h2>Operating Systems Used </h2>

- Domain Controller - Windows Server 2022  </b> (21H2)
- Client-1 - Windows 10 

<h2>Lets Begin </h2>

<p>
    To begin the tutorial, it's a good idea to set up 2 virtual machines in Azure.  Its important to name these two virtual machines DC-1(Domain Controller) and name the other Client-1.  Client 1 vm needs to be on the same virtual network as DC-1 machine.
</p>
<br />

![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/71ec7bc6-2053-496f-a976-887fab93236d)


                                          </h1> *Note - Be sure to set Client-1 Vm to DC-1 Virtual Network. </h1> 

                                                
![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/4ce8d167-f80e-490f-a2cd-ce785b1b6ee8)
![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/cda88a10-1c3c-46d3-9e90-2cc29ffe17d8)


<p>
    Now log into Client-1 Virtual Machine to test connectivity to the Domain Controller DC-1.  To do this, simply remote desktop into Client-1 and ping the domain 
  controller from the command prompt using ping command.  After running the command the DC controller times out.  Therefore you will need to change the firewall ICMP settings in Domain controller to allow ICMP traffic through the firewall.
</p>
<br />


![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/17624636-a5c4-4664-b3d8-2640be9f93b9)
![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/b0634dc9-9ed6-4834-9b9d-f24b5518f745)


                                    AFTER FIREWALL SETTINGS CHANGED ON DC-1, PING IS WORKING NOW



![image](https://github.com/techwithterrence/Configuring-On-premises-Active-Directory-within-Azure-VMs/assets/174138674/b3c34825-c014-43e3-9017-62c02e336d5d)

</p>
                               

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
