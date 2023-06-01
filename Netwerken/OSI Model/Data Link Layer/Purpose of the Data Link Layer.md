Responsible for communications between end-device [[NIC|NICs]]
Allows upper layer protocols to access physical layer media
Encapsulates layer 3 packets into layer 2 frames
Performs error detection and rejects corrupt frames.

![[Pasted image 20230601193641.png]]

# Data Link Sublayers

Standards are specific to the type of network (Ethernet, WLAN, WPAN, etc.)
consists of two sublayers:
- Logical Link control (LLC)
	- communicates between networking software at upper layers and device hardware at lower layers 
- Media Access Control (MAC)
	- responsible for data encapsulation and media access control.

![[Pasted image 20230601193826.png]]

# Providing Access to Media

Packets may experience numerous data link layers and media transitions.

With each hop a router performs four Layer 2 functions:
- Accepts frame from medium
- De-encapsulates frame to expose packet
- Re-encapsulates packet into frame
- Forwards new frame on medium

# Data Link Layer Standards

Defined by engineering organizations:
- Institute for Electrical and Electronic Engineers (IEEE)
- International Telecommunications Union (ITU)
- International Organizations for Standardization (ISO)
- American National Standards Institute (ANSI)