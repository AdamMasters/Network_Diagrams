# Network_Diagrams
A browser-based network emulator for teaching computer networking concepts at GCSE and/or A Level courses. 

What it does
Networx lets you build virtual networks by dragging hardware components onto a canvas and connecting them with wired or wireless links. Once built, you can:

Run terminal commands on PCs, laptops, and servers — ping, traceroute, ipconfig, nslookup, curl, ssh, and more

Browse the web — a built‑in browser on PC/Laptop/Server nodes renders pages served by Web Server nodes, resolves hostnames via local DNS, and simulates internet access through a Cloud node

SSH between nodes — ssh <ip> opens a persistent session; all subsequent commands run on the remote device until you type exit

Assign IPs with DHCP — routers run a DHCP server; clients request leases with dhclient (Linux) or ipconfig /renew (Windows), animating the full four‑way handshake

Configure DNS records — DNS Server nodes hold A records that resolve hostnames across the network

Ping domain names — ping google.com resolves via DNS and routes through the internet node

Inspect switch MAC tables — tables populate as traffic flows, showing which MAC address was learned on which port

Configure routers — add static routing table entries

Set firewall rules — allow/deny by protocol, port, and IP

Configure wireless access points — SSID, WPA key, 2.4/5 GHz band

Load preset scenarios — five built‑in topologies covering key WJEC Digital Technology network topics

Save and share — export your network as a .json file and import it elsewhere

Preset scenarios
Scenario	WJEC‑relevant focus
Star Topology (LAN)	Switch MAC tables, LAN addressing, ping, basic topologies
Home Network	NAT, router, WAP, wired + wireless clients, basic security
School Network	Firewall rules, network segmentation, servers, access control
Client–Server Model	DNS resolution, HTTP, nslookup, curl, client–server architecture
Mesh / WAN Topology	Redundant paths, inter‑site routing, internet backbone, WAN concepts
You can treat these as ready‑made contexts for exploring WJEC network content such as hardware roles, protocols, IP addressing, and security.

Curriculum links
Networx is designed around the WJEC GCE Digital Technology specification, with direct relevance to network‑related content in:

AS Unit 1: Innovation in Digital Technology

2.1.1 Connected digital systems and smart devices

Network communication hardware (router, switch, WAP, etc.)

Protocols and standards (TCP/IP, Wi‑Fi, Ethernet)

LAN/WLAN/WAN concepts and transmission media

A2 Unit 3: Connected Systems

2.3.3 Digital technology networks

IP addressing, DHCP, DNS

Routing, firewalls, and basic network security

Client–server models and common application protocols

The simulator does not implement every detail in the specification, but it provides an interactive environment to visualise and experiment with the core networking ideas that learners are expected to understand and apply.

Specification:
WJEC GCE AS/A Level Digital Technology (teaching from 2022)

(Use the official WJEC specification and support materials for exact wording and assessment requirements.)
