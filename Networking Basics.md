# **DEFINITION**

A computer network, also known as a data network, is a telecommunications network that enables computers to exchange data.

A network consists of a group of computers (two or more) and other devices connected through cable media or wireless media, allowing them to share data.

Devices in the network that initiate, direct, or receive data are referred to as network nodes.
Nodes may include hosts like personal computers, phones, servers, as well as networking hardware, and each node possesses a unique address.

# **PROPERTIES**

Devices on a network that begin, route, or receive data are called network nodes.
Network nodes can be hosts such as personal computers, phones, servers, or networking hardware, with each node having its own unique address.

**Basic Components of a Computer Network:**

1. Work Stations – Computers;
2. Network Interface Card (NIC);
3. Connecting Media:
4. Shared Resources (Printers etc.);
5. Network Protocols.

Network computers require Network Interface Cards (NICs), which are installed hardware components that enable connection to other computers.
These computers must be connected through some form of connecting media, which can be either cables such as copper wires or light pulses, or wireless methods like radio waves.
A Network Protocol serves as the language—a set of rules—for exchanging information over network links that all hosts on the network understand; an example of this is the Internet Protocol (IP).

# **CLASIFICATION**

Computer networks are classified based on various factors. They include:

| Classification Factor                 | Examples                     |
| ------------------------------------- | ---------------------------- |
| Architecture / Host Role              | Peer-to-Peer, Client/Server  |
| Geographical Span                     | PAN, LAN, MAN, WAN           |
| Topology / Inter-connectivity         | Bus, Star, Ring, Tree        |
| Organizational Scope / Administration | Intranet, Extranet, Internet |

There are two major types of network architectures:
**Peer-to-Peer** connects computers with each other without the need for an intermediary computer. It’s a simple, inexpensive network that typically connects fewer than 10 computers. All computers in the network have equal capabilities to use the resources (hardware, software, data and file) available on the network. There is no central server.

**Client / Server model** relies on a server to act as an intermediary between the network computers. One computer act as a server that provides services and the other computers (clients) on the network request services from the server.

A **server** is a computer that controls access to the hardware, software and other resources on the network and provides a centralized storage area for program.
A **client** is a computer that requests services from a server computer

| **Client/Server**                                       | **Peer-to-Peer**                                 |
| ------------------------------------------------------- | ------------------------------------------------ |
| Server has control ability; clients do not              | All computers have equal ability                 |
| Higher cabling cost                                     | Cheaper cabling cost                             |
| Used in small and large networks                        | Normally used in small networks (< 10 computers) |
| Easy to manage                                          | Hard to manage                                   |
| Software installed only on the server; clients share it | Software must be installed on every computer     |
| One powerful computer acts as server                    | No server is needed                              |

# **GEOGRAPHICAL SPAN**

**Personal Area Network (PAN)** is a personal computer network used for communication among computer and different information technological devices close to one person. This may include Bluetooth enabled devices or infra-red enabled devices (phone, wireless computer keyboard and mouse, Bluetooth enabled headphones, wireless printers and TV remotes). PAN has connectivity range up to 10 meters.

**Local Area Network (LAN)** is a short-distance network that connects computers and devices in a limited geographical area such as a home, school, office building, or closely positioned group of buildings. It connects computers usually within a room or a building. Very rarely, a LAN network will span a couple of buildings. An example of a LAN network is the network in a school or an office building. A LAN network doesn’t need a router to operate. It mostly operates on private IP addresses and does not involve heavy routing. LAN works under its own local domain and controlled centrally. LAN uses either Ethernet or Token-ring technology. Ethernet is most widely employed LAN technology and uses Star topology, while Token-ring is rarely seen. LAN can be wired, wireless, or in both forms at once.

**Metropolitan Area Network (MAN)** generally spanned across a whole city such as cable TV network. It can be in the form of Ethernet, Token-ring, ATM … Backbone of MAN is high-capacity and high-speed fiber optics. MAN works in between Local Area Network and Wide Area Network.

**Wide Area Network (WAN)** covers a huge geographical area which may span across provinces and even a whole country. A WAN is a collection of LAN networks. LANs connect to other LANs with the help of a router. The router has a LAN address and a WAN address, which lets it send data to the desired location. The biggest WAN in the world is, of course, the Internet. WANs are different from LANs in that they’re not owned by a single person/organization. They also use different technology that enables them to communicate over long distances, like Frame Relay and ATM. Since they are equipped with very high speed backbone, WANs use very expensive network equipment.

**Virtual Private Networks (VPN)** are very important today. They let you connect to your network from a remote location through the Internet. This saves you time and money- you don’t need to set up a physical connection with your network. The Internet acts as a medium between you and your network. For example, you can access your computer at work through your computer at home.

**NETWORK TOPOLOGY/INTER-CONNECTIVITY**

A network topology describes how computer systems or network devices are interconnected, either physically or logically, within a network.​Topology can define the specific pattern or structure of these connections, showing both the arrangement of cables (physical) and the flow of data (logical).​The actual geographic placement of network devices is usually less important than the way network nodes are linked, which is why network diagrams typically represent topological connections with symbols for nodes and links.​The chosen topology influences how information is exchanged among devices within the network.​

A network topology describes how computer systems or network devices are interconnected, either physically or logically, within a network.​
Different types are:

1. Point-to-Point;
2. Bus Topology;
3. Star Topology;
4. Ring Topology;
5. Mesh Topology;
6. Tree Topology;
7. Daisy Chain;
8. Hybrid Topology.

**Point-to-point** networks contains exactly two hosts such as computer, switches or routers, servers connected back to back using a single piece of cable. Often, the receiving end of one host is connected to sending end of the other and vice-versa. If the hosts are connected point-to-point logically, then may have multiple intermediate devices. But the end hosts are unaware of underlying network and see each other as if they are connected directly.

In case of **Bus topology**, all devices share single communication line or cable. Bus topology may have problem while multiple hosts sending data at the same time. Therefore, Bus topology either uses CSMA/CD technology or recognizes one host as Bus Master to solve the issue. It is one of the simple forms of networking where a failure of a device does not affect the other devices. But failure of the shared communication line can make all other devices stop functioning. Both ends of the shared channel have line terminator. The data is sent in only one direction and as soon as it reaches the extreme end, the terminator removes the data from the line.

All hosts in **Star topology** are connected to a central device, known as hub device, using a point-to-point connection. That is, there exists a point to point connection between hosts and hub. The hub device can be any of the following:
• Layer-1 device such as hub or repeater
• Layer-2 device such as switch or bridge
• Layer-3 device such as router or gateway

As in Bus topology, hub acts as single point of failure. If hub fails, connectivity of all hosts to all other hosts fails. Every communication between hosts, takes place through only the hub. Star topology is not expensive as to connect one more host, only one cable is required and configuration is simple.

In **ring topology**, each host machine connects to exactly two other machines, creating a circular network structure. When one host tries to communicate or send message to a host which is not adjacent to it, the data travels through all intermediate hosts. To connect one more host in the existing structure, the administrator may need only one more extra cable. Failure of any host results in failure of the whole ring. Thus, every connection in the ring is a point of failure. There are methods which employ one more backup ring.

