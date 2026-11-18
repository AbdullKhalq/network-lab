# Todd Lammle Network+ N09

## Chapter 1
THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 1.0 Networking Concepts
1.6 Compare and contrast network topologies, architectures, and types.
Mesh
Hybrid
Star/hub and spoke
Spine and leaf
Point to point
Three-tier hierarchical model
Core
Distribution
Access
Traffic flows
North-south
East-west

Exam Essentials
Know your network topologies.    Know the names and descriptions of the topologies. Be aware of the difference between physical networks (what humans see) and logical networks (what the equipment “sees”).

Know the advantages and disadvantages of the topologies.    It is essential to know what each topology brings to the table. Knowing the various characteristics of each topology comes in handy during troubleshooting.

Understand the terms LAN and WAN.    You need to understand when you would use a LAN and when you would use a WAN. A LAN is used to connect a group of hosts, and a WAN is used to connect various LANs.

Know the three-tiered model and collapsed core.    Know what the core, distribution, and access layer provide in the three-tier model. The collapsed core is used to reduce costs by collapsing the core and distribution tiers into one tier.

Understand the differences between north-south traffic and east-west traffic.    North-south traffic typically leaves the network through a routed connection. East-west traffic typically resides in the immediate network.

## Chapter 2

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 1.0 Networking Concepts
1.1 Explain concepts related to the Open Systems Interconnection (OSI) reference model.
Layer 1 - Physical
Layer 2 - Data link
Layer 3 - Network
Layer 4 - Transport
Layer 5 - Session
Layer 6 - Presentation
Layer 7 - Application

Memorize and understand the OSI layers.    You must remember and understand the seven layers of the OSI model and what function each layer provides. The Application, Presentation, and Session layers are the upper layers responsible for communicating from a user interface to an application. The Transport layer provides segmentation, sequencing, and virtual circuits. The Network layer provides logical network addressing and routing through the internetwork. The Data Link layer frames and places data on the network medium. The Physical layer is responsible for taking 1s and 0s and encoding them into a digital signal for transmission on the network segment.

Know the sublayers of the Data Link layer.    In addition to the OSI layers, knowing that the Data Link layer is the only layer that has sublayers and the functions of those sublayers is extremely important. The Data Link layer has two sublayers: LLC and MAC. The LLC sublayer is responsible primarily for the multiplexing of Network layer protocols. The MAC sublayer is responsible for physical addressing and determining the appropriate time to place data on the network.

## Chapter 3

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:
Domain 1.0 Networking Concepts
1.5 Compare and contrast transmission media and transceivers.
Wired
Single-mode vs. multimode fiber
Direct attach copper
(DAC) cable
Twinaxial cable
Coaxial cable
Cable speeds
Plenum vs. non-plenum cable
Transceivers
Protocol
Ethernet
Fibre Channel (FC)
Form factors
Small form-factor pluggable (SFP)
Quad small form-factor pluggable (QSFP)
Connector types
Subscriber connector (SC)
Local connector (LC)
Straight tip (ST)
Multi-fiber push on (MPO)
Registered jack (RJ)11
RJ45
F-type
Bayonet Neill–Concelman (BNC)
Domain 5.0
5.2 Given a scenario, troubleshoot common cabling and physical interface issues.
Cable issues
Incorrect cable
Single mode vs. multimode
Category 5/6/7/8
Shielded twisted pair (STP)
vs. unshielded twisted pair
(UTP)

Know the various types of cables used in today's networks.    Coaxial (other than for cable modems) is rarely used, but twisted-pair cable and fiber-optic cable are very common in today's networks.

Know the various types of ends that are used on each type of cable.    Coax uses BNC; twisted-pair uses RJ-11 for voice and RJ-45 for data; and fiber uses various ends, depending on its use. Know how to identify each type of connector.

Describe the various types of media converters that are available.    These include single-mode fiber to Ethernet, multimode fiber to Ethernet, fiber to coaxial, and single-mode to multimode fiber.

Understand what a T568A to T568A cable is.    A T568A to T568A cable is also known as an Ethernet straight-through cable and is used to connect hosts to switches, for example.

Understand what a T568A to T568B cable is.    A T568A to T568B cable is also known as an Ethernet crossover cable and is used to connect switches to switches, for example.

Define the function of a T1 crossover cable.    In rare instances, you may have the need to run a cable between two CSU/DSUs.

Know the various transceivers in use.    You should know how to identify the SFP, QSFP, FC, and Ethernet transceivers. In addition, you should know the benefits of each of the transceivers.

## Chapter 4

Domain 1.0 Networking Concepts
1.5 Compare and contrast transmission media and transceivers.
Wired
802.3 standards
Coaxial cable

Understand basic Ethernet communication.    Know how hosts use hardware addresses to communicate on an Ethernet LAN.

Understand Ethernet addressing.    Know the hexadecimal addressing scheme used to create an Ethernet address.

