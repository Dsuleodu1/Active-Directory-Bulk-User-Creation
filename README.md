![](https://ecostruxure-building-help.se.com/graphics/en-US/graphics23401.png)

# Active-Directory-Bulk-User-Creation

An Active Directory home lab using Oracle VirtualBox on our personal computer to then also add 1000+ users using PowerShell script. Created a simple Windows network environment by dowloading two ISO files, a Windows 10 and a Server 2019 file which will be our operating systems for our two virtual machines. Our first virtual machine will be our Domain Controller which will house active directory and will get two network adaptors one external and the other will be private for the clients to connect to. We then create our domain and configure NAT/Routing for clients to reach Domain Controller. Next we set up a DHCP on the domain controller so our second virtual machine can automatically get an IP address. Lastly we use PowerShell script to create 1000+ users and then we finally make our second virtual machine which is connected to our private network. After creating this virtual machine we will join it to the domain then log into it with one of our domain accounts we created earlier.
![](https://github.com/Dsuleodu1/Active-Directory-Bulk-User-Creation/blob/main/Screenshot%202025-06-11%20160954.png)

## Features

- Created with Oracle VirtualBox, ISO Microsoft 10, Server 2019 files, PowerShell, Active Directory
- Provides Knowledge of basic networking infrastructure, PowerShell scripting, virtual machines and AD!
- No installation necessary just dowload VirtualBox and 2019/2010 ISO files. ![]().
- Gives you hands on experience of VM infrastructure scaliing, DHCP, NAT/ROUTING, creating domain accounts.
- Allows you to scale VM infrastructure, create user persmissions, and use PowerShell to create various       User/Passwords.
- Works on Mac, Linux and Windows

### Output

![](https://github.com/Dsuleodu1/Active-Directory-Bulk-User-Creation/blob/main/Screenshot%202025-06-11%20162543.png)

> This is the completed output of the Active Directory lab, as you can see after using our PowerShell script we were able to create various users that total up to 1000+. Each of these users can be found in our virtual machines domain and have their own username and password. We also created our very own Admin account using our own name for which we personally already logged onto the virtual machine. Also as you can see you can see you can you certain commands to query certain indiduals first or last names to retrieve their information. Each virtual machine was scaled up to standard and various users could log in and out without any problems. 

## Tools
- Active Directory, PowerShell, NAT/Routing, DHCP, Virtual Machines, Load Balancing
