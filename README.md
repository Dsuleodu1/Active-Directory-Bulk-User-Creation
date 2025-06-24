![](https://www.baeldung.com/wp-content/uploads/sites/4/2023/04/Password-Cracking.png)

# Active-Directory-Bulk-User-Creation

An Active Directory home lab using Oracle VirtualBox on our personal computer to then also add 1000+ users using PowerShell script. Created a simple Windows network environment by dowloading two ISO files, a Windows 10 and a Server 2019 file which will be our operating systems for our two virtual machines. Our first virtual machine will be our Domain Controller which will house active directory and will get two network adaptors one external and the other will be private for the clients to connect to. We then create our domain and configure NAT/Routing for clients to reach Domain Controller. Next we set up a DHCP on the domain controller so our second virtual machine can automatically get an IP address. Lastly we use PowerShell script to create 1000+ users and then we finally make our second virtual machine which is connected to our private network. After creating this virtual machine we will join it to the domain then log into it with one of our domain accounts we created earlier.
![](https://github.com/Dsuleodu1/Azure-Soc-Lab/blob/main/Screenshot%202025-06-11%20093403.png)

## Features

- Created with Microsoft Azure Sentinel (SIEM) log analytics.
- Provides Knowledge of KQL, PowerShell scripting, remote desktop protocol and virtual machines.
- No installation necessary just create azure free account ![]().
- Gives you hands on experience dropping firewall rules and creating new users to RDP into.
- Allows you to visualize 24hrs of cyber attacks with precise insights on attackers information.
- Works on Mac, Linux and Windows

### Output

![](https://github.com/Dsuleodu1/Azure-Soc-Lab/blob/main/Screenshot%202025-06-11%20093936.png)

> This is the completed visualization of our Microsft Sentinel Log analysis map after 24 hours of monitoring our system. As you can see this visualization presents various locations around the world where our attackers geoIp were found based on our log analytics. Using our PowerShell script we comprised we were able to automate a task in (KQL) Kusto Query Language allowing us to filter out our log analytics to key in on specifications like; time generated, computer, attackerIp, Ipaddres, city name, country name, latitude, and longitude. 

## Tools
- Azure Sentinel, KQL, Virtual Machines, Remote desktop protocol, PowerShell, Windows Event logs