Understand binary, decimal, and hexadecimal addressing.    Know the different addressing types, and also use the written lab to practice your conversions.

Know the various Ethernet standards.    This includes understanding the various copper and fiber-based standards.

## Chapter 5

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 2.0 Network Implementation
2.3 Given a scenario, select and configure wireless devices and technologies
Autonomous vs. lightweight access point
Domain 3.0 Network Operations
3.4 Given a scenario, implement IPv4 and IPv6 network services.
Dynamic addressing
DHCP
Reservations
Scope
Lease time
Options
Relay/IP helper
Exclusions
Name resolution
DNS
Domain Name Security
Extensions (DNSSEC)
DNS over HTTPS (DoH) and DNS over TLS (DoT)
Record types
Address (A)
AAAA
Canonical name (CNAME)
Mail exchange (MX)
Text
Nameserver (NS)
Pointer
Zone types
Forward
Reverse
Authoritative vs. non-authoritative
Primary vs. secondary
Recursive
Hosts file
Time protocols
NTP
Precision Time Protocol (PTP)
Network Time Security (NTS)

Understand how DHCP works and its purpose.    Dynamic Host Configuration Protocol (DHCP) provides IP configuration information to hosts. It is important to know how a DHCP client requests information from a server, how a server receives this information, and also how the server responds to the client and with what type of information.

Understand how DNS works and its purpose.    The Domain Name System (DNS) is used to resolve human names to IP addresses. Understanding how DNS resolves these names is critical, as is understanding how a DNS query is sent and how a DNS server responds. Know the different types of DNS records and what they are used for.

Understand the difference between a hub, a switch (bridge), and a router.    A hub just connects network segments together. A switch/bridge segments the network using MAC addresses, and a router segments the network using logical addressing (IP and IPv6). Switches break up collision domains, and routers break up broadcast domains by default.

Remember the different names for a router.    A router is a layer 3 hardware device, but it can also be called a layer 3 switch or a multilayer switch.

Remember the various devices used on networks today and when you would use each one and how.    Understand the differences and how each device works: routers, switches, hubs, DNS servers, and DHCP servers.

Identify the purpose, benefits, and characteristics of using a proxy service.    A proxy server keeps a LAN somewhat separated from the Internet. Doing so increases security and filtering control and has the tendency to speed up Internet access through caching of recently used web pages.

Describe the proper use of network segmentation when planning and implementing a basic SOHO network.    Understand and apply the concepts of proper network segmentation when planning the use of various devices in the design of a SOHO network.

Describe the benefits of using a network load balancer.    Network load balancers allow incoming connections to be spread out across multiple servers for scalability and resiliency. Understand the architecture of how load balancers are inserted into a network.

Describe the benefits of using dedicated appliances for certain services.    Using appliances to offload functions such as encryption, content filtering, and VPN concentrators can decrease the workload of other systems and add functionality that may be present in these dedicated devices.

Also, wireless LAN controllers let you configure the complete network on a single device and push the configurations out to the Wi-Fi access points. The access points also tunnel the user data back to the controller, which then forwards the traffic onto the local area network (LAN).

Lastly, NTP servers provide accurate date and time information to servers and networking equipment.

Identify the environmental requirements of infrastructure devices.    A cool temperature, ample ventilation, and the proper humidity level are all keys to maintaining the operation of devices such as routers, switches, and appliances.

Written Lab

## Chapter 6

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 1.0 Networking Concepts
1.1 Explain concepts related to the Open Systems Interconnection (OSI) reference model.
Layer 1 - Physical
Layer 2 - Data link
Layer 3 - Network
Layer 4 - Transport
Layer 5 - Session
Layer 6 - Presentation
Layer 7 - Application
1.4 Explain common networking ports, protocols, services, and traffic types.
Protocols Ports
	File Transfer Protocol (FTP)	20/21
	Secure File Transfer Protocol (SFTP)	22
	Secure Shell (SSH)	22
	Telnet	23
	Simple Mail Transfer Protocol (SMTP)	25
	Domain Name System (DNS)	53
	Dynamic Host Configuration Protocol (DHCP)	67/68
	Trivial File Transfer Protocol (TFTP)	69
	Hypertext Transfer Protocol (HTTP)	80
	Network Time Protocol (NTP)	123
	Simple Network Management Protocol (SNMP)	161/162
	Lightweight Directory Access Protocol (LDAP)	389
	Hypertext Transfer Protocol Secure (HTTPS)	443
	Server Message Block (SMB)	445
	Syslog	514
	Simple Mail Transfer Protocol Secure (SMTPS)	587
	Lightweight Directory Access Protocol over SSL (LDAPS)	636
	Structured Query Language (SQL) Server	1433
	Remote Desktop Protocol (RDP)	3389
	Session Initiation Protocol (SIP)	5060/5061
