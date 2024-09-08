# Fintech Network - Cisco Packet Tracer Project

## Project Overview
This project simulates a comprehensive network infrastructure for a fintech company using Cisco Packet Tracer. The network is designed with a focus on security, performance, redundancy, and scalability.

## Prerequisites
- Cisco Packet Tracer (version 8.0 or later recommended)

## Opening the Project
1. Launch Cisco Packet Tracer
2. File > Open
3. Navigate to the project file: `FintechNetwork.pkt`
4. Click Open

## Network Topology
The network consists of:
- Multiple departments, each with its own VLAN
- Core layer with multilayer switches
- Distribution layer with redundant connections
- Access layer switches for each department
- Wireless access points for each department
- Voice over IP (VoIP) implementation
- Server farm with DHCP and other services
- Dual ISP connections for redundancy

## Key Configurations
1. VLANs: Separate VLANs for each department and voice traffic
2. Inter-VLAN Routing: Implemented on multilayer switches
3. DHCP: Server configured for dynamic IP assignment
4. VoIP: Cisco 2811 router configured for telephony services
5. Wireless: Each department has WiFi access
6. Routing: OSPF protocol implemented
7. Security:
   - Port security on switches
   - SSH for remote administration
   - ACLs for access control
   - NAT/PAT for internet access
8. VPN: Site-to-site IPsec VPN between HQ and server site

## IP Addressing Scheme
- Data Network: 192.168.20.0/24
- Voice Network: 10.10.10.0/24
- Public Addresses: 190.200.100.0/24

## Simulation Exercises
1. Test inter-VLAN communication
2. Verify VoIP calls between departments
3. Check wireless client connectivity
4. Simulate internet access and verify NAT functionality
5. Test VPN connectivity between sites
6. Verify DHCP assignment for client devices

## Troubleshooting
If devices can't communicate:
1. Check physical connections
2. Verify IP addressing and VLAN assignments
3. Ensure routing is properly configured
4. Check ACL configurations

## Note
This is a simulated environment. Some advanced features of physical Cisco devices may not be fully represented in Packet Tracer.