In **Mesh type** of topology, a host is connected to one or multiple hosts. This topology has hosts in point-to-point connection with every other host or may also have hosts which are in point-to-point connection to few hosts only.
Hosts in Mesh topology also work as relay for other hosts which do not have direct point-to-point links. Mesh technology comes into two types:
_Full Mesh_: All hosts have a point-to-point connection to every other host in the network. Thus for every new host n(n-1)/2 connections are required. It provides the most reliable network structure among all network topologies.
_Partially Mesh_: Not all hosts have point-to-point connection to every other host. Hosts connect to each other in some arbitrarily fashion. This topology exists where we need to provide reliability to some hosts out of all.

**Tree topology**, also known as Hierarchical Topology, this is the most common form of network topology in use presently. This topology imitates as extended Star topology and inherits properties of bus topology.This topology divides the network in to multiple levels/layers of network. Mainly in LANs, a network is bifurcated into three types of network devices. The lowermost is access-layer where computers are attached. The middle layer is known as distribution layer, which works as mediator between upper layer and lower layer. The highest layer is known as core layer, and is central point of the network, i.e. root of the tree from which all nodes fork. All neighboring hosts have point-to-point connection between them. Similar to the Bus topology, if the root goes down, then the entire network suffers even though it is not the single point of failure. Every connection serves as point of failure, failing of which divides the network into unreachable segment.

**Daisy Chain**, this topology connects all the hosts in a linear fashion. Similar to Ring topology, all hosts are connected to two hosts only, except the end hosts. Means, if the end hosts in daisy chain are connected then it represents Ring topology. Each link in daisy chain topology represents single point of failure. Every link failure splits the network into two segments.Every intermediate host works as relay for its immediate hosts.

A network structure whose design contains more than one topology is said to be **hybrid topology**. Hybrid topology inherits merits and demerits of all the incorporating topologies. The combining topologies may contain attributes of Star, Ring, Bus, and Daisy-chain topologies. Most WANs are connected by means of Dual-Ring topology and networks connected to them are mostly Star topology networks. Internet is the best example of largest Hybrid topology.

# **ADMINISTRATION**

From an administrator’s point of view, a network can be private network which belongs a single autonomous system and cannot be accessed outside its physical or logical domain. A network can be public which is accessed by all.

An **intranet** is a set of networks that are under the control of a single administrative entity. The intranet uses the IP protocol and IP-based tools such as web browsers and file transfer applications. The administrative entity limits use of the intranet to its authorized users. Most commonly, an intranet is the internal LAN of an organization. A large intranet typically has at least one web server to provide users with organizational information. An intranet is also anything behind the router on a local area network.

An **extranet** is a network that is also under the administrative control of a single organization, but supports a limited connection to a specific external network. For example, an organization may provide access to some aspects of its intranet to share data with its business partners or customers. These other entities are not necessarily trusted from a security standpoint. Network connection to an extranet is often, but not always, implemented via WAN technology.

An **internetwork** is the connection of multiple computer networks via a common routing technology using routers.

**The Internet** is the largest example of an internetwork. It is a global system of interconnected governmental, academic, corporate, public, and private computer networks. It is based on the networking technologies of the Internet Protocol Suite. It is the successor of the Advanced Research Projects Agency Network (ARPANET) developed by DARPA of the United States Department of Defense. The Internet is also the communications backbone underlying the World Wide Web (WWW). Participants in the Internet use a diverse array of methods of several hundred documented, and often standardized, protocols compatible with the Internet Protocol Suite and an addressing system (IP addresses) administered by the Internet Assigned Numbers Authority andaddress registries. Service providers and large enterprises exchange information about the reachability of their address spaces through the Border Gateway Protocol (BGP), forming a redundant worldwide mesh of transmission paths.

A **Darknet** is an overlay network, typically running on the internet, that is only accessible through specialized software. A darknet is an anonymizing network where connections are made only between trusted peers — sometimes called "friends" — using non-standard protocols and ports. Darknets are distinct from other distributed peer-to-peer networks as sharing is anonymous (that is, IP addresses are not publicly shared), and therefore users can communicate with little fear of governmental or corporate interference.

# **COMPUTER NETWORK MODEL**

To ease network engineering, the whole networking concept is divided into multiple layers. Each layer is involved in some particular task and is independent of all other layers. But as a whole, almost all networking tasks depend on all of these layers. Layers share data between them and they depend on each other only to take input and send output.

Open System Interconnect (OSI) model established by International Standard Organization (ISO) is a standard reference model for communication between two end users in a network.This model has seven layers. Each layer is functionally independent of the others, but provides services to the layer above it and receives services from the layer below it.

The layers are in two groups:
-The upper four layers are used whenever a message passes from or to a user.
-The lower three layers are used when any message passes through the host computer. Messages intended for this computer pass to the upper layers. Messages destined for some other host are not passed up to the upper layers but are forwarded to another host.

**Layer 1 - Physical Layer:** This layer defines the hardware, cabling, wiring, power output, pulse rate etc. (Media, signal and binary transmission.)This layer transmits bits from one computer to another and regulates the transmission of a stream of bits over a physical medium. This layer defines how the cable is attached to the network adapter and what transmission technique is used to send data over the cable.

**Layer 2 – Data Link Layer:** This layer is responsible for reading and writing data from and onto the line. Link errors are detected at this layer. (Physical addressing – Ethernet, VLAN…; MAC addresses). This layer package raw bit from the Physical layer into frames (logical, structures packets for data). It is responsible for transferring frames from one computer to another, without errors. After sending a frame, it waits for an acknowledgment from the receiving computer.

**Layer 3 - Network Layer:** This layer is responsible for address assignment and uniquely addressing hosts in a network. (Logical addressing - IP, path determination / routing - ARP). This layer handles the routing of the data, addresses messages and translates logical addresses and names into physical addresses. It also determines the route from the source to the destination computer and manages traffic problems (flow control), such as switching, routing, and controlling the congestion of data packets.

**Layer 4 - Transport Layer:** This layer is responsible for end-to-end delivery between hosts (TCP, UDP, SPX…).
This layer handles error recognition and recovery, manages the end-to-end control (for example, determining whether all packets have arrived) and error-checking. It ensures complete data transfer.

**Layer 5 - Session Layer:** This layer maintains sessions between remote hosts (logical ports). This layer allows applications on different computers to establish, use, and end a session/connection. Establishes dialog control between the two computers in a session, regulating which side transmits, and when and how long it transmits.

**Layer 6 - Presentation Layer:** This layer defines how data in the native format of remote host should be presented in the native format of host (Syntax layer – encrypt and decrypt; HTML, doc, jpeg, gif …). This is a layer, usually part of an operating system, that converts incoming and outgoing data from one presentation format to another (for example, from a text stream into a popup window with the newly arrived text). This layer also manages security issues by providing services such as data encryption and compression. It’s sometimes called the syntax layer.