Internet Protocol (IP) types
Internet Control Message Protocol (ICMP)
Transmission Control Protocol (TCP)
User Datagram Protocol (UDP)
Generic Routing Encapsulation (GRE)
Internet Protocol Security (IPSec)
Authentication Header (AH)
Encapsulating Security Payload (ESP)
Internet Key Exchange (IKE)

## Chapter 7

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 1.0 Networking Concepts
1.7 Given a scenario, use appropriate IPv4 network addressing.
Public vs. private
Automatic Private IP Addressing (APIPA)
RFC1918
Loopback/localhost
Subnetting
Variable Length Subnet Mask (VLSM)
Classless Inter-domain Routing (CIDR)
IPv4 address classes
Class A
Class B
Class C
Class D
Class E
1.8 Summarize evolving use cases for modern network environments.
IPv6 addressing
Mitigating address exhaustion
Compatibility requirements
Tunneling
Dual stack
NAT64
Domain 3.0 Network Operations
3.4 Given a scenario, implement IPv4 and IPv6 network services.
Stateless address autoconfiguration (SLAAC)

## Chapter 8

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 1.0 Networking Concepts
1.4 Explain common networking ports, protocols, services, and traffic types.
Traffic types
Unicast
Multicast
Anycast
Broadcast
1.7 Given a scenario, use appropriate IPv4 network addressing.
Public vs. private
Automatic Private IP Addressing (APIPA)
RFC1918
Loopback/localhost
Subnetting
Variable Length Subnet Mask (VLSM)
Classless Inter-domain Routing (CIDR)
IPv4 address classes
Class A
Class B
Class C
Class D
Class E
Domain 2.0 Network Implementation
2.1 Explain characteristics of routing technologies.
Address translation
NAT
Port address translation (PAT)

Exam Essentials
Remember the steps to subnet in your head.    Understand how IP addressing and subnetting work. First, determine your block size by using the 256-subnet mask math. Then, count your subnets and determine the broadcast address of each subnet—it is always the number right before the next subnet. Your valid hosts are the numbers between the subnet address and the broadcast address.

Understand the various block sizes.    This is an important part of understanding IP addressing and subnetting. The valid block sizes are always 4, 8, 16, 32, 64, 128, and so on. You can determine your block size by using the 256-subnet mask math.

Remember the four diagnostic steps.    The four simple steps for troubleshooting are ping the loopback address, ping the NIC, ping the default gateway, and ping the remote device.

You must be able to find and fix an IP addressing problem.    Once you go through the four troubleshooting steps, you should be able to determine the IP addressing problem by drawing out the network and finding the valid and invalid hosts addressed in your network.

Understand basic NAT terminology.    You want to know the difference between inside local and inside global. Inside local is before translation, and inside global is after translation. Inside global is a registered address representing an inside host to an outside network. You should also understand PAT and how it works by using different port numbers to map multiple private IP addresses to a single registered IP address.

## Chapter 9

Domain 2.0 Network Implementation
2.1 Explain characteristics of routing technologies.
Static routing
Dynamic routing
Border Gateway Protocol (BGP)
Enhanced Interior Gateway Routing Protocol (EIGRP)
Open Shortest Path First (OSPF)
Route selection
Administrative distance
Prefix length
Metric

Exam Essentials
Understand the basic IP routing process.    You need to remember that the frame changes at each hop, but that the packet is never changed or manipulated in any way until it reaches the destination device.

Understand that MAC addresses are always local.    A MAC (hardware) address will be used only on a local LAN. It will never pass a router's interface.

Understand that a frame carries a packet to only two places.    A frame uses MAC (hardware) addresses to send a packet on a LAN. The frame will take the packet to either a host on the LAN or a router's interface if the packet is destined for a remote network.

Remember the difference between static and dynamic routing.    Static routing is where you, as the administrator, by hand add every route into every routing table on every router on the network. This is as much work as it sounds like, which is why we use dynamic routing protocols that do the work for us. Of course, we'll discuss dynamic routing protocols more in the next chapter, but the main job of a routing protocol is to update routing tables.

## Chapter 10

Domain 1.0 Networking Concepts
1.2 Compare and contrast networking appliances, applications, and functions.
Physical and virtual appliances
Router
1.8 Summarize evolving use cases for modern network environments.
IPv6 addressing
Mitigating address exhaustion
Compatibility requirements
Tunneling
Dual stack
Domain 2.0 Network Implementation
2.1 Explain characteristics of routing technologies.
Static routing
Dynamic routing
Border Gateway Protocol (BGP)
Enhanced Interior Gateway
Routing Protocol (EIGRP)
Open Shortest Path First (OSPF)
Route selection
Administrative distance
Prefix length
Metric
First Hop Redundancy Protocol (FHRP)
Virtual IP (VIP)
Subinterfaces

