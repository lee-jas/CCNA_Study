---
tags:
  - intro-to-networking
  - dikta
date:
---

---

## Multiple Choice Questions

### Question 1
**Q:** Which of the following protocols are examples of TCP/IP transport layer protocols? (2)

- [ ] A) Ethernet
- [ ] B) HTTP
- [ ] C) IP
- [x] D) UDP
- [ ] E) SMTP
- [x] F) TCP

<details>
<summary>**Answer**</summary>
C) To direct traffic between different networks
</details>


### Question 2
**Q:** Which of the following protocols are examples of TCP/IP data-link layer protocols? (2)

- [x] A) Ethernet
- [ ] B) HTTP
- [ ] C) IP
- [ ] D) UDP
- [ ] E) SMTP
- [ ] F) TCP
- [x] G) 802.11

### Question 3
**Q:** The process of HTTP asking TCP to send some data and making sure that it is received correctly is an example of what?

- [ ] A) Same-layer interaction
- [ ] B) Adjacent-layer interaction
- [x] C) TCPIP model
- [ ] D) All of the answers are correct

### Question 4
**Q:** The process of TCP on one computer marking a TCP segment as segment 1 and the receiving computer then acknowledging the receipt of TCP segment 1 is an example of

- [ ] A) Data encapsulation
- [x] B) Same-layer interaction
- [ ] C) Adjacent-layer interaction
- [ ] D) TCP/IP model
- [ ] E) All of the answers are correct

### Question 5
**Q:** The process of web server adding a TCP header to the contents of a web page, followed by adding an IP header and then adding data-link header and trailer, is an example of what?

- [x] A) Data encapsulation
- [ ] B) Same-layer interaction
- [ ] C) Adjacent-layer interaction
- [ ] D) TCP/IP model
- [ ] E) All of the answers are correct

---
### 1. Some end-user devices connect to a LAN using a cable while others use wireless. Which answer best characterizes which devices use Ethernet to connect to the LAN?
- [ ] a. Only the end-user devices that use cables are using Ethernet.
- [ ] b. Only the end-user devices that use wireless are using Ethernet.
- [x] c. Both the end-user devices using cables and those using wireless are using
Ethernet.
- [ ] d. Neither the end-user devices using cables nor those using wireless are using
Ethernet.

### 2. Which of the following Ethernet standards defines Gigabit Ethernet over UTP cabling?
- [x] a. 10GBASE-T
- [ ] b. 100BASE-T
- [ ] c. 1000BASE-T
- [ ] d. None of the other answers are correct.

### 3. Which of the following is true about Ethernet crossover cables for Fast Ethernet?
- [ ] a. Pins 1 and 2 are reversed on the other end of the cable.
- [ ] b. Pins 1 and 2 on one end of the cable connect to pins 3 and 6 on the other end of
the cable.
- [ ] c. Pins 1 and 2 on one end of the cable connect to pins 3 and 4 on the other end of
the cable.
- [ ] d. The cable can be up to 1000 meters long to cross over between buildings.
- [ ] e. None of the other answers are correct.

### 4. Each answer lists two types of devices used in a 100BASE-T network. If these devices were connected with UTP Ethernet cables, which pairs of devices would require a straight-through cable? (Choose three answers.)
- [x] a. PC and router
- [x] b. PC and switch
- [ ] c. Hub and switch
- [ ] d. Router and hub
- [ ] e. Wireless access point (Ethernet port) and switch
### 5. Which of the following are advantages of using multimode fiber for an Ethernet link instead of UTP or single-mode fiber? (Choose two answers.)
- [ ] a. To achieve the longest distance possible for that single link.
- [ ] b. To extend the link beyond 100 meters while keeping initial costs as low as possible.
- [ ] c. To make use of an existing stock of laser-based SFP/SFP+ modules.
- [ ] d. To make use of an existing stock of LED-based SFP/SFP+ modules.


---

### 1. Which of the following terms is not commonly used to describe a serial link?
- [x] a. Private line
- [ ] b. Point-to-point link
- [ ] c. Leased circuit
- [ ] d. E-line

### 2. Two routers, R1 and R2, connect using an Ethernet WAN service. The service provides point-to-point service between these two routers only, as a Layer 2 Ethernet service. Which of the following are the most likely to be true about this WAN? (Choose two answers.)
- [ ] a. R1 will connect to a physical Ethernet link, with the other end of the cable
connected to R2.
- [ ] b. R1 will connect to a physical Ethernet link, with the other end of the cable
connected to a device at the WAN service provider point of presence.
- [ ] c. R1 will forward data-link frames to R2 using an HDLC header/trailer.
- [ ] d. R1 will forward data-link frames to R2 using an Ethernet header/trailer.

### 3. Imagine a network in which PC1 connects to the same Ethernet LAN as Router1, PC2 connects to the same LAN as Router2, and the two routers connect to each other with a PPP serial link. When PC1 sends data to PC2, and Router1 removes the Ethernet header and trailer, which of the following is true?
- [ ] a. Router1 does not use the removed Ethernet header/trailer again.
- [x] b. Router1 re-encapsulates the packet in a PPP frame that uses the Ethernet
addresses from the removed header.
- [ ] c. Router1 also removes the IP header before forwarding the data to Router2.
- [ ] d. Router1 re-encapsulates the packet in a new Ethernet frame before forwarding the
packet to Router2.

### 4. Which of the following does a router normally use when making a decision about routing TCP/IP packets?
- [ ] a. Destination MAC address
- [ ] b. Source MAC address
- [ ] c. Destination IP address
- [ ] d. Source IP address
- [x] e. Destination MAC and IP addresses

### 5. Which of the following are true about a LAN-connected TCP/IP host and its IP routing (forwarding) choices?
- [ ] a. The host always sends packets to its default gateway.
- [ ] b. The host never sends packets to its default gateway.
- [x] c. The host sends packets to its default gateway if the destination IP address is in a
different subnet than the host.
- [ ] d. The host sends packets to its default gateway if the destination IP address is in the
same subnet as the host.

---
[[1_Introduction to TCP IP Networking]]
[[2_Fundamentals of Ethernet LANs]]
[[3_Fundamentals of WANs and IP Routing]]