**Layer 7 - Application Layer:** This layer is responsible for providing interface to the application user. This layer encompasses protocols which directly interact with the user (End User Layer - DNS, HTTP, …). This is the layer at which communication partners are identified, quality of service is identified, user authentication and privacy are considered, and any constraints on data syntax are identified. (This layer is not the application itself, although some applications may perform application layer functions). It represents the services that directly support applications such as software for file transfers, database access, email, and network games.

The low layers (1, 2, 3 and 4) are necessary to the routing of information between the two concerned ends and depend on the physical medium. The higher layers (5, 6 and 7) are responsible for the data processing relative to the management of exchanges between information processing systems. In addition, layers 1 to 3 intervene between close machines, but not between ending machines that can be separated by several routers. On the contrary, layers 4 to 7 intervene only between distant hosts.

# **Internet Model / The Internet Protocol Suite**

The Internet Protocol Suite is the computer networking model and set of communications protocols used on the Internet and similar computer networks. It is commonly known as TCP/IP, because its most important protocols, the Transmission Control Protocol (TCP) and the Internet Protocol (IP) were the first networking protocols defined during its development. It is occasionally known as the Department of Defense (DoD) model, because the development of the networking model was funded by DARPA, an agency of the United States Department of Defense. TCP/IP provides end-to-end data communication specifying how data should be packetized, addressed, transmitted, routed and received. This functionality is organized into four abstraction layers which are used to sort all related protocols according to the scope of networking involved.

From lowest to highest, the layers are:

1. **The Link Layer:** This layer provides mechanism of sending and receiving actual data. Unlike its OSI
   Model counterpart, this layer is independent of underlying network architecture and hardware.
   It contains communication methods for data that remains within a single network segment (link);
2. **The Internet Layer:** This layer facilitates host addressing and recognition - Internet Protocol (IP) works on this layer. This layer defines routing.
   It connects independent networks, thus providing internetworking;
3. **The Transport Layer:** This layer defines how data should flow between hosts. Major protocol at this layer is Transmission Control Protocol (TCP). This layer ensures data delivered between hosts is in order and is responsible for end-to-end delivery.
4. **The Application Layer:** This layer defines the protocol which enables user to interact with the network. For example, FTP, HTTP etc.

Internet uses TCP/IP protocol suite, also known as Internet suite. This defines Internet Model which contains four layered architecture. OSI Model is general communication model but Internet Model is what the internet uses for all its communication. The internet is independent of its underlying network architecture so is its Model.

# **TYPES OF NETWORK MEDIA**

The transmission media (often referred to in the literature as the physical media) used to link devices to form a computer network include:

1. Electrical cable (Ethernet, HomePNA, power line communication, G.hn),
2. Optical fiber (fiber-optic communication), and
3. Radio waves (wireless networking).

In the OSI model, these are defined at layers 1 and 2 - the physical layer and the data link layer.
A widely adopted family of transmission media used in local area network (LAN) technology is collectively known as Ethernet. The media and protocol standards that enable communication between networked devices over Ethernet are defined by IEEE 802.3. Ethernet transmits data over both copper and fiber cables. Wireless LAN standards (e.g. those defined by IEEE 802.11) use radio waves, or others use infrared signals as a transmission medium. Power line communication uses a building's power cabling to transmit data.

**WIRED TECHNOLOGIES**

The orders of the following wired technologies are, roughly, from slowest to fastest transmission speed.

**COAXIAL CABLE** - Most users relate to a coaxial or coax cable as a cable used to connect their TVs to a cable TV service. However, these cables are also used in networks and allow a broadband cable Internet connection using a cable modem. The cables consist of copper or aluminum wire (core) surrounded by an insulating layer (typically a flexible material), which itself is surrounded by a conductive layer. The insulation helps minimize interference and distortion. Transmission speed ranges from 200 million bits per second to more than 500 million bits per second.

_Types:_

1. RG-58/U is a type of coaxial cable that was once widely used in "thin" Ethernet (10BASE2), for which it provides a maximum segment length of 185 meters. They are using BNC connectors (T-connector and terminator). However, it has been almost completely replaced by twisted-pair cabling such as Cat 5, Cat 6, and similar cables in data networking applications.
2. RG-59 - cable TV;
3. RG-6 - used with cable TV and satellite;
4. RG-8 - used as a backbone in 10BASE5 network.
   Advantages:

- Resistant to a electro-magnetic interference (EMI);
- Resistant to physical damages (flexible).
  Disadvantages:
- More expensive;
- Not supported anymore by fast network standards.

**Twisted pair wire** is the most widely used medium for all telecommunication. Twisted-pair cabling consist of copper wires that are twisted into pairs. Ordinary telephone wires consist of two insulated copper wires twisted into pairs. Computer network cabling (wired Ethernet as defined by IEEE 802.3) consists of 4 pairs of copper wiring that can be utilized for both voice and data transmission. The use of two wires twisted together helps to reduce crosstalk and electromagnetic induction. The transmission speed ranges from 2 million bits per second to 10 billion bits per second. Twisted pair cabling comes in two forms: unshielded twisted pair (UTP) and shielded twisted-pair (STP). Each form comes in several category ratings, designed for use in various scenarios.

_UTP Categories:_

1. Cat 1 (Telephone cables; RJ-11 connector);
2. Cat 3 (10 - 60 Mbps; 10BASE-T);
3. Cat 4 (16 Mbps; Token Ring);
4. Cat 5 (100 - 1000 Mbps; 100BASE-T (Fast Ethernet); terminated by a RJ-45 connector);
5. Cat 5e (1000 Mbps - );
6. Cat 6.

Advantages:

- Very flexible;
- Very easy to work with;
- Extremely inexpensive;
- Modern standards support it.
  Disadvantages:
- Susceptible to EMI;
- They absorb signals very easy and also radiate them.

An **optical fiber** is a glass fiber. It carries pulses of light that represent data. Optical fibers can simultaneously carry multiple wave lengths of light, which greatly increases the rate that data can be sent, and helps enable data rates of up to trillions of bits per second. Some advantages of optical fibers over metal wires are very low transmission loss and immunity from electrical interference. Optic fibers can be used for long runs (2 - 100 km) of cable carrying very high data rates (100 Mbps - 1 Gbps), and are used for undersea cables to interconnect continents.

Disadvantages: Very expensive; not flexible.
Types: single mode (single ray); multimode (multiple rays).

Price is a main factor distinguishing wired and wireless technology options in a business. Wireless options command a price premium that can make purchasing wired computers, printers and other devices a financial benefit. Before making the decision to purchase hard-wired technology products, a review of the restrictions and limitations of the selections is necessary. Business and employee needs may override any cost considerations.

**WIRELESS TECHNOLOGIES**

Computers are very often connected to networks using wireless links.

Terrestrial microwave – Terrestrial microwave communication uses Earth-based transmitters and receivers resembling satellite dishes. Terrestrial microwaves are in the low-gigahertz range, which limits all communications to line-of-sight. Relay stations are spaced approximately 48 km (30 mi) apart.