Exam Essentials
Understand the various dynamic routing protocols including RIP, OSPF, EIGRP, and BGP.    RIP is a distance-vector routing protocol. It sends the complete routing table out to all active interfaces every 30 seconds. RIP uses hop count to determine the best path to a remote network. EIGRP is also a distant-vector protocol that uses link-state characteristics to determine the best path to a remote network. BGP is an external protocol that uses a path vector protocol between autonomous systems. OSPF is an open-standard and link-state protocol that uses the Dijkstra algorithm for best path selection.

Be able to distinguish between link state vs. distance vector vs. hybrid.    Link-state protocols use an algorithm to learn more information about the internetwork. Distance-vector protocols use a hop count to determine neighbors. Hybrid protocols will use a combination of distance vector and link state to determine the best path selection.

Know what the Neighborhood Discovery Protocol (NDP) and Router Advertisement (RA) protocol is used for.    NDP is used in an IPv6 network to discover various information from neighboring devices. Router advertisements are used to detect the gateway out of the network.

Remember the differences between RIPv1 and RIPv2.    RIPv1 sends broadcasts every 30 seconds and has an AD of 120. RIPv2 sends multicasts (224.0.0.9) every 30 seconds and also has an AD of 120. RIPv2 sends subnet mask information with the route updates, which allows it to support classless networks and discontiguous networks. RIPv2 also supports authentication between routers, and RIPv1 does not.

Compare OSPF and RIPv1.    OSPF is a link-state protocol that supports VLSM and classless routing; RIPv1 is a distance-vector protocol that does not support VLSM and supports only classful routing.

Understand the various compatibility requirements.    Know the various compatibility strategies for supporting both IPv4 and IPv6. This should include tunneling of IPv6 through an IPv4 network, Teredo, ISATAP tunneling, and dual stack.

## Chapter 11

THE FOLLOWING COMPTIA NETWORK+ EXAM OBJECTIVES ARE COVERED IN THIS CHAPTER:

Domain 2.0 Network Implementation
2.2 Given a scenario, configure switching technologies and features.
Virtual Local Area Network (VLAN)
VLAN database
Switch Virtual Interface (SVI)
Interface configuration
Native VLAN
Voice VLAN
802.1Q tagging
Link aggregation
Speed
Duplex
Spanning tree
Maximum transmission unit (MTU)
Jumbo frames
Domain 5.0 Network Troubleshooting
5.3 Given a scenario, troubleshoot common issues with network services.
Switching issues
STP
Network loops
Root bridge selection
Port roles
Port states
5.4 Given a scenario, troubleshoot common performance issues.

Exam Essentials
Remember the three switch functions.    Address learning, forward/filter decisions, and loop avoidance are the functions of a switch.

Understand the main purpose of the Spanning Tree Protocol in a switched LAN.    The main purpose of STP is to prevent switching loops in a network with redundant switched paths.

Remember the states of STP.    The purpose of the blocking state is to prevent the use of looped paths. A port in the listening state prepares to forward data frames without populating the MAC address table. A port in the learning state populates the MAC address table but doesn't forward data frames. A port in the forwarding state sends and receives all data frames on the bridged port. Last, a port in the disabled state is virtually nonoperational.

Remember to check a switch port's VLAN assignment when plugging in a new host.    If you plug a new host into a switch, then you must verify the VLAN membership of that port. If the membership is different than what is needed for that host, the host will not be able to reach the needed network services, such as a workgroup server.

Understand what PoE provides.    Power over Ethernet was created to provide power to devices that are connected to a switch port but that are not in a place that has a power outlet—for example, an access point in a ceiling.

Understand what jumbo frames provide.    Jumbo frames allow the maximum transmission unit (MTU) to be extended to 9000 bytes from the default 1500 bytes.

List features that can be used to maintain the STP topology.    These include BPDU Guard, Root Guard, and flood guards.

## Chapter 12

Domain 1.0 Networking Concepts
1.5 Compare and contrast transmission media and transceivers.
Wireless
802.11 standards
Cellular
Satellite
Domain 2.0 Network Implementation
2.3 Given a scenario, select and configure wireless devices and technologies.
Channels
Channel width
Non-overlapping channels
Regulatory impacts
802.11h
Frequency options
2.4GHz
5GHz
6GHz
Band steering
Service set identifier (SSID)
Basic service set identifier (BSSID)
Extended service set identifier (ESSID)
Network types
Mesh networks
Ad hoc
Point to point
Infrastructure
Encryption
Wi-Fi Protected Access 2 (WPA2)
WPA3
Guest networks
Captive portals
Authentication
Pre-shared key (PSK) vs. Enterprise
Antennas
Omnidirectional vs. directional
Autonomous vs. lightweight access point

Exam Essentials
Understand the IEEE 802.11a specification.    802.11a runs in the 5 GHz spectrum, and if you use the 802.11h extensions, you have 23 non-overlapping channels. 802.11a can run up to 54 Mbps, but only if you are less than 50 feet from an access point.

