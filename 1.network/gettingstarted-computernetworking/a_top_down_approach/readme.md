# Summary of Computer Networking A Top-Down Approach - james F. Kurose & Keith W. Ross

## Table of Conents

1. ##### Computer Networks and the Internet
   
   1. What is The Internet
      
      1. A Nuts-and-Bolts Description
      
      2. A Services Description
      
      3. What is a Protocol ?
   
   2. The Network Edge
      
      1. Access Networks
      
      2. Physical Media
   
   3. The Network Core
      
      1. Packet Switching
      
      2. Circuit Switching
      
      3. A Network of Networks
   
   4. Delay, Loss, and Throughput in Packet-Switched Networks
      
      1. Overview of Delay in Packet-Switched Networks
      
      2. Queuing Delay and Packet Loss
      
      3. End-to-End Delay
      
      4. Throughput in Computer Networks
   
   5. Protocol Layers and Their Service Models
      
      1. Layered Architecture
      
      2. Encapsulation
   
   6. Networks Under Attack
   
   7. History of Computer Networking and the Internet
      
      1. The Development of Packet Switching: 1961-1972
      
      2. Proprietary Networks and Internetworking: 1972-1980
      
      3. A Proliferation of Networks: 1980-1990
      
      4. The Internet Explosion: The 1990s
      
      5. The New Millenium
   
   8. Summary

2. ##### Application Layer
   
   1. Principles of Network Applications
      
      1. Network Application Architectures
      
      2. Process Communicating
      
      3. Transport Services Available to Applications
      
      4. Transport Services Provided by the Internet
      
      5. Application-Layer Protocols
      
      6. Network Applications Covered in This Book
   
   2. The Web and HTTP
      
      1. Overview of HTTP
      
      2. Non-Persistent and Persistent Connections
      
      3. HTTP Message Format
      
      4. User-Server Interaction: Cookies
      
      5. Web Caching
      
      6. HTTP/2
   
   3. Electronic Mail in the Internet
      
      1. SMTP
      
      2. Mail Message Formats
      
      3. Mail Access Protocols
   
   4. DNS - The Internet's Directory Service
      
      1. Services Provided by DNS
      
      2. Overview of How DNS Works
      
      3. DNS Records and Messages
   
   5. Peer-to-Peer File Distribution
   
   6. Video Streaming and Content Distribution Networks
      
      1. Internet Video
      
      2. HTTP Streaming and DASH
      
      3. Content Distribution Networks
      
      4. Case Studies: Netflix and Youtube
   
   7. Socket Programming: Creating Network Applications
      
      1. Socket Programming with UDP
      
      2. Socket Programming with TCP
   
   8. Summary

3. ##### Transport Layer
   
   1. Introduction and Transport-Layer Services
      
      1. Relationshipo Between Transport and Network Layers
      
      2. Overview of the Transport Layer in the Internet
   
   2. Multiplexing and Demultiplexing
   
   3. Connectionless Transport: UDP
      
      1. UDP Segment Structure
      
      2. UDP Checksum
   
   4. Principles of Reliable Dta Transfer
      
      1. Building a Reliable Data Transfer Protocol
      
      2. PipelinedReliable Data Transfer Protocols
      
      3. Go-Back-N (GBN)
      
      4. Selective Repeat(SR)
   
   5. Connection-Oriented Transport: TCP
      
      1. The TCP Connection
      
      2. TCP Segment Structure
      
      3. Round-Trip Time Estimation and Timeout
      
      4. Reliable Data Transfer
      
      5. Flow Control
      
      6. TCP Connection Management
   
   6. Principles of Congestion Control
      
      1. The Causes and the Costs of Congestion
      
      2. Approaches to Congestion Control
   
   7. TCP Congestion Control
      
      1. Classic TCP COngestion Control
      
      2. Network-Assisted Explicit Congestion Notification and Delayed-based Congestion Control
      
      3. Fairness
   
   8. Evolution of Transport-Layer Functionality
   
   9. Summary

4. ##### The Network Layer: Data Plane
   
   1. Overview of Network Layer
      
      1. Forwading and Routing: The Data and Control Planes
      
      2. Network Service Model
   
   2. What's Inside a Router ?
      
      1. Input Port Processing and Desination-Based Forwarding
      
      2. Switching
      
      3. Output Port Processing
      
      4. Where Does Queuing Occur ?
      
      5. Packet Scheduling
   
   3. The Internet Protocol(IP): IPv4, Addressing,  IPv6, and more
      
      1. IPv4 Datagram Format
      
      2. IPv4 Addressing
      
      3. Network Address Translation(NAT)
      
      4. IPv6
   
   4. Generalized Forwarding and SDN
      
      1. Match
      
      2. Action
      
      3. OpenFlow Examples of Match-plus-action in Action
   
   5. Middleboxes
   
   6. Summary