Communications satellites – Satellites communicate via microwave radio waves, which are not deflected by the Earth's atmosphere. The satellites are stationed in space, typically in geosynchronous orbit 35,400 km (22,000 mi) above the equator. These Earth-orbiting systems are capable of receiving and relaying voice, data, and TV signals.

Cellular and PCS systems use several radio communications technologies. The systems divide the region covered into multiple geographic areas. Each area has a low-power transmitter or radio relay antenna device to relay calls from one area to the next area.

Radio and spread spectrum technologies – Wireless local area networks use a high-frequency radio technology similar to digital cellular and a low-frequency radio technology. Wireless LANs use spread spectrum technology to enable communication between multiple devices in a limited area. IEEE 802.11 defines a common flavor of open-standards wireless radio-wave technology known as Wifi.

Free-space optical communication uses visible or invisible light for communications. In most cases, line-of-sight propagation is used, which limits the physical positioning of communicating devices.

**NETWORK NODES/DEVICES**

Apart from any physical transmission medium there may be, networks comprise additional basic system building blocks, such as network interface controller (NICs), repeaters, hubs, bridges, switches, routers, modems, and firewalls.

**A network interface controller (NIC)** is computer hardware that provides a computer with the ability to access the transmission media, and has the ability to process low-level network information. For example, the NIC may have a connector for accepting a cable, or an aerial for wireless transmission and reception, and the associated circuitry. The NIC responds to traffic addressed to a network address for either the NIC or the computer as a whole. In Ethernet networks, each network interface controller has a unique Media Access Control (MAC) address usually stored in the controller's permanent memory. To avoid address conflicts between network devices, the Institute of Electrical and Electronics Engineers (IEEE) maintains and administers MAC address uniqueness. The size of an Ethernet MAC address is six octets. The three most significant octets are reserved to identify NIC manufacturers. These manufacturers, using only their assigned prefixes, uniquely assign the three least-significant octets of every Ethernet interface they produce.

A **repeater** is an electronic device that receives a network signal, cleans it of unnecessary noise and regenerates it. The signal is retransmitted at a higher power level, or to the other side of an obstruction, so that the signal can cover longer distances without degradation. In most twisted pair Ethernet configurations, repeaters are required for cable that runs longer than 100 meters. With fiber optics, repeaters can be tens or even hundreds of kilometers apart. A repeater with multiple ports is known as a **hub**. Repeaters work on the physical layer of the OSI model. Repeaters require a small amount of time to regenerate the signal. This can cause a propagation delay that affects network performance. As a result, many network architectures limit the number of repeaters that can be used in a row, e.g., the Ethernet 5-4-3 rule. Hubs have been mostly obsoleted by modern switches; but repeaters are used for long distance links, notably undersea cabling.

A **network bridge** connects and filters traffic between two network segments at the data link layer (layer 2) of the OSI model to form a single network. This breaks the network's collision domain but maintains a unified broadcast domain. Network segmentation breaks down a large, congested network into an aggregation of smaller, more efficient networks.
Bridges come in three basic types:
-Local bridges: Directly connect LANs;
-Remote bridges: Can be used to create a wide area network (WAN) link between LANs. Remote bridges, where the connecting link is slower than the end networks, largely have been replaced with routers.
-Wireless bridges: Can be used to join LANs or connect remote devices to LANs.

A **network switch** is a device that forwards and filters OSI layer 2 datagrams (frames) between ports based on the destination MAC address in each frame. A switch is distinct from a hub in that it only forwards the frames to the physical ports involved in the communication rather than all ports connected. It can be thought of as a multi-port bridge. It learns to associate physical ports to MAC addresses by examining the source addresses of received frames. If an unknown destination is targeted, the switch broadcasts to all ports but the source. Switches normally have numerous ports, facilitating a star topology for devices, and cascading additional switches.
Multi-layer switches are capable of routing based on layer 3 addressing or additional logical levels. The term switch is often used loosely to include devices such as routers and bridges, as well as devices that may distribute traffic based on load or based on application content (e.g., a Web URL identifier).

A **router** is an internetworking device that forwards packets between networks by processing the routing information included in the packet or datagram (Internet protocol information from layer 3). Routers can analyze the data being sent over a network, change how it is packaged, and send it to another network or over a different network. The routing information is often processed in conjunction with the routing table (or forwarding table). A router uses its routing table to determine where to forward packets. A destination in a routing table can include a "null" interface, also known as the "black hole" interface because data can go into it, however, no further processing is done for said data, i.e. the packets are dropped.

**WAP** is a networking hardware device that allows a Wi-Fi compliant device to connect to a wired network. The WAP usually connects to a router (via a wired network) as a standalone device, but it can also be an integral component of the router itself. A WAP is differentiated from a hotspot, which is the physical location where Wi-Fi access to a WLAN is available.

**Modems** (MOdulator-DEModulator) are used to connect network nodes via wire not originally designed for digital network traffic, or for wireless. To do this one or more carrier signals are modulated by the digital signal to produce an analog signal that can be tailored to give the required properties for transmission. Modems are commonly used for telephone lines, using a Digital Subscriber Line technology.

A **firewall** is a network device for controlling network security and access rules. Firewalls are typically configured to reject access requests from unrecognized sources while allowing actions from recognized ones. The vital role firewalls play in network security grows in parallel with the constant increase in cyber attacks.

# **DIFFERENCES BETWEEN A NETWORK HUB, SWITCH, AND ROUTER?**

There are three main devices that work to connect one computer to another computer. A network hub, switch, and router can all perform this function. It can sometimes be confusing when trying to figure out what device is currently being used on a computer network, without knowing what each device does.

**Network Hub**
A network hub is designed to connect computers to each other with no real understanding of what it is transferring. Typically, a network hub is used for a private network, one that does not have any connections to sources other than local computers (meaning, no Internet access). When a hub receives a packet of data from a connected device, it broadcasts that data packet to all other connected devices regardless of which one ends up being the final destination. Additionally, network bandwidth is split between all of the connected computers. (Bandwidth, communication speed, or connection speed is the total maximum transfer rate of a network cable or device. Essentially, it is a measurement of how fast data can be sent over a wired or wireless connection, usually measure in bits per second.)
So, the more computer that are connected, the less bandwidth that is available for each computer, which means slower connection speeds.
In the past network switches and routers were expensive, confusing, and hard to use for most users and most opted for network hubs. Today, home network switches and routers are much easier to use and cheaper, which is why network hubs are rarely used or found anymore.

**Network Switch**
A network switch also connects computers to each other, like a hub. Where the switch differs from a hub is in the way it handles packets of data. When a switch receives a packet of data, it determines what computer or device the packet is intended for and sends it to that computer only. It does not broadcast the packet to all computers as a hub does which means bandwidth is not shared and makes the network much more efficient. For this reason alone, switches are usually preferred over a hub.