Understand the IEEE 802.11b specification.    IEEE 802.11b runs in the 2.4 GHz range and has three non-overlapping channels. It can handle long distances but with a maximum data rate of up to 11 Mbps.

Understand the IEEE 802.11g specification.    IEEE 802.11g is 802.11b's big brother and runs in the same 2.4 GHz range, but it has a higher data rate of 54 Mbps if you are less than 100 feet from an access point.

Understand the IEEE 802.11n specification.    IEEE 802.11n operates in the 2.4 GHz and 5 GHz range. Support for 5 GHz bands is optional. Its net data rate ranges from 54 Mbit/s to 600 Mbit/s. The standard also added support for multiple-input, multiple-output (MIMO) antennas.

Understand the IEEE 802.11ac specification.    IEEE 802.11ac-2013 is an amendment that builds on 802.11n. Changes include wider channels (80 or 160 MHz versus 40 MHz) in the 5 GHz band and more spatial streams (up to eight versus four). Wave 2 products include additional features like MU-MIMO, 160 MHz channel width support, support for more 5 GHz channels, and four spatial streams with four antennas.

Understand the IEEE 802.11ax specification.    IEEE 802.11ax is the successor to 802.11ac. It's marketed as Wi-Fi 6 (2.4 GHz and 5 GHz) and Wi-Fi 6E (6 GHz). It is also known as High Efficiency Wi-Fi, for the overall improvements to Wi-Fi 6. Data rates against the predecessor (802.11ac) are only 39%. For comparison, this improvement was nearly 500% for the other predecessors.

Understand the different Wi-Fi standards, frequencies, and ranges.    Wi-Fi standards are 802.11a/b/g/n/ac/ax using 2.4 GHz and 5 GHz. 802.11ac is also known as Wi-Fi 5, and 802.11ax is also known as Wi-Fi 6.

Remember the various service set identifiers (SSIDs).    SSIDs can use a basic service set, an extended service set, an independent service set (ad hoc), and a roaming service set.

Remember the antenna types.    Wi-Fi antennas can be Omni directional or directional.

Remember the encryption standards.    Encryption standards include Wi-Fi Protected Access (WPA), WPA2 Personal (Advanced Encryption Standard-AES), Temporal Key Integrity Protocol (TKIP), and WPA/WPA2 Enterprise (AES/TKIP).

Remember the cellular technologies.    Technologies used in cellular communications include code division multiple access(CDMA), global System Mobile (GSM), Long-Term Evolution (LTE), and 3g, 4g, and 5g.

Understand MIMO/MU-MIMO.    MIMO is multiple-input, multiple output, which is widely used in 802.11n and 802.11zc. MU-MIMO is multiuser multiple input, multiple output, which is used in the new 802.11ax protocol.

Remember the wireless LAN modulation techniques.    Direct-sequence spread spectrum (DSSS) is the most widely used modulation technique, but it has speeds only to 11 Mbps. However, the old and pretty much no-longer used frequency-hopping spread spectrum (FHSS), although it is still used in old wireless devices like Bluetooth, isn't the technique of choice for either vendors or the 802.11 working group. To get the higher speeds needed in today's WLANs, we use orthogonal frequency-division multiplexing (OFDM) in 802.11g/a/n and 802.11ac/ax networks.

Understand how WPA works in a WLAN.    Wi-Fi Protected Access (WPA) is the security of choice in today's home and corporate networks. It provides both authentication and encryption (either TKIP or AES).

## Chapter 13

Domain 3.0 Network Operations
3.5 Compare and contrast network access and management methods.
Site-to-site VPN
Client-to-site VPN
Clientless
Split tunnel vs. full tunnel
Connection methods
SSH
Graphical user interface (GUI)
API
Console
Jump box/host
In-band vs. out-of-band management

Exam Essentials
Explain VPN architectures.    These include site-to-site VPNs, client-to-site VPN, clientless VPN, split tunnel versus full, and SSH VPN.

Describe SSL and TLS.    This includes the differences between the two and the advantages of TLS. It also includes common applications with respect to VPNs.

Identify other remote access solutions.    These include VNC, RDP, Remote Desktop Gateway, remote desktop connections, and virtual connections.

Understand in-band and out-of-band management.    In-band management is access via the network over SSH, Telnet, or some other network protocol. Out-of-band management is access via a method not connected to the network, such as a serial connection.

## Chapter 14

Domain 3.0 Network Operations
3.2 Given a scenario, use network monitoring technologies.
Methods
SNMP
Traps
Management information base (MIB)
Versions: v2c, v3
Community strings
Authentication
Flow data
Packet capture
Baseline metrics
Anomaly alerting/notification
Log aggregation
Syslog collector
Security information and event management (SIEM)
Application programming interface (API) integration
Port mirroring
Solutions
Network discovery
Ad hoc
Scheduled
Traffic analysis
Performance monitoring
Availability monitoring
Configuration monitoring

