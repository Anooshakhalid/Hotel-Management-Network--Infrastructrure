# Hotel-Management-Network
 Project for Computer Communication Course (CS-327) #fifth Semester

A structured network designed for a three-floor hotel to ensure efficient connectivity, scalability, and performance. The project incorporates OSPF routing for dynamic path selection,VLAN, Subnetting and NAT for internet access.
Architecture:
 ![Screenshot 2024-12-17 194048](https://github.com/user-attachments/assets/1d2d1cf1-31d2-4414-ba38-7c90a3a63416)


-----
🛠️ Features
-Three Subnet Divisions:
Each floor has a dedicated VLAN for better management.

-OSPF Routing Protocol:
Dynamic routing with cost-based metrics for optimal performance.

-NAT Implementation:
Seamless internet access for private IPs.

-Scalability:
Ready to integrate future expansions or devices.

------
🌐 Network Highlights
IP Addressing: 

**First floor: (Network 192.168.1.0/26)** 
-Reception Dept: 192.168.1.0/26   (Subnet 0) 
-Store Dept: 192.168.1.64/26   (Subnet 1) 
-Logistics Dept: 192.168.1.128/26   (Subnet 2) 
-192.168.1.192/26  (Subnet 3) is for the future implementation.  

**Second floor: (Network 192.168.2.0/26)** 
-Sales & Marketing Dept: 192.168.2.0/26   (Subnet 0) 
-Human Resources Dept: 192.168.2.64/26   (Subnet 1) 
-Finance Dept: 192.168.1.128/26   (Subnet 2) 
-192.168.2.192/26  (Subnet 3) is for the future implementation.  

**Third floor: : (Network 192.168.1.0/25)** 
-IT Dept: 192.168.3.0/25   (Subnet 0) 
-Admin Dept: 192.168.3.128/25   (Subnet 1) 


-Public Ips: 
200.100.50.0/30 

-Web Server: 
8.8.8.0/24

Hardware:
Cisco 2911 Routers
Layer 2/3 Switches
End Devices (PCs, Servers, Printers).