**Network Router**
A network router is quite different from a switch or hub since its primary function is to route data packets to other networks, instead of just the local computers. A router is quite common to find in homes and businesses since it allows your network to communicate with other networks including the Internet. Essentially, a router bridges the gap between other networks and gives your network access to more features, e.g. a firewall, QoS, traffic monitoring, VPN, and more.

# **COMMUNICATIONS PROTOCOLS**

A communications protocol is a set of rules for exchanging information over network links. In a protocol stack each protocol leverages the services of the protocol below it. An important example of a protocol stack is HTTP (the World Wide Web protocol) running over TCP over IP (the Internet protocols) over IEEE 802.11 (the Wi-Fi protocol). This stack is used between the wireless router and the home user's personal computer when the user is surfing the web. Communication protocols have various characteristics. They may be connection-oriented or connectionless, they may use circuit mode or packet switching, and they may use hierarchical addressing or flat addressing. There are many communication protocols, a few of which are described below.

**IEEE 802** refers to a family of IEEE standards dealing with local area networks and metropolitan area networks. More specifically, the IEEE 802 standards are restricted to networks carrying variable-size packets. The number 802 was simply the next free number IEEE could assign, though “802” is sometimes associated with the date the first meeting was held — February 1980. The complete IEEE 802 protocol suite provides a diverse set of networking capabilities. The protocols have a flat addressing scheme. They operate mostly at levels 1 and 2 of the OSI model. The most widely used standards are for the Ethernet family, Token Ring, Wireless LAN, Bridging and Virtual Bridged LANs.

# **NETWORK LAN TECHNOLOGIES**

**Ethernet**, sometimes simply called LAN, is a family of protocols used in wired LANs, described by a set of standards together called IEEE 802.3 published by the Institute of Electrical and Electronics Engineers.
Ethernet is a family of computer networking technologies commonly used in local area networks (LANs) and metropolitan area networks (MANs). It was commercially introduced in 1980 and first standardized in 1983 as IEEE 802.3, and has since been refined to support higher bit rates and longer link distances. Over time, Ethernet has largely replaced competing wired LAN technologies such as Token Ring, FDDI and ARCNET. The original 10BASE5 Ethernet uses coaxial cable as a shared medium, while the newer Ethernet variants use twisted pair and fiber optic links in conjunction with hubs or switches. Traditional Ethernet uses 10BASE-T specifications. The number 10 depicts 10MBPS speed, BASE stands for baseband, and T stands for Thick Ethernet. 10BASE-T Ethernet provides transmission speed up to 10MBPS and uses coaxial cable or Cat-5 twisted pair cable with RJ-5 connector. Ethernet follows Star topology with segment length up to 100 meters. All devices are connected to a hub/switch in a star fashion. The Ethernet standards comprise several wiring and signaling variants of the OSI physical layer in use with Ethernet. Systems communicating over Ethernet divide a stream of data into shorter pieces called frames. Each frame contains source and destination addresses, and error-checking data so that damaged frames can be detected and discarded; most often, higher-layer protocols trigger retransmission of lost frames. As per the OSI model, Ethernet provides services up to and including the data link layer. Since its commercial release, Ethernet has retained a good degree of backward compatibility. Features such as the 48-bit MAC address and Ethernet frame format have influenced other networking protocols. The primary alternative for some uses of contemporary LANs is Wi-Fi, a wireless protocol standardized as IEEE 802.11. Over the course of its history, Ethernet data transfer rates have been increased from the original 2.94 megabits per second (Mbit/s) to the latest 100 gigabits per second (Gbit/s), with 400 Gbit/s expected by late 2017.

To encompass need of fast emerging software and hardware technologies, Ethernet extends itself as **Fast-Ethernet**. It can run on UTP, Optical Fiber, and wirelessly too. It can provide speed up to 100MBPS. This standard is named as 100BASE-T in IEEE 803.2 using Cat-5 twisted pair cable. It uses CSMA/CD technique for wired media sharing among the Ethernet hosts and CSMA/CA (CA stands for Collision Avoidance) technique for wireless Ethernet LAN. Fast Ethernet on fiber is defined under 100BASE-FX standard which provides speed up to 100MBPS on fiber. Ethernet over fiber can be extended up to 100 meters in half-duplex mode and can reach maximum of 2000 meters in full-duplex over multimode fibers.

After being introduced in 1995, Fast-Ethernet retained its high speed status only for three years till **Giga-Ethernet** introduced. Giga-Ethernet provides speed up to 1000 mbits/seconds. IEEE 802.3ab standardizes Giga-Ethernet over UTP using Cat-5, Cat-5e and Cat-6 cables. IEEE802.3ah defines Giga-Ethernet over Fiber.

**Wireless LAN**, also widely known as WLAN or WiFi, is probably the most well-known member of the IEEE 802 protocol family for home users today. It is standarized by IEEE 802.11 and shares many properties with wired Ethernet. A wireless local area network (WLAN) is a wireless computer network that links two or more devices using a wireless distribution method (often spread-spectrum or OFDM radio) within a limited area such as a home, school, computer laboratory, or office building. This gives users the ability to move around within a local coverage area and still be connected to the network, and can provide a connection to the wider Internet. Most modern WLANs are based on IEEE 802.11 standards, marketed under the Wi-Fi brand name. Wireless LANs have become popular in the home due to ease of installation and use, and in commercial complexes offering wireless access to their customers; often for free. New York City, for instance, has begun a pilot program to provide city workers in all five boroughs of the city with wireless Internet access.

**LAN** uses Ethernet which in turn works on shared media. Shared media in Ethernet create one single Broadcast domain and one single Collision domain. Introduction of switches to Ethernet has removed single collision domain issue and each device connected to switch works in its separate collision domain. But even Switches cannot divide a network into separate Broadcast domains. Virtual LAN is a solution to divide a single Broadcast domain into multiple Broadcast domains. Host in one VLAN cannot speak to a host in another. By default, all hosts are placed into the same VLAN. VLAN is Layer-2 technology which works closely on Ethernet. To route packets between two different VLANs, a Layer-3 device such as Router is required.

**NETWORK LAYER PROTOCOLS**

IPv4 is 32-bit addressing scheme used as TCP/IP host addressing mechanism. IP addressing enables every host on the TCP/IP network to be uniquely identifiable. IPv4 provides hierarchical addressing scheme which enables it to divide the network into sub-networks, each with well-defined number of hosts.

IP addresses are dividedinto many categories: A, B, C, D, E. IPv4 also has well-defined address spaces to be used as private addresses (not routable on internet), and public addresses (provided by ISPs and are routable on internet).

Exhaustion of IPv4 addresses gave birth to a next generation **Internet Protocol version 6**. IPv6 addresses its nodes with 128-bit wide address providing plenty of address space for future to be used on entire planet or beyond. IPv6 has introduced Anycast addressing but has removed the concept of broadcasting. IPv6 enables devices to self-acquire an IPv6 address and communicate within that subnet. This auto-configuration removes the dependability of Dynamic Host Configuration Protocol (DHCP) servers. This way, even if the DHCP server on that subnet is down, the hosts can communicate with each other. IPv6 provides new feature of IPv6 mobility. Mobile IPv6-equipped machines can roam around without the need of changing their IP addresses. IPv6 is still in transition phase and is expected to replace IPv4 completely in coming years. At present, there are few networks which are running on IPv6. There are some transition mechanisms available for IPv6-enabled networks to speak and roam around different networks easily on IPv4.

