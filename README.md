# office-network-design
Cisco Packet Tracer implementation of a ring-topology office network

# Office Network Design - Cisco Packet Tracer

## Project Description
Implementation of a functional office network with:
- 16 PCs across 4 office sections
- Hubs connected in ring topology
- Full inter-device communication
- Successful ping tests between all nodes

## Key Features
✔︎ Ring topology with 4 hubs  
✔︎ IP addressing scheme (192.168.1.0/24)  
✔︎ 100% successful ping rate  
✔︎ VLAN segmentation by department  

## Technologies Used
- Cisco Packet Tracer 8.2
- IPv4 addressing
- ICMP protocol

## Setup Instructions
1. Open `project_files/Office_Network.pkt` in Cisco Packet Tracer
2. To test connectivity:
   ```
   PC1> ping 192.168.1.16
   ```

## Testing Evidence
![Ping Test](images/ping_test.jpg)  
*Successful ping from PC1 to PC16*

## Commit History
- `Initial network setup - July 5`
- `Implemented ring topology - July 6`
- `Added VLAN configuration - July 7`
- `Updated documentation - July 8`
