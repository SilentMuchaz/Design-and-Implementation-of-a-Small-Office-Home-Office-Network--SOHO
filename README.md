# SOHO Network Design & Implementation | Cisco Packet Tracer

Designed and configured a simulated **Small Office/Home Office (SOHO) branch network** for a fictional company with three departments: **Administration & IT**, **Finance & HR**, and **Reception & Customer Service**. The project uses a Cisco router and access-layer switch to provide departmental VLAN segmentation, inter-VLAN routing, router-based DHCP, and wired/wireless access.

## Project at a glance

| Area | Work documented |
| --- | --- |
| **Network design** | Branch-office topology with one router, one access-layer switch, and departmental wired/wireless clients |
| **Segmentation** | Separate VLAN for each of the three departments |
| **Routing** | Router-on-a-stick design for communication between VLANs |
| **Addressing** | Subnetting from the assigned `192.168.1.0/24` network |
| **Host configuration** | Router-based DHCP for automatic IPv4 assignment |
| **Wireless access** | Cisco access-point connectivity included in the design |
| **Validation** | Connectivity testing with ping is documented as part of the project workflow |

**Environment:** Cisco Packet Tracer · Cisco router · Cisco access-layer switch · Cisco access point · IPv4 · VLANs · 802.1Q inter-VLAN routing · DHCP

## Network topology

The branch was designed to operate independently from the headquarters while supporting three internal departments. Departmental VLANs provide logical separation, and the router provides the Layer 3 path between them.

![SOHO branch network topology](https://imgur.com/JHRqQ7R.png)

## Configuration work

### 1. Departmental VLAN segmentation

Created a logical network design in which Administration & IT, Finance & HR, and Reception & Customer Service each have a dedicated VLAN. The project includes switchport assignments for the departmental devices.

![VLAN configuration in Cisco Packet Tracer](https://imgur.com/rcmFWY0.png)

### 2. Router-on-a-stick inter-VLAN routing

Used a single router and switch uplink to support communication between the departmental VLANs through the router-on-a-stick approach.

![Inter-VLAN routing configuration](https://imgur.com/Ac3NZ5F.png)

### 3. IPv4 subnetting and DHCP

Worked from the assigned `192.168.1.0/24` address space and configured router-based DHCP for automatic client addressing. The screenshot documents the DHCP configuration in the Packet Tracer project.

![DHCP configuration](https://imgur.com/Uj3kEOK.png)

### 4. Wired and wireless connectivity

Included wired connections through the access-layer switch and wireless access through Cisco access-point infrastructure for the departmental users.

## Validation and outcome

The project documents a network design intended to provide **automatic IPv4 addressing** and **communication across the three VLANs**, with ping tests used for connectivity checks. The uploaded README does not include the actual ping output or a client lease table, so this summary does not claim a verified number of successful tests.

| Requirement | Implementation documented | Evidence available |
| --- | --- | --- |
| Three departmental VLANs | VLAN creation and switchport assignment | VLAN configuration screenshot |
| Inter-VLAN communication | Router-on-a-stick configuration | Routing screenshot |
| Automatic IPv4 addressing | Router DHCP configuration | DHCP screenshot |
| Wired/wireless users | Switch and access-point topology | Topology screenshot |
| End-to-end connectivity | Ping testing included in project workflow | Test outputs not included in supplied files |

## Project artifact

**[Open the Cisco Packet Tracer simulation](Small-Office-Home-Office-Network%20--%20SOHO.pkt)** to inspect the network and its device configurations in Cisco Packet Tracer.

A more detailed account of the implementation and evidence is available in the [SOHO Network Case Study](SOHO-Network-Case-Study.md).

## Scope

This is a **simulated branch-office network**, not a production deployment. The provided project materials document the network design and configuration areas above; exact VLAN IDs, per-VLAN subnet allocations, DHCP lease results, and successful ping counts should be confirmed directly in Packet Tracer before adding them as verified results.