These are:
-Dual stack implementation
-Tunneling
-NAT-PT.

It’s a protocol used by the Internet Protocol (IP), specifically IPv4, to map IP network addresses to the hardware addresses used by a data link protocol. The protocol operates below the network layer as a part of the interface between the OSI network and OSI link layer.
While communicating, a host needs Layer-2 (MAC) address of the destination machine which belongs to the same broadcast domain or network. A MAC address is physically burnt into the Network Interface Card (NIC) of a machine and it never changes. On the other hand, IP address on the public domain is rarely changed. If the NIC is changed in case of some fault, the MAC address also changes. This way, for Layer-2 communication to take place, a mapping between the two is required.

ICMP is network diagnostic and error reporting protocol. ICMP belongs to IP protocol suite and uses IP as carrier protocol. After constructing ICMP packet, it is encapsulated in IP packet. Because IP itself is a best-effort non-reliable protocol, so is ICMP. Any feedback about network is sent back to the originating host. If some error in the network occurs, it is reported by means of ICMP. ICMP contains dozens of diagnostic and error reporting messages. ICMP-echo and ICMP-echo-reply are the most commonly used ICMP messages to check the reachability of end-to-end hosts. When a host receives an ICMP-echo request, it is bound to send back an ICMP-echo-reply. If there is any problem in the transit network, the ICMP will report that problem.

**TRANSPORT LAYER PROTOCOLS**

The two main Transport Layer protocols are:

1. Transmission Control Protocol - It provides reliable communication between two hosts.
2. User Datagram Protocol - It provides unreliable communication between two hosts.

The Transmission Control Protocol (TCP) is one of the most important protocols of Internet Protocol suite. It is most widely used protocol for data transmission in communication network such as internet.

Features:
-TCP is reliable protocol. That is, the receiver always sends either positive or negative acknowledgement about the data packet to the sender, so that the sender always has bright clue about whether the data packet is reached the destination or it needs to resend it.
-TCP ensures that the data reaches intended destination in the same order it was sent.
-TCP is connection oriented. TCP requires that connection between two remote points be established before sending actual data.
-TCP provides error-checking and recovery mechanism.
-TCP provides end-to-end communication.
-TCP provides flow control and quality of service.
-TCP operates in Client/Server point-to-point mode.
-TCP provides full duplex server, i.e. it can perform roles of both receiver and sender.

**The User Datagram Protocol (UDP)** is simplest Transport Layer communication protocol available of the TCP/IP protocol suite. It involves minimum amount of communication mechanism. UDP is said to be an unreliable transport protocol but it uses IP services which provides best effort delivery mechanism. In UDP, the receiver does not generate an acknowledgement of packet received and in turn, the sender does not wait for any acknowledgement of packet sent. This shortcoming makes this protocol unreliable as well as easier on processing.

_Requirement of UDP_

A question may arise, why do we need an unreliable protocol to transport the data?
We deploy UDP where the acknowledgement packets share significant amount of bandwidth along with the actual data. For example, in case of video streaming, thousands of packets are forwarded towards its users. Acknowledging all the packets is troublesome and may contain huge amount of bandwidth wastage. The best delivery mechanism of underlying IP protocol ensures best efforts to deliver its packets, but even if some packets in video streaming get lost, the impact is not calamitous and can be ignored easily. Loss of few packets in video and voice traffic sometimes goes unnoticed.

Features:
-UDP is used when acknowledgement of data does not hold any significance.
-UDP is good protocol for data flowing in one direction.
-UDP is simple and suitable for query based communications.
-UDP is not connection oriented.
-UDP does not provide congestion control mechanism.
-UDP does not guarantee ordered delivery of data.
-UDP is stateless.
-UDP is suitable protocol for streaming applications such as VoIP, multimedia
streaming.

**APPLICATION PROTOCOLS**

There are several protocols which work for users in Application Layer. These protocols can be broadly divided into two categories:
-Protocols which are used by users (for example, e-Mail);
-Protocols which help and support protocols used by users (for example, DNS).

**The Domain Name System (DNS)** works on Client/Server model. It uses UDP protocol for transport layer communication. DNS uses hierarchical domain based naming scheme. It translates human-readable domain names like www.dyn.com into machine-readable numerical IP addresses like 204.13.248.115 needed for the purpose of locating and identifying computer services and devices with the underlying network protocols.

**The Dynamic Host Configuration Protocol** is a Client/Server protocol that automatically provides an Internet Protocol (IP) host with its IP address and other related configuration information such as the subnet mask and default gateway.

**The Simple Mail Transfer Protocol** is used to transfer electronic mail from one user to another. This task is done by means of e-mail client software (User Agents) the user is using. User Agents help the user to type and format the email and store it until internet is available. When an email is submitted to send, the sending process is handled by Message Transfer Agent which is normally comes inbuilt in email client software. Message Transfer Agent uses SMTP to forward the email to another Message Transfer Agent (Server side). While SMTP is used by end user to only send the emails, the Servers normally use SMTP to send as well as receive emails. SMTP uses TCP port number 25 and 587. Client software uses Internet Message Access Protocol (IMAP) or POP protocols to receive emails.

**The File Transfer Protocol (FTP)** is the most widely used protocol for file transfer over the network. FTP uses TCP/IP for communication and it works on TCP port 21. FTP works on Client/Server Model where a client requests file from Server and server sends requested resource back to the client. FTP uses out-of-band controlling i.e. FTP uses TCP port 20 for exchanging controlling information and the actual data is sent over TCP port 21. The client requests the server for a file. When the server receives a request for a file, it opens a TCP connection for the client and transfers the file. After the transfer is complete, the server closes the connection. For a second file, client requests again and the server reopens a new TCP connection.

**The Post Office Protocol version 3 (POP3)** is a simple mail retrieval protocol used by User Agents (client email software) to retrieve mails from mail server. When a client needs to retrieve mails from server, it opens a connection with the server on TCP port 110. User can then access his mails and download them to the local computer. POP3 works in two modes. The most common mode, the delete mode, is to delete the emails from remote server after they are downloaded to local machines. The second mode, the keep mode, does not delete the email from mail server and gives the user an option to access mails later on mail server.

**The Hyper Text Transfer Protocol (HTTP)** is the foundation of World Wide Web. Hypertext is well organized documentation system which uses hyperlinks to link the pages in the text documents. HTTP works on client server model. When a user wants to access any HTTP page on the internet, the client machine at user end initiates a TCP connection to server on port 80. When the server accepts the client request, the client is authorized to access web pages. To access the web pages, a client normally uses web browsers, who are responsible for initiating, maintaining, and closing TCP connections. HTTP is a stateless protocol, which means the Server maintains no information about earlier requests by clients.
HTTP versions:
-HTTP 1.0 uses non persistent HTTP. At most one object can be sent over a single TCP connection.
-HTTP 1.1 uses persistent HTTP. In this version, multiple objects can be sent over a sing.

