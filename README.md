# Design-and-Implementation-of-a-Small-Office-Home-Office-Network--SOHO


<h2>Overview</h2>
XYZ Company is expanding its operations by establishing a small branch office in Rzeszów, Poland. 
The branch network will operate independently from the headquarters and must support three internal departments with reliable wired and wireless connectivity. 
As the network engineer, the task is to design, configure, and verify a functional network in accordance with the provided specifications.
<br />


<h2>Network Requirements</h2>

Cisco-based network using:

 - 1 Router
 - 1 Access Layer Switch

Three departments must be implemented:
- Administration & IT
 - Finance & HR
 - Reception & Customer Service
  
/////////////////////////////////////////////////////////////////////////////////////
- Each department is assigned to a unique VLAN *
- Wireless network access is provided for each department
- All host devices must receive IPv4 addresses automatically (DHCP)
- Devices in all VLANs must communicate across the network
- IPv4 base address assigned by ISP: 192.168.1.0/24


<h2>Technologies and Configurations</h2>

- Basic enterprise LAN design using a Router and a Switch
- Proper cabling and device connectivity setup
- VLAN creation and switchport assignments
- Subnetting and structured IP addressing plan
- Inter-VLAN routing using Router-on-a-Stick
- DHCP service configuration on the router
- Wireless LAN configuration via Cisco Access Point
- End device setup and interface configuration
- Network testing and connectivity verification (ping tests)

<h2>Screenshot:</h2>
<br/>
Network Topology
<img src="https://imgur.com/JHRqQ7R.png" width="50%"/>

<br/>
DHCP Configuration
<img src="https://imgur.com/Uj3kEOK.png" width="50%"/>

<br/>
Inter-VLAN routing
<img src="https://imgur.com/Ac3NZ5F.png" width="50%"/>

<br/>
VLAN
<img src="https://imgur.com/rcmFWY0.png" width="50%"/>