Exam Essentials
Understand how to use performance metrics.    These include device metrics such as temperature, central processing unit (CPU) usage, and memory and network metrics, such as bandwidth, latency, jitter, and packet loss.

Describe the operation of SNMP.    Identify the roles that traps, object identifiers (OIDs), and management information bases (MIBs) play in monitoring the network with SNMP.

Know the various versions of SNMP.    The two versions covered on the Network+ exam are v2c and v3. Version 3 allows for better authentication and encryption of messages.

Utilize network device logs in addressing system issues.    Locate relevant information by reviewing logs such as traffic logs and audit logs. Describe the use of Syslog in centralizing these logs.

## Chapter 15

Domain 2.0 Network Implementations
2.4 Explain important factors of physical installations.
Important installation implications
Locations
Intermediate distribution frame (IDF)
Main distribution frame (MDF)
Rack size
Port-side exhaust/intake
Cabling
Patch panel
Fiber distribution panel
Lockable
Domain 3.0 Network Operations
3.1 Explain the purpose of organizational processes and procedures.
Documentation
Physical vs. logical diagrams
Rack diagrams
Cable maps and diagrams
Network diagrams
Layer 1
Layer 2
Layer 3
Asset inventory
Hardware
Software
Licensing
Warranty support
IP address management (IPAM)
Service-level agreement (SLA)
Wireless survey/heat map
Life-cycle management
End-of-life (EOL)
End-of-support (EOS)
Software management
Patches and bug fixes
Operating system (OS)
Firmware
Decommissioning
Change management
Request process tracking/service request
Configuration management
Production configuration
Backup configuration
Baseline/golden configuration

Exam Essentials
Understand the importance of plans and procedures.    These include change management, incident response, disaster recovery, business continuity, and the system life cycle.

Describe hardening and security policies.    Among these are acceptable use, password, bring your own device (BYOD), remote access, and onboarding and offboarding policies.

Utilize common documentation.    These include physical network diagrams, floor plans, rack diagrams, intermediate distribution frame (IDF)/main distribution frame (MDF) documentation, logical network diagrams, wiring diagrams and site survey reports.

Identify common business agreements.    These agreements include nondisclosure agreements (NDA), service-level agreements (SLA), and memorandums of understanding (MOUs).

## Chapter 16

Domain 2.0 Network Implementations
2.4 Explain important factors of physical installations.
Power
Uninterruptible power supply(UPS)
Power distribution unit (PDU)
Power load
Voltage
Environmental factors
Humidity
Fire suppression
Temperature
Domain 3.0 Network Operations
3.3 Explain disaster recovery (DR) concepts.
DR metrics
Recovery point objective (RPO)
Recovery time objective (RTO)
Mean time to repair (MTTR)
Mean time between failures (MTBF)
DR sites
Cold site
Warm site
Hot site
High-availability approaches
Active-active
Active-passive
Testing
Tabletop exercises
Validation tests

Exam Essentials
Understand the importance of fault tolerance and high availability techniques.    These include load balancing, multipathing, NIC teaming, and router, switch, and firewall clusters.

Describe facilities and infrastructure redundancy techniques.    Among these are uninterruptible power supplies (UPSs), power distribution units (PDUs), generators, HVAC systems, fire suppression, and multiple Internet service providers (ISPs)/diverse paths.

Utilize disaster recovery techniques.    These include physical cold sites, warm sites, hot sites, and cloud sites. It also requires an understanding of RPO, MTTR, MTBF, and RTO.

Identify applications of active/active and active/passive configurations.    These include switch clusters, VRRP and HSRP, and firewall clusters.

## Chapter 17

Domain 1.0 Networking Concepts
1.3 Summarize cloud concepts and connectivity options.
Network functions virtualization (NFV)
Virtual private cloud (VPC)
Network security groups
Network security lists
Cloud gateways
Internet gateway
Network address translation (NAT) gateway
Cloud connectivity options
VPN
Direct Connect
Deployment models
Public
Private
Hybrid
Service models
Software as a service (SaaS)
Infrastructure as a service (IaaS)
Platform as a service (PaaS)
Scalability
Elasticity
Multitenancy
1.8 Summarize evolving use cases for modern network environments.
Software-defined network (SDN)
and software-defined wide area network (SD-WAN)
Application-aware
Zero-touch provisioning
Transport agnostic
Central policy management
Virtual Extensible Local Area Network (VXLAN)
Data Center Interconnect (DCI)
Layer 2 encapsulation
Zero trust architecture (ZTA)
Policy-based authentication
Authorization
Least privilege access
Secure Access Secure Edge (SASE)/Security Service Edge (SSE)
Infrastructure as code (IaC)
Automation
Playbooks/templates/reusable tasks
Configuration drift/compliance
Upgrades
Dynamic inventories
Source control
Version control
Central repository
Conflict identification
Branching