# **NETWORK ADDRESSING**

Layer 3 network addressing is one of the major tasks of Network Layer. Network Addresses are always logical i.e. these are software based addresses which can be changed by appropriate configurations.
A network address always points to host / node / server or it can represent a whole network.
Network address is always configured on network interface card and is generally mapped by system with the MAC address (hardware address or layer-2 address) of the machine for Layer-2 communication.
There are different kinds of network addresses in existence: IP, IPX, AppleTalk … We are discussing IP here as it is the only one we use in practice these days.

An Internet Protocol address (IP address) is a numerical label assigned to each device (e.g., computer, printer) participating in a computer network that uses the Internet Protocol for communication. An IP address serves two principal functions: host or network interface identification and location addressing.

An IP address is defined as a 32-bit number and this system, known as Internet Protocol Version 4 (IPv4), is still in use today. However, because of the growth of the Internet and the predicted depletion of available addresses, a new version of IP (IPv6), using 128 bits for the address, was developed in 1995. IP addresses are usually written and displayed in human-readable notations, such as 172.16.254.1 (IPv4), and 2001:db8:0:1234:0:567:8:1 (IPv6). Each part represents a group of 8 bits (octet) of the address. In some cases of technical writing, IPv4 addresses may be presented in various hexadecimal, octal, or binary representations.

**SUBNETTING**

Subnet: A separate and identifiable portion of an organization's network, typically arranged on one floor, building or geographical location.

Subnet Mask: A 32-bit number used to differentiate the network component of an IP address by dividing the IP address into a network address and host address.

The address is made up of 32 binary bits, which can be divisible into a network portion and host portion with the help of a subnet mask. The 32 binary bits are broken into four octets (1 octet = 8 bits).

Each octet is converted to decimal and separated by a period (dot). For this reason, an IP address is said to be expressed in dotted decimal format (for example, 172.16.81.100).

The value in each octet ranges from 0 to 255 decimal, or 00000000 - 11111111 binary. IP addresses are limited to 32 bits in length and the maximum number of combinations of binary numbers you could have in an octet is 256 (mathematically calculated as 28). Hence, the largest IP address you could have would be 255.255.255.255, given that any one octet could be from 0 to 255.

Each IP address belongs to a class of IP addresses depending on the number in the first octet:

| Rule                                             | Minimums and Maximums            | Decimal Range |
| ------------------------------------------------ | -------------------------------- | ------------- |
| **Class A:**<br>First bit is always 0.           | 00000000 = 0<br>01111111 = 127   | 1 - 126\*     |
| **Class B:**<br>First two bits are always 10.    | 10000000 = 128<br>10111111 = 191 | 128 - 191     |
| **Class C:**<br>First three bits are always 110. | 11000000 = 192<br>11011111 = 223 | 192 - 223     |
| **Class D:**<br>First four bits are always 1110. | 11100000 = 224<br>11101111 = 239 | 224 - 239     |

-In a Class A address, the first octet is the network portion, so the Class A has a major network address of 1.0.0.0 - 127.255.255.255. Octets 2, 3, and 4 (the next 24 bits) are for the network manager to divide into subnets and hosts as he/she sees fit. Class A addresses are used for networks that have more than 65,536 hosts (actually, up to 16777214 hosts!).
-In a Class B address, the first two octets are the network portion, so the Class B has a major network address of 128.0.0.0 - 191.255.255.255. Octets 3 and 4 (16 bits) are for local subnets and hosts. Class B addresses are used for networks that have between 256 and 65534 hosts.
-In a Class C address, the first three octets are the network portion. The Class C has a major network address of 192.0.0.0 - 223.255.255.255. Octet 4 (8 bits) is for local subnets and hosts - perfect for networks with less than 254 hosts.
-Class D addresses are reserved for IP multicast addresses. The four high-order bits in a class D address are always set to binary 1 1 1 0. The remaining bits are for the address that interested hosts recognize. Microsoft supports class D addresses for applications to multicast data to multicast-capable hosts on an internetwork.
-Class E is an experimental address that is reserved for future use. The high-order bits in a class E address are set to 1111.

| Class | 1st Octet Decimal Range | 1st Octet High Order Bits | Network/Host ID                 | Default Subnet Mask | Number of Networks | Hosts per Network (Usable Addresses) |
| ----- | ----------------------- | ------------------------- | ------------------------------- | ------------------- | ------------------ | ------------------------------------ |
| A     | 1 – 126\*               | 0                         | N.H.H.H                         | 255.0.0.0           | 126                | 16,777,214                           |
| B     | 128 – 191               | 10                        | N.N.H.H                         | 255.255.0.0         | 16,382             | 65,534                               |
| C     | 192 – 223               | 110                       | N.N.N.H                         | 255.255.255.0       | 2,097,150          | 254                                  |
| D     | 224 – 239               | 1110                      | Reserved for Multicasting       | N/A                 | N/A                | N/A                                  |
| E     | 240 – 254               | 1111                      | Experimental; used for research | N/A                 | N/A                | N/A                                  |

A **network mask** helps you know which portion of the address identifies the network and which portion of the address identifies the node. Class A, B, and C networks have default masks, also known as natural masks.

IP addressing provides mechanism to differentiate between hosts and network.
Because IP addresses are assigned in hierarchical manner, a host always resides under a specific network. The host which needs to communicate outside its subnet, needs to know destination network address, where the packet/data is to be sent.
Hosts in different subnet need a mechanism to locate each other. This task can be done by DNS.
DNS is a server which provides Layer-3 address of remote host mapped with its domain name or FQDN. When a host acquires the Layer-3 Address (IP Address) of the remote host, it forwards all its packet to its gateway.
A network gateway is a network point that acts as an entrance to another network. On the Internet, a node or stopping point can be either a gateway node or a host (end-point) node. Usually a gateway node is a router equipped with all the information which leads to route packets to the destination host.

**PUBLIC AND PRIVATE IP ADDRESS**

-A public IP address is an IP address that can be accessed over the Internet. Like postal address used to deliver a postal mail to your home, a public IP address is the globally unique IP address assigned to a computing device. Your public IP address can be found at What is my IP Address page.

-Private IP address on the other hand is used to assign computers within your private space without letting them directly expose to the Internet. For example, if you have multiple computers within your home you may want to use private IP addresses to address each computer within your home. In this scenario, your router get the public IP address, and each of the computers, tablets and smartphones connected to your router (via wired or wifi) get a private IP address from your router via DHCP protocol.

Internet Assigned Numbers Authority (IANA) is the organization responsible for registering IP address ranges to organizations and Internet Service Providers (ISPs). To allow organizations to freely assign private IP addresses, the Network Information Center (InterNIC) has reserved certain address blocks for private use.

**STATIC AND DYNAMIC IP ADDRESS**

