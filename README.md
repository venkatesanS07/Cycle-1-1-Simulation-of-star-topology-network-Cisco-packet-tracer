# DATE
# EXPT. NO. 1 SIMULATION OF STAR TOPOLOGY NETWORK

# AIM 
 To simulate a network with Topology, using Cisco Packet Tracer and to verify the connectivity between computer using ICMP.
# EQUIPMENTS REQUIRED

Desktop computer
Cisco Packet Tracer 5.0 Software.

# PROCEDURE
* STEP 1: Open a Packet Tracer Software.
* STEP 2: Drag a 2950 Switch from tool bar and drop it in work area.
* STEP 3: Drag a PC Terminal from tool bar and drop it in work area.
* STEP 4: Repeat the Step:3 for four terminals.
* STEP 5: Select Copper straight-through cable from tool bar and connect each PC Terminal with 2950 switch in different ports.
* STEP 6: Click on the PC Terminal, Select the fast Ethernet Interface from configuration table and set IP address and Subnet mask.
* STEP 7: Repeat the Step:6 for all the PC Terminals.
* STEP 8: click on the PC Terminal and Select Terminal from the Desktop tab to verify the connectivity between the PC Terminals using Ping Command.
* STEP 9: Select “add simple PDU” from tool bar and place it in source and destination PC Terminals to verify the connectivity





# IP CONNECTIVITY TABLE
<img width="979" height="228" alt="image" src="https://github.com/user-attachments/assets/051001ec-2e44-41aa-af2e-3d5deea4a3a1" />
# NETWORK DIAGRAM
<img width="1280" height="717" alt="image" src="https://github.com/user-attachments/assets/6bfc4c9e-a9c3-4bfd-bf0e-dd9be525c122" />

# BASIC NETWORKING COMMANDS
```
IP Configuration Details:
(i) ipconfig Command(windows OS) (or) ifconfig command(Linux OS) Syntax:
C:\> ipconfig
(ii) ipconfig/all Command:
Syntax:
C:\> ipconfig /all Testing
Connectivity:
(i) Self Ping Command:
Syntax:
c:\> ping <ipaddress> Example:
C:\> ping 172.17.80.201
C:\> ping 127.0.0.1 (ii)
Ping to Destination
Syntax:
c:\> ping <destination-ipaddress> Example:
C:\ping 172.17.80.1
To Display IP to Physical address Translation Table and trace the route
i) Arp Command Syntax:
10
C:\arp –a
(ii)To trace the route Syntax:
C:\tracert <ipaddress (or) specific address> Example:
C:\tracert 172.17.80.1
C:\tracert www.saveetha.ac.in
```
# OUTPUT
![WhatsApp Image 2026-03-21 at 11 40 51 AM](https://github.com/user-attachments/assets/f481aa54-b357-4102-a6d9-4b3a22cc48e1)


# RESULT

Thus the computers in same network are able to communicate with each other and the communication between them were verified.