Exam Essentials
Know and understand the various type of cloud services.    Software as a service (SaaS) allows us to use an application provided and maintained by the service provider. Platform as a service (PaaS) is a platform for designing applications that are compiled and executed in the cloud. Infrastructure as a service (IaaS) allows the customer to rent the infrastructure of compute, network, and storage from the cloud provider.

Know and understand the various cloud delivery models.    In a private cloud, resources are owned by the organization and exclusively used by the organization. In a public cloud, resources at the provider are provisioned and used by the general public. A hybrid model is a blend of both the public cloud and private cloud within an organization.

Understand the basic operations of infrastructure as code (IaC).    Infrastructure as code allows an administrator to provision servers with code-based automation and orchestration tools, in lieu of manual provisioning. IaC is performed through the methods of automation and source control.

Know the basic concepts of software-defined networking.    SDN controllers are centralized management plane systems that use application programming interfaces (APIs) to configure the data network as a whole, which eliminates the need to log in and make changes individually to a large number of individual networking devices. Infrastructure as code allows you to divide your infrastructure into modular components that can be combined in different ways using automation.

## Chapter 18

Domain 5.0 Network Troubleshooting
5.1 Explain the troubleshooting methodology.
Identify the problem
Gather information
Question users
Identify symptoms
Determine if anything has changed
Duplicate the problem, if possible
Approach multiple problems individually
Establish a theory of probable cause
Question the obvious
Consider multiple approaches
Top-to-bottom/bottom-to-top OSI model
Divide and conquer
Test the theory to determine the cause
If the theory is confirmed, determine the next steps to resolve the problem
If the theory is not confirmed, reestablish a new theory or escalate
Establish a plan of action to resolve the problem and identify potential effects
Implement the solution or escalate as necessary
Verify full system functionality and, implement preventive measures if applicable
Document findings, actions, and outcomes and lessons learned throughout the process
5.2 Given a scenario, troubleshoot common cabling and physical interface issues.
Cable issues
Incorrect cable
Single mode vs. multimode
Shielded twisted pair (STP) vs. unshielded twisted pair (UTP)
Signal degradation
Crosstalk
Interference
Attenuation
Improper termination
Transmitter (TX)/Receiver (RX) transposed
Interface issues
Increasing interface counters
Cyclic redundancy check (CRC)
Runts
Giants
Drops
Port status
Error disabled
Administratively down
Suspended
Hardware issues
Power over Ethernet (PoE)
Power budget exceeded
Incorrect standard
Transceivers
Mismatch
Signal strength
5.3 Given a scenario, troubleshoot common issues with network services.
Switching issues
Incorrect VLAN assignment
ACLs
Route selection
Routing table
Incorrect default gateway
Incorrect IP address
Duplicate IP address
Incorrect subnet mask
5.4 Given a scenario, troubleshoot common performance issues.
Congestion/contention
Bottlenecking
Bandwidth
Throughput capacity
Latency
Packet loss
Jitter
Wireless
Interference
Channel overlap
Signal degradation or loss
Insufficient wireless coverage
Client disassociation issues
Roaming misconfiguration

Exam Essentials
Know the seven troubleshooting steps, in order.    The steps, in order, are as follows:

Identify the problem.
Establish a theory of probable cause.
Test the theory to determine a cause.
Establish a plan of action to resolve the problem and identify potential effects.
Implement the solution or escalate as necessary.
Verify full system functionality and implement preventative measures if applicable.
Document findings, actions, outcomes, and lessons learned throughout the process.
Be able to identify a link light.   A link light is the small, usually green LED on the back of a network card. This LED is typically found next to the media connector on a NIC and is usually labeled Link.

Understand how proper network use procedures can affect the operation of a network.   If a user is not following a network use procedure properly (for example, not logging in correctly), that user may report a problem where none exists. A good network troubleshooter should know how to differentiate between a network hardware/software problem and a “lack of user training” problem.

Know how to narrow down a problem to one specific area or cause.   Most problems can be traced to one specific area or cause. You must be able to determine if a problem is specific to one user or a bunch of users, specific to one computer or a bunch of computers, and related to hardware or software. The answers to these questions will give you a very specific problem focus.

Know how to detect cabling-related problems.   Generally speaking, most cabling-related problems can be traced by plugging the suspect workstation into a known, working network port. If the problem disappears (or at the very least changes significantly), it is related to the cabling for that workstation.

## Chapter 19

5.5 Given a scenario, use the appropriate tool or protocol to solve networking issues.
Software tools
Protocol analyzer
Command line
ping
traceroute/tracert
nslookup
tcpdump
dig
netstat
ip/ifconfig/ipconfig
arp
Nmap
Link Layer Discovery Protocol (LLDP)/Cisco Discovery Protocol (CDP)
Speed tester
Hardware tools
Toner
Cable tester
Taps
Wi-Fi analyzer
Visual fault locator
Basic networking device commands
show mac-address-table
show route
show interface
show config
show arp
show vlan
show power

