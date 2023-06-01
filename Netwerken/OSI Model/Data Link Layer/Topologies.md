# Physical and Logical Topologies

The topology of a network is the arrangement and relationship of the network devices and interconnections between them

This is described in [[Network Representations and Topologies]]

# WAN Topologies

Three common physical WAN topologies:
- Point-to-Point - simplest and most common. Permanent link between endpoints.
- Hub and spoke - similar to star topology where central site interconnects branch sites through point-to-point links.
- Mesh - provides high availability but requires every end system to be connected

## Point-to-Point WAN Topology

Physical directly connects two nodes
Nodes may not share media with other hosts.
WAN Protocols can be very simple

![[Pasted image 20230601194626.png]]

# LAN Topologies

Typically interconnected using a star or extended star topology.
Star and extended star topologies are easy to install, very scalable and easy to troubleshoot.

Early technologies provide two additional topologies:
- Bus - All end systems chained together and terminated on each end
- Ring - Each end system connected to its respective neighbours to form a ring

![[Pasted image 20230601205440.png]]

# Half and Full Duplex Communication

Half-duplex communication
- Only allows one device to send or receive at a time on a shared medium
- Used on [[Wireless Media#Wireless LAN|WLAN]]s and legacy bus topologies with Ethernet hubs. 

Full-duplex communication
- Allows both devices to simultaneously transmit and receive on a shared medium
- Ethernet switches operate in full-duplex mode

# Access Control Methods

Contention-based access
All nodes operating in half-duplex, examples:
- Carrier sense multiple access with collision detection (CSMA/CD)
- Carrier sense multiple access with collision avoidance (CSMA/CA)

Controlled access
- Deterministic access where each nodes has own time on medium
- Used on legacy networks

## Contention-Based Access - CSMA/CD

CSMA/CD
- used by legacy Ethernet LANs
- Operates in half-duplex
- Uses collision detection process

CSMA/CD collision detection process:
- Devices transmitting simultaneously will result in collision
- Devices detect collision
- Devices wait random period of time before retransmit of data

## Contention-Based Access - CSMA/CA
CSMA/CA
- Operates in half-duplex
- Uses a collision avoidance process

CSMA/CA collision avoidance process:
- Devices include time duration needed for transmission
- Other devices receive this duration and know how long medium is unavailable