5. ##### The Network Layer: Control Plane
   
   1. Introduction
   
   2. Routing Algorithms
      
      1. The Link-State(LS) Routing Algorithm
      
      2. The Distance-Vector(DV) Routing Algorithm
   
   3. Intra-AS Routing int he Internet: OSPF
   
   4. Routing Among the ISPs: BGP
      
      1. The Role of BGP
      
      2. Advertising BGP Route Information
      
      3. Determining the Best Routes
      
      4. IP-Anycast
      
      5. Routing Policy
      
      6. Putting the Pieces Together: Obtaining Internet Presence
   
   5. The SDN Control Plane
      
      1. The SDN Control Plane: SDN Controller and SDN Network-control Applications
      
      2. OpenFlow Protocol
      
      3. Data and Control Plane Interaction: An Example
      
      4. SDN: Past and Future
   
   6. ICMP: The Internet Control Message Protocol
   
   7. Network Management and SNMP, NETCONF/YANG
      
      1. The Network Management Framework
      
      2. The SImple Network Management Protocol(SNMP) and the Management Information Base (MIB)
      
      3. The Network Configuration Protocol (NETCONF) and YANG
   
   8. Summary

6. ##### The Link Layer and LANs
   
   1. Introduction to the Link Layer
      
      1. The Services Provided by the Link Layer
      
      2. Where Is the Link Layer Implemented ?
   
   2. Error-Detection and  Correction Techniques
      
      1. Parity Checks
      
      2. Checksumming Methods
      
      3. Cyclic Redudancy Check(CRC)
   
   3. Multiple Access Links and Protocols
      
      1. Channel Partitioning Protocols
      
      2. Random Access Protocols
      
      3. Taking-Turns Protocols
      
      4. DOCSIS: The Link-Layer Protocol for Cable Internet Access
   
   4. Switched Local Area Networks
      
      1. Link-Layer Addressing and ARP
      
      2. Ethernet
      
      3. Link-Layer Switches
      
      4. Virtual Local Area Networks (VLANs)
   
   5. Link Virtualization: A Network as a Link Layer
      
      1. Multiprotocol Label Switching (MPLS)
   
   6. Data Center Networking
      
      1. Data Center Architectures
      
      2. Trends in Data Center Networking
   
   7. Retrospective: A Day in the Life of a Web Page Request
      
      1. Getting Started: DHCP, UDP, IP, and Ethernet
      
      2. Still Getting Started: DNS and ARP
      
      3. Still Getting Started: Intra-Domain Routing to the DNS Server
      
      4. Web Client-Server Interaction: TCP and HTTP
   
   8. Summary

7. ##### Wireless and Mobile Networks
   
   1. Introduction
   
   2. Wireless Links and Network Characteristics
      
      1. CDMA
   
   3. WiFi: 802.11 Wireless Lans
      
      1. The 802.11 Wireless LAN Architecture
      
      2. The 802.11 MAC Protocol
      
      3. The IEEE 802.11 Frame
      
      4. Mobility in the Same IP Subnet
      
      5. Advanced Features in 802.11
      
      6. Personal Area Networks: Bluetooth
   
   4. Cellular Networks: 4G and 5G
      
      1. 4G LTE Cellular Networks: Architecture and Elements
      
      2. LTE Protocols Stacks
      
      3. LTE Radio Access Network
      
      4. Additional LTE Functions: Network Attachment and Power Management
      
      5. The Global Cellular network: A Network of Networks
      
      6. 5G Cellular Networks
   
   5. Mobility Management: Principles
      
      1. Device Mobility: a Network-layer Perspective
      
      2. Home Networks and Roaming on Visited Networks
      
      3. Direct and Indirect Routing to/from a Mobile Device
   
   6. Mobility Management in Practice
      
      1. Mobility Management in 4G/5G Networks
      
      2. Mobile IP
   
   7. Wireless and Mobility: Impact on Higher-Layer Protocols
   
   8. Summary

8. ##### Security in Computer Networks
   
   1. What is Network Security
   
   2. Principles of Cryptography
      
      1. Symmetric Key Cryptography
      
      2. Public Key Encryption
   
   3. Message Integrity and Digital Signatures
      
      1. Cryptographic Hash Functions
      
      2. Message Authentication Code
      
      3. Digital Signatures
   
   4. End-Point Authentication
   
   5. Securing E-Mail
      
      1. Secure E-Mail
      
      2. PGP
   
   6. Securing TCP Connections: TLS
      
      1. The Big Picture
      
      2. A More Complete Picture
   
   7. Network-Layer Security: IPsec and Virtual Private Networks
      
      1. IPsec and Virtual Private Networks (VPNs)
      
      2. The AH and ESP Protocols
      
      3. Security Associations
      
      4. The IPsec Datagram
      
      5. IKE: Key Management in IPsec
   
   8. Securing Wireless LANs and 4G/5G Cellular Networks
      
      1. Authentication and Key Agreement in 802.11 Wireless LANs
      
      2. Authentication and Key Agreement in 4G/5G Cellular Networks
   
   9. Operational Secuirty: Firewalls and Intrusion Detection Systems
      
      1. Firewalls
      
      2. Intrusion Detection Systems
   
   10. Summary
