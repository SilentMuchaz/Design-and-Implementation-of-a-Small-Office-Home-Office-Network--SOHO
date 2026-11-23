# SOHO Network — Design, Configuration & Validation Case Study

## Project overview

Designed and configured a Cisco Packet Tracer network for a fictional XYZ Company branch office in Rzeszów, Poland. The branch was intended to operate independently of headquarters and serve three internal departments using a single router, an access-layer switch, and wireless access infrastructure.

**Project type:** Simulated network implementation  
**Platform:** Cisco Packet Tracer  
**Base IPv4 network:** `192.168.1.0/24`  
**Departments:** Administration & IT; Finance & HR; Reception & Customer Service

## Design requirements

The documented requirements called for a separate VLAN for each department, automatic IPv4 assignment for hosts, wireless connectivity, and communication between the VLANs. The network was to use one Cisco router and one access-layer switch.

## Technical implementation

### Departmental segmentation

The design separates the three departments into distinct VLANs and includes switchport assignments. This provides logical separation at Layer 2 while retaining a shared access-layer switch.

![VLAN configuration](https://imgur.com/rcmFWY0.png)

### Inter-VLAN connectivity

Router-on-a-stick was selected to connect the departmental VLANs using the router and switch uplink. The project includes an inter-VLAN routing configuration screenshot.

![Inter-VLAN routing configuration](https://imgur.com/Ac3NZ5F.png)

### Addressing and DHCP

The project uses the assigned `192.168.1.0/24` network as the basis for subnetting and describes DHCP service on the router to automate host IPv4 assignment. Exact subnet ranges and actual lease outputs are not listed in the supplied README.

![Router DHCP configuration](https://imgur.com/Uj3kEOK.png)

### Wired and wireless clients

The topology incorporates a Cisco access-layer switch for wired endpoints and Cisco access-point connectivity for departmental wireless access.

![SOHO network topology](https://imgur.com/JHRqQ7R.png)

## Validation and results

The source documentation lists ping tests as the method used for connectivity verification. It also identifies the expected results: hosts receive addresses automatically and devices in different VLANs communicate through inter-VLAN routing.

| Check | Supporting project material | Evidence status |
| --- | --- | --- |
| VLAN creation / switchport assignments | VLAN screenshot | Configuration depicted; specific VLAN IDs not transcribed |
| Router-on-a-stick | Routing screenshot | Configuration depicted; live forwarding not independently tested here |
| DHCP | Router DHCP screenshot | Configuration depicted; actual client lease output not supplied |
| Wired / wireless design | Topology screenshot | Topology depicted; individual wireless association outputs not supplied |
| Cross-VLAN ping | Listed in README testing workflow | Ping output not supplied |

**Outcome:** A Packet Tracer network artifact and supporting configuration screenshots documenting the intended three-department SOHO implementation. The `.pkt` file is the primary artifact for checking device configurations and running additional connectivity tests.

## Technical skills demonstrated

- Cisco Packet Tracer topology design and network simulation
- VLAN segmentation and switchport assignment
- Router-on-a-stick inter-VLAN routing
- IPv4 subnetting and DHCP service configuration
- Wired and wireless LAN design
- Connectivity testing and network documentation

## Project files

- [Packet Tracer network](Small-Office-Home-Office-Network%20--%20SOHO.pkt)
- [Evidence links](evidence/README.md)
- [PDF case study](01-soho-network-case-study.pdf)

## Evidence limitations

The uploaded archive contains the Packet Tracer `.pkt` file and a README with four externally hosted screenshot links. It does not contain local screenshot files, router/switch running-config exports, DHCP lease logs, or captured ping output. The technical claims above follow the source README; screenshots and the `.pkt` configuration were not independently validated in this environment.
