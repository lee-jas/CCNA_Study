
## Key Topics
Figure 2-3 Drawing of a typical wired and wireless enterprise LAN 40
Table 2-2 Several types of Ethernet LANs and some details about each 41
Figure 2-9 Conceptual drawing of transmitting in one direction each over
two different electrical circuits between two Ethernet nodes
47
Figure 2-10 10- and 100-Mbps Ethernet straight-through cable pinouts 47
Figure 2-11 10- and 100-Mbps Ethernet crossover cable pinouts 48
Table 2-3 List of devices that transmit on wire pair 1,2 and pair 3,6 48
Figure 2-12 Typical uses for straight-through and crossover Ethernet cables 49
Figure 2-15 Physical transmission concepts in a multimode cable 51
Table 2-5 Comparison between UTP, MM, and SM Ethernet cabling 53
Figure 2-19 Format of Ethernet MAC addresses 55
List Definitions of half duplex and full duplex 58
Figure 2-23 Examples of which interfaces use full duplex and which interfaces use half duplex 59
## Notes
- Ethernet Local-Area Networks (LAN) are often referred to as wired LANs
	- Wireless LANs
- LANs need an Ethernet LAN switch
- LANs uses Ethernet cables
- Devices using UTP cabling transmit data over electrical circuits via copper wires inside
- Fiber-optic cabling allows Ethernet nodes to send light over glass fibers in the center of the cable
- The Ethernet data-link protocols focus on sending an Ethernet frame from source to destination Ethernet node.
	- Nodes build and forward frames
- The three most commonly used Ethernet standards are 10BASE-T (Ethernet), 100BASE-T (Fast Ethernet), and 1000BASE-T (Gigabit Ethernet)
- When electrical current passes over any wire it creates electromagnetic interference (EMI)
- Ethernet link refers to any physical cable between two Ethernet nodes
- RJ-45 connector has eight physical locations into which the eight wires in the cable can be inserted, called pins
- To complete the physical link, the nodes each need an RJ-45 Ethernet port that matches the RJ-45 connectors on the cable so that the connectors on the ends of the cable can connect to each
	- Often included as part of a network interface card (NIC)
- Cisco switches include some physical ports whose port hardware (the transceiver) can be changed later
- An Ethernet straight-through cable connects the wire at pin 1 on one end of the cable to pin 1 at the other end of the cable; the wire at pin 2 needs to connect to pin 2 on the other end of the cable; pin 3 on one end connects to pin 3 on the other and so on
	- if the endpoints transmit on different pin pairs
- The crossover cable pinout crosses the pair at the transmit pins on each device to the receive pins on the opposite device
	- If the endpoints transmit on the same pin pair
- Auto-MDIC allows sites to use straight-through pinouts on all cables.
- A fiber-optic cable holds the fiber in the middle of the cable, allowing the light to pass through the glass
	- Cladding
	- Core
	- Multimode fiber allows for multiple angles (modes) of light waves entering the core
	- Single-mode fiber transmit light into a much smaller core, a laser-based transmitter sends light at a single angle
- Ethernet addresses or Media Access Control (MAC) addresses, represent a single NIC or other Ethernet port
	- 6 byte, 48 bit
	- unicast address represents a single LAN interface
	- Ethernet devices a assigned a unique 3 byte code (OUI)
- broadcast address means all devices that reside on this LAN right now
- Ethernet Frame Check Sequence (FCS) the only field in the Ethernet trailer gives the receiving node a way to compare results with the sender to discover whether errors occurred in the frame
- NOdes that use half-duplex logic actually use a relatively well-known algorithm called carrier sense multiple access with collision detection (CSMA/CD)



## Diagrams / Topologies
![[Pasted image 20241027125007.png]]

![[Pasted image 20241027125330.png]]

![[Pasted image 20241027132438.png]]

![[Pasted image 20241027131509.png]]

![[Pasted image 20241027131520.png]]

![[Pasted image 20241027131851.png]]

![[Pasted image 20241027131902.png]]

![[Pasted image 20241027131941.png]]

![[Pasted image 20241027132246.png]]

![[Pasted image 20241027132457.png]]

![[Pasted image 20241027133039.png]]

![[Pasted image 20241027133950.png]]

![[Pasted image 20241027134839.png]]





---
#GBIC #SFP #10BASE-T #100BASE-T #1000BASE-T #Crossover-cable #EMI #Ethernet #Fiber-optic #FCS #IEEE #MAC-address #RJ-45 #Stright-trough-cable #LAN #wired-LAN #wireless-LAN