An IP address is an address assigned to a device on the Internet. It is analogous to postal address where a letter is delivered, and an IP address is computer's address where internet traffic is delivered. An IP address is assigned to you by your Internet Service Provider (ISP). When you sign up with your ISP, your ISP either assigns you a static IP address or a dynamic IP address depending on the contract. If you need to setup a web server or an email service, you'll need a static IP address. If you are just browsing an Internet, you may just get by with a dynamic IP address.

-**A static IP address** is an address that is permanently assigned to you by your ISP (as long as your contract is in good standing), and does not change even if your computer reboots. A static IP address is usually assigned to a server hosting websites, and providing email, database and FTP services. A static IP address is also assigned to a commercial leased line, or public organization requiring same IP address each and every time. Since static IP address is assigned to you, you'll have to manually configure your machine (router or server) to use the static IP address assigned to you.
Static IP address Advantages

- Address does not change - good for web servers, email servers and other Internet servers.
- Use DNS to map domain name to IP address, and use domain name to address the static IP address. Similar can be achieved with Dynamic DNS for dynamic IP address, but it's not as clean as the static IP address.
  Static IP address Disadvantages
- Expensive than dynamic IP address - ISPs generally charge additional fee for static IP addresses.
- Need additional security - Since same IP is assigned to a machine, hackers try brute force attack on the machine over period of time. -**A dynamic IP address** is an IP address dynamically assigned to your computer by your ISP. Each time your computer (or router) is rebooted, your ISP dynamically assigns an IP address to your networking device using DHCP protocol. Since your ISP dynamically assigns an IP address to a computing device on reboot, your device may not always receive the same IP address previous assigned to it. Even if your machine is always on and permanently connected, some ISPs do change IP address on-the-fly even though this is very rare. A sticky nature of DHCP generally reassigns same IP address to the same machine, it is not guaranteed to receive same IP address as IP pool may exhaust at times and lease time may expire.

Dynamic IP address advantages:

- Cheaper than static IP address
- Changing IP address gives more privacy.
  Dynamic IP address Disadvantages:
- Requires DHCP server to obtain an IP address.
- Non-static. Each time IP address changes, you may have to find you IP address again.

**SWITCHING**

Switching is a mechanism by which data/information sent from source towards destination which are not directly connected. Networks have interconnecting devices, which receives data from directly connected sources, stores data, analyze it and then forwards to the next interconnecting device closest to the destination.

A network switch is a computer networking device that connects devices together on a computer network, by using packet switching to receive, process and forward data to the destination device. Unlike less advanced network hubs, a network switch forwards data only to one or multiple devices that need to receive it, rather than broadcasting the same data out of each of its ports.

It’s a multiport network bridge that uses hardware addresses to process and forward data at the data link layer (layer 2) of the OSI model. Switches can also process data at the network layer (layer 3) by additionally incorporating routing functionality that most commonly uses IP addresses to perform packet forwarding; such switches are commonly known as layer-3 switches or multilayer switches.
At broad level, switching can be divided into two major categories:
-Connectionless: The data is forwarded on behalf of forwarding tables. No previous handshaking is required and acknowledgements are optional.
-Connection-Oriented: Before switching data to be forwarded to destination, there is a need to pre-establish circuit along the path between both endpoints. Data is then forwarded on that circuit. After the transfer is completed, circuits can be kept for future use or can be turned down immediately.

_Circuit Switching_

When two nodes communicate with each other over a dedicated communication path, it is called circuit switching. There is a need of pre-specified route from which data travels and no other data is permitted. In circuit switching to transfer the data, circuit must be established so that the data transfer can take place. Circuits can be permanent or temporary. Applications which use circuit switching may have to go through three phases:

- Establish a circuit;
- Transfer the data;
- Disconnect the circuit.
  Circuit switching was designed for voice applications. Telephone is the best suitable example of circuit switching. Before a user can make a call, a virtual path between caller and callee is established over the network.

_Packet Switching_

A mode of data transmission in which a message is broken into a number of parts which are sent independently, over whatever route is optimum for each packet, and reassembled at the destination.

Packet switching is a digital networking communications method that groups all transmitted data into suitably sized blocks, called packets, which are transmitted via a medium that may be shared by multiple simultaneous communication sessions. Packet switching increases network efficiency, robustness and enables technological convergence of many applications operating on the same network.
Packets are composed of a header and payload or body.

Control Information in the header is used by networking hardware to direct the packet to its destination where the payload is extracted and used by application software. It provides data for delivering the payload, for example: source and destination network addresses, error detection codes, and sequencing information. Payload / Body is the part of the transmitted data that is the actual intended message.
Packet switching may be classified into connectionless packet switching, also known as datagram switching, and connection-oriented packet switching, also known as virtual circuit switching.

Examples of connectionless protocols are Ethernet, Internet Protocol (IP), and the User Datagram Protocol (UDP). Connection-oriented protocols include X.25, Frame Relay, Multiprotocol Label Switching (MPLS), and the Transmission Control Protocol (TCP).

**Datagram (data packet) construction**

Each datagram has two components: a header and a payload.
The IP header is tagged with the source IP address, the destination IP address, and other meta-data needed to route and deliver the datagram. The payload is the data that is transported. This method of nesting the data payload in a packet with a header is called encapsulation.

The term datagram is often considered synonymous to packet but there are some nuances. The term datagram is generally reserved for packets of an unreliable service, which cannot notify the sender if delivery fails, while the term packet applies to any packet, reliable or not.

Datagrams are the IP packets that provide a quick and unreliable service like UDP, and all IP packets are datagrams; however, at the TCP layer what is termed a TCP segment is the sometimes necessary IP fragmentation of a datagram, but those are referred to as "packets".

**ROUTING**

Routing is the process of selecting best paths in a network. Routing is a function associated with the Network layer (layer 3) in the standard model of network programming, the OSI model.
Routing is done by special network devices called routers or it can be done by means of software processes. The software based routers have limited functionality and limited scope.
In packet switching networks, routing directs packet forwarding (the transit of logically addressed network packets from their source toward their ultimate destination) through intermediate nodes (network hardware devices such as routers, bridges, gateways, firewalls, or switches).

A router may create or maintain a table (record) of the available routes and their conditions - routing table, and use this information along with distance and cost algorithms to determine the best route for a given packet. Typically, a packet may travel through a number of network points with routers before arriving at its destination.
A router is always configured with some default route. A default route tells the router where to forward a packet if there is no route found for specific destination.

Routes can be statically configured or dynamically learnt. One route can be configured to be preferred over others.

Routers upon receiving a forwarding request, forwards packet to its next hop (adjacent router) towards the destination. The next router on the path follows the same thing and eventually the data packet
reaches its destination.

Network address can be of one of the following:
-Unicast (destined to one host);
-Multicast (destined to group);
-Broadcast (destined to all);
-Anycast (destined to nearest one).

A router never forwards broadcast traffic by default. Multicast traffic uses special treatment as it is most a video stream or audio with highest priority. Anycast is just similar to unicast, except that the packets are delivered to the nearest destination when multiple destinations are available