## Chapter 20

Domain 4.0 Network Security
4.1 Explain the importance of basic network security concepts.
Logical security
Encryption
Data in transit
Data at rest
Certificates
Public key infrastructure (PKI)
Self-signed
Identity and access management (IAM)
Authentication
Multifactor authentication (MFA)
Single sign-on (SSO)
Remote Authentication Dial-in User Service (RADIUS)
LDAP
Security Assertion Markup Language (SAML)
Terminal Access Controller Access Control System Plus (TACACS+)
Time-based authentication
Authorization
Least privilege
Role-based access control
Risk
Vulnerability
Exploit
Threat
Confidentiality, Integrity, and Availability (CIA) triad
Audits and regulatory compliance
Data locality
Payment Card Industry Data Security Standards (PCI DSS)
General Data Protection Regulation (GDPR)

Exam Essentials
Know the CIA triad and how it applies to information security.    The CIA triad consists of the three concepts of confidentiality, integrity, and availability. Confidentiality defines how data is secured. Integrity defines how data is protected from unauthorized altering. Availability defines how data in systems is kept available to users and outages are avoided.

Understand the various security concepts.    A threat can be internal or external to your organization. A threat is the opportunity for a security event. Risk is the potential that a threat can occur. A vulnerability is a weakness in security. The Common, Vulnerabilities, and Exposures (CVE) is a standardized cataloging system for vulnerabilities across all vendors. Exploits are code or techniques that can be carried out upon a vulnerability.

Know the two basic types of encryptions.    Symmetric encryption uses the same key as used to decrypt the information. Asymmetrical encryption uses a key pair: One key is used to encrypt, and the other is used to decrypt.

Understand how PKI is used to protect information.    PKI uses asymmetrical key encryption to protect information by signing documents for integrity. PKI can also be used to encrypt documents for the purpose of confidentiality.

Identify common authentication methods.    These include multifactor methods, Terminal Access Controller Access-Control System Plus (TACACS+), single sign-on (SSO), Remote Authentication Dial-In User Service (RADIUS), and LDAP.

Understand the various authorization concepts.    Identity and access management (IAM) is a security framework. The principle of least privilege defines that an employee is given only the access required to perform their duties. Role-based access is the technique of combining privileges together for common roles in an organization.

## Chapter 21

Domain 4.0 Network Security
4.1 Explain the importance of basic network security concepts.
Physical security
Camera
Locks
Deception technologies
Honeypot
Honeynet
Network segmentation enforcement
Internet of Things (IoT) and Industrial Internet of Things (IIoT)
Supervisory control and data acquisition (SCADA), industrial control System (ICS), operational technology (OT)
Guest
Bring your own device (BYOD)
4.2 Summarize various types of attacks and their impact to the network.
Denial-of-service (DoS)/
distributed denial-of-service
(DDoS)
VLAN hopping
Media Access Control (MAC)
Flooding
Address Resolution Protocol
(ARP) poisoning
ARP spoofing
DNS poisoning
DNS spoofing
Rogue devices and services
DHCP
AP
Evil twin
On-path attack
Social engineering
Phishing
Dumpster diving
Shoulder surfing
Tailgating
Malware
4.3 Given a scenario, apply network security features, defense techniques, and solutions.
Device hardening
Disable unused ports and services
Change default passwords
Network access control (NAC)
Port security
802.1X
MAC filtering
Key management
Security rules
Access control list (ACL)
Uniform Resource Locator (URL) filtering
Content filtering
Zones
Trusted vs. untrusted
Screened subnet

Exam Essentials
Explain common technology-based attacks.    These include denial-of-service (DoS)/distributed denial-of-service (DDoS) attacks, on-path attacks, DNS poisoning, VLAN hopping, ARP spoofing, rogue DHCP and rogue access point (AP) attacks, evil twin attacks, ransomware, and password attacks.

Identify human and environmental attacks.    These include social engineering, phishing, tailgating, piggybacking, and shoulder surfing.

Understand the various methods of hardening network systems.    Changing default credentials for network systems will thwart brute-force attacks against default usernames. Disabling unused services on a network system reduces the area of attack by reducing the number of services that are potentially vulnerable. Access control lists (ACLs) consist of conditions and actions to control traffic for applications.

Know the various techniques of implementing network segmentations.    Screened subnets, 802.1X, NAC, and port security are just a few of the many tactics used for network segmentation covered in this chapter. You should review the various techniques listed in this chapter.

Know the various tactics used for physical security.    Video surveillance can be deployed as a coaxial network called closed-circuit television (CCTV) or Ethernet. Using locks prevent equipment from being affected by malicious intent, mistakenly being affected, or stolen. Locking doors and cabinets safeguards against snooping employees or attackers looking for files or equipment.