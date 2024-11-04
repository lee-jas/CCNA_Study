
## Key Topics
Figure 3-6 Router de-encapsulation and re-encapsulation 68 
Figure 3-7 Ethernet WAN—physical connections 69 
List Common terms to describe an Ethernet WAN link 70 
List Four-step process of how routers route (forward) packets 74 
Figure 3-11 IP Routing and Encapsulation 74 
List Two statements about how IP expects IP addresses to be grouped into networks or subnets 76 
List Three-step process of how routing protocols learn routes 77 
Figure 3-13 IP Routing Protocol Basic Process 78 
Figure 3-14 Example that shows the purpose and process of DNS name resolution 80 
Figure 3-15 Example of the purpose and process of ARP 81

## Notes
- Wide-Area Network (WAN)
- WAN tech defines L1 standard and L2 protocols used to communicate over long distances
- WAN links between two routers to connect LANs
- The leased line service is a L1 service that delivers bits in both directions at a predetermined speed using full-duplex logic
	- telco
- Different names for a leased line include leased circuit, serial link, point-to-point link, T1, WAN link, and private line
	- Serial link refers to the fact that the bits flow serially and that routers are serial interfaces
- Leased line provides a L1 service
	- To make use of it, routers on the ends of the line use one of two L2 protocols: High-Level Data Link Control (HDLC) or Point-to-Point Protocol (PPP)
- Forwarding IP packets
	- A leased line with DHLC creates a WAN link between two routers so that they can forward packets for devices on the attached LANs
- Ethernet WAN service/Ethernet WAN/Ethernet Line Service (E-Line)
	- logically, behaves like a point to point connection between two routers
	- physically, behaves as if a physical fiber Ethernet link existed between the two routers
- Routing protocols give routers a means by which to learn routers to all the IP subnets in an internetwork 
- The default router/default gateway is sent a packet and knows where to route the data
- Each router keeps an IP routing table which lists IP address groupings called IP networks and IP subnets
- Two foundational rules of subnetting
	- Two IP addresses not separated from each other by a router must be in the same group (subnet)
	- Two IP addresses separated from each other by at least one router must be in different groups (subnets)
- Hostnames are used to identify other computers
- DNS allows a computer to find the IP address used by a hostname 
- Routers use ARP to know what MAC address to use for the destination 
- Ping uses ICMP to send a message called an ICMP echo request to another IP address

## Diagrams / Topologies
![[Pasted image 20241027160041.png]]

![[Pasted image 20241103062437.png]]

![[Pasted image 20241103062813.png]]

![[Pasted image 20241103064529.png]]

![[Pasted image 20241103065901.png]]

![[Pasted image 20241103070240.png]]

![[Pasted image 20241103070726.png]]

![[Pasted image 20241103071021.png]]

![[Pasted image 20241103071510.png]]

--- 
#ARP #default-gateway #DNS #Ethernet-Line-Service #Ethernet-WAN #HDLC #hostname #IP-address #IP-network #IP-packet #IP-subnet #ping #routing-protocol #routing-table #serial-interface #subnetting #WAN