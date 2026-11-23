# SOHO Network — Evidence Index

The project README includes four screenshots hosted on Imgur. The uploaded repository archive did **not** contain the image files themselves, so this folder links to the existing images rather than presenting fabricated or reconstructed screenshots.

| Screenshot | What it illustrates | Original link |
| --- | --- | --- |
| Network topology | Router, switch, departmental devices and wireless design | [View topology](https://imgur.com/JHRqQ7R.png) |
| VLAN configuration | Departmental VLAN and switch configuration | [View VLAN screenshot](https://imgur.com/rcmFWY0.png) |
| Inter-VLAN routing | Router-on-a-stick configuration | [View routing screenshot](https://imgur.com/Ac3NZ5F.png) |
| DHCP configuration | Router-based automatic IPv4 addressing | [View DHCP screenshot](https://imgur.com/Uj3kEOK.png) |

The editable **[Cisco Packet Tracer file](../Small-Office-Home-Office-Network%20--%20SOHO.pkt)** is the primary project artifact.

To make the repository fully self-contained, export the four original screenshots from Cisco Packet Tracer and add them to this folder. The README can then use `evidence/...` paths instead of external image URLs. Actual client DHCP leases, `show vlan brief`, `show ip interface brief`, and ping output would strengthen the evidence further, if available.
