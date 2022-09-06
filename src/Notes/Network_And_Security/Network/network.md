#Intro to Networks

##Ch 1. Computer Network Fundamentals

###what is a computer network?

**computer network** 
    a collection of Nodes(computers) connected via wireless or cable
    such as Ethernet or fiber optic cable. wi-fi is ent via radio waves

 **Ethernet**  
    a technology used to connect devices(nodes) to a network (local or wide-area)
    the ethernet is the cable connected to our router

**Topologies**
    the techniques used to connect computers(nodes) the most come is
    the star
    
  **Star topology**
    a central node extends cable(or wireless) to each computer
    on the network. computers are connected independently of the center.
    
  _Advantage_
        straight forward connection from the center. since they 
        have their own connection, the loss of one node will not
        break the entire system. also, it is easy to add another
        node to the network.
   _Disadvantage_ 
        the issue with star is its single point of failure. if
        the hub fails all nodes fail.
        so have fail over servers backups in order to keep the
        main server going until you fix the main server.


   **Bus Topology**
    all nodes are connected to a single cable, all information that needs
    to reach the last node must pass through all nodes
    
   _Advantage_
        you will use a minimal amount of cables
   _Disadvantages_ 
        if the cable is broken all the nodes will shut down

   **Ring Topology**
    the nodes are connected to the server on a central node that are all
    connected via a single cable without an end. the information is 
    circulated until the intended recipient is reached

  _Disadvantages_
   If a network node is not configured properly, or it is down 
    temporarily for another reason, the signal will make a number of 
    attempts to find its destination.

   **collapsed ring**
    the central node will be a router or a switch. a ring topology is used 
    internally and features plugin cables each node has an independent
    cable. offices usually have a cable closet containing switch devices
    that connect the network. wth wireless available nodes are connected
    to a central router, which is connected to the main server.

   **Cable Types**

  cables are conductive media that allows the signals to flow. the signal can be an 
  electric pulse or flicker. the type of signal is defined by the type of cable.
    all cables have a limit to how far they can carry a signal it is call _attenuation_ .

  **Coaxial cables**
    a cable with a central copper wire covered by insulation, its often seen used with cable television
    
 **twisted copper cable**
   cooper wires twisted together (ethernet cable) plastic insulation. these use to be use in telephone
    wires cables can range from five to seven. they can withstand high level of noise, which makes
    the signal efficient. each cooper wire has its own touch point.

 **fiber optic**
   a cable with a core made of a glass strand which carries light. signal can carry a longer distance
    without the need to repeat the signal, which makes carrying more data much faster for a single user
    its flows near the speed of light.
    fiber optic is gaining popularity because higher bandwidth and greater network speed 

### ___focus on:___
   computer networks are a set of nodes connected by a cable. the internet is a big network. 
   the most common topology is the star other topologies are called ring and bus.
    connections utilize coaxial cables, fiber optic or the popular twisted copper wire
    networks allow for data to be shared more efficiently

###Importance of communication

  **Communication Networks**
    an is a network of a group of devices comprising hardware and 
    software connected together, whether in the same geographical 
    location or globally to facilitate communication and information sharing.

  Modern communication network consist of servers, clients, transmission media, data, operating systems, 
  switches, routers, cables, printers, and various peripheral devices extending communication 
  between devices from local area networks to globally covered networks.

  **1. File Sharing: Multimedia**
  the sharing or distribution of computer data and files. can range from 2kb or 25 Gb, can be in a 
    local network or across the world
  like your disney+ netflix or evan amazon its our phone and mobile devices make this possible,
    when we were kids we used VHS or cassette tapes or even CDs

  **2. Hardware Sharing: Backup and Recovery**
     Hardware can be expensive, with servers gaining popularity cloud computing is gaining stem
    which is nothing more than just storing everything on servers and sharing the cost with bigger
    companies. 
     There is no need to incur the costs of building or acquiring physical proprietary infrastructure
   in data servers and backup solutions. The responsibility of securing and maintain the integrity
   of your data and information is in the hands of the service host. Using these remote services 
   is not only financially economical to companies and business but also allows them to maintain 
   he is high standards they need in the competitive world.
     GitHub, AWS and Google Drive  are a few i have studied


  **3. Messaging and Communicating**
   Chat messages, emails, and correspondence sent and received within fractions of a second through
  various channels comprising the communications networks.
  With access to shared data storage and applications stored on cloud servers, a constant flow of
  communication is established between various Local Area Networks (LANs) and Wide Area Networks (WANs).


  **4. Web Access: Web Browser Applications**
   Web browser applications allow users to search, access, and display web pages.
    we use URls Uniform Resource Locators, which are addresses of the web. with authentication 
    web resources are everywhere knowledge is everywhere, the sky isnt even the limit to the 
    capabilities that you could learn.

### ___focus on:___
   1) communication is essential especially in tech
   2) communication networks, which are networks of groups 
    of devices comprising hardware and software connected together
   3) you can communicate locally(LANs) or across the world(WANs)
   4) everything we do today is  supported by communication networks, so when you are on the phone
        internet watching YouTube, Disney, or even emails are all communication networks.

### the Components of a Telecommunications System
  **Telecommunications Systems**
    nodes and links to enable telecommunication, Telecommunication systems allow distant communication 
    using electrical signals or _electromagnetic waves_ and some basic components to support the system

  **Components of a Telecommunication System**
   a telecommunication system includes a transmitter to take information and convert it to a signal, 
  a transmission medium to carry the signal and a receiver to take the signal and convert it back 
  into usable information. This applies to any communication system, whether it uses computers or 
  not.
   today communication systems are basically networks, 6 components to networks are:
    
   1) **terminals** input and output devices, starting and stopping points are established
   2) Channels which transmit and receive data
   3) processors, which provide a number of control and support functions (converting from analog to digital)
   4) Control software, which is responsible for controlling the functionality and activities of the network
   5) data in the form of messages 
   6)  Protocols(rules) TCP/IP is a protocol for communications over the Internet. I use this to make APIs

  in a network.

  **Computer Network**

   computer network is a system of computers and peripheral devices that are connected 
    electronically.
   Each computer has its own network address, so it can be uniquely identified among all the computers

  **Different Types of Networks**

   1) networks include: 
   2) network size: how broad a network expands LAN(building) WAN(country) 
   3) transmission media: the means or material the data is transferred physical(wired) or electromagnetic(wireless)
   4) management method: 
      1) peer-to-peer: P2P task allocated amongst all members without hierarchy
      2) mainframes : (server) a very powerful computer does all the processing, and very basic terminals
      3) client/server:users request resources from the network typically servers
      
   5) network topology: The layout of the interconnections between the computers in a network 


  **Network Properties**
   networks can be broken down in terms of bandwidth, cost and reliability

  1) Bandwidth: the amount of data that can be transferred over a network per second
     1) wireless 11 and 54 Mbit/s
     2) Ethernet 1 Gbit/s or more
     
  2) Cost: installing the network hardware, such as cables and switches,
    and the cost of running and maintaining the system.
  3) Reliability:  how often the network does not perform as expected, reliable systems have backups
  
### ___focus on:___
  -A telecommunications system is a collection of nodes and links to enable telecommunication

    The six basic components of a telecommunication system are:

    Input and output devices
    Telecommunication channels
    Telecommunication processors
    Control software
    Messages
    Protocols
-A computer network is a system of computers and peripheral devices that are connected electronically.

### What is a Client-server Network

 **What Is a Client-Server Network?**
    a client makes a request to the server over a network if the server deems the request valid the server
    fetches the requested information(data) for the client.

 **How Does It Work?**

   a client make http request to the server, which produces a request response with data if
   authorize and the client is authenticated. the network is the channel for the communication.
   designed for end-users clients to obtain resources(data) from a server.
   a servers main purpose is to serve its client

  the server can make request of the client as well to check authentication and authorization, if not 
    valid the server will end the connection in order to free up network traffic.

 **What Are the Advantages of a Client-Server Network?**
  The biggest advantage to using this setup is central management of the server.
   One centrally managed server is the key to ease of management, and it is cost-effective, too.
    the central server is simple to set up and troubleshooting can be done in one location. multiple servers
    can cause redundancy(RDBMS) 

 **What are the Disadvantages of a Client-Server Network?**
 single point of failure (SPF): having one location being able to take down an entire system

### ___focus on:___
 1) A server designed to allow users access to certain resources
 2) Advantages
    1) Central management and simple configuration
 3) Disadvantages
    1) Single point failure and hacker prone

### Network Architecture: Tiered & Peer-to-Peer

  **Network Architecture**
  how computers are organized in a system and how tasks are allocated between these computers.

   two of the world's most widely used types of network architecture are:

  **Peer-to-Peer(P2P)**
  1) the tasks are allocated among all the members of the network.
  2) There is no real hierarchy among the computers, and all of them are considered equal.
     1) This is also referred to as a distributed architecture or workgroup without hierarchy.
     2) every computer on the network has a special software running that allows for communications 
        between all the computers(Napster)
     3) if one node fails he networks continues to function
     
  **Client/Server**
  Client/server architecture is also called 'tiered' because it uses multiple levels.
  a number of network clients or workstations request resources or services from the network. 
  1) Servers are typically computers with more processing speed, memory and hard disk space than a 
  regular desktop computer.
     1) servers run their own operating system that manages the various network
     2) Depending on the need for network storage and services, a single network 
       may only use one or a large number of servers.
     3) Very large databases are stored on the server
  2) Clients are hardware devices which provide end users with access to data and services on the 
    server.
     1) SERVICES CAN BE USED INDEPENDENTLY
     2) the client accesses these databases without copying them onto the local hard drive.
     
  **Multi-Tier Architecture**
  A client/server network is also called a 'tiered' network, with the clients representing 
   one level and the servers or server representing a second level.
  A client (level 1) sends a request for the data to a server (level 2). The server obtains 
  the data from the database and replies to the request by sending the data back to the client. 
  This is referred to as a 'two-tier' system since there are two levels.

 1) Provides greater flexibility by not having to rely on a single server
 2) Increases security by allowing different security policies at each level
 3) Increases performance since tasks are allocated to multiple servers
 4) a multi-tier client/server system requires more resources and is also more complex to manage.

  
### ___focus on:___
 1) In a peer-to-peer network, the tasks are allocated among all the members of the network, 
    and there is no hierarchy. 
 2) In a client/server network, a number of network clients or workstations request 
   resources or services from the network. 
 3) A server is used to provide these resources or services. 
    1) A multi-tier client/server network makes it possible to configure different servers for 
    2) different tasks.

### Types of Networks: LAN, WAN, WLAN, MAN, SAN, PAN, EPN & VPN

  **Types of Networks**
  1) Computer networks can be characterized by their size as well as their purpose.

  **Personal Area Network**
  1) PAN
  2) a network organized around a single person or building
  3) can be in a small office or residence
     1) one or more computers, telephones, peripheral devices, video game consoles 
        and other personal entertainment devices
     2) we are a HAN home area network we use wired and wireless networks, also because we use the
        same network typically.
        1) this is convenient because we can stream movies to tv, print wireless-ly, upload from our phone
        
  **Local Area Network**
  1) LAN
  2) a computer network at a single site, typically an individual office building
  3) built with relatively inexpensive hardware, such as hubs, network adapters and Ethernet cables.
     1) typically, relies mostly on wired connections for increased speed and security, but wireless connections can also be part of a LAN. 
     2) High speed and relatively low cost are the defining characteristics of LANs.
  4) LAN are ideal for startups when you need to share resources 
  5) when entirely wireless, it is referred to as a wireless local area network, or WLAN.

  **Metropolitan Area Network**
  1) MAN
  2) computer network across an entire city, college campus or small region
  3) MAN(city) are bigger than a LAN(a building)
  4) MANs can connect multiple LANs
  5) A campus is referred to as CAN campus area network

  **Wide Area Network**
  1) WAN
  2) very large area, such as an entire country or the entire world.
  3) this is our world wide web!
  4) multiple LANs virtually are VLANs
  5) virtual connections, fiber optic provides a backbone to many WAN setups

  **Private Networks**
  One of the benefits of networks like PAN and LAN is that they can be kept entirely private 
  by restricting some communications to the connections within the network.
5
  1) Enterprise private network, or EPN 
     1) controlled by organizations who need to obtain a private network
     2) used in sectors where security can be an issue
  2) Virtual private network, or VPN
     1) private networks that are virtual 
     2) data is encrypted before being sent
     3) A VPN provides a high level of security for traffic over the Internet.

  **Other Special Purpose Networks**
  some networks have been built for a very specific purpose.
  1) storage area network (SAN)
     1) a network dedicated to data storage
     2) gives network and database administrators more control over data storage.
     
  2) body area network, or BAN
     1) wearable devices like fit bits
     2) tracking devices air tags
     
### ___focus on:___
1) Computer networks can be characterized in the term of the geographic area they occupy 
  and the purpose of the network within this geographic area.
2) A personal area network is a computer network organized around an individual person within a 
  single building. 
3) A local area network consists of a computer network at a single site for sharing resources, 
 typically an individual office building.
4) A metropolitan area network consists of a computer network across an entire city, college 
  campus or small region.
5) A wide area network occupies a very large area, such as an entire country or the entire world.
6) Special purpose networks include storage area networks, home area networks and body area networks.
  
### What is an Internet Service Provider(ISP) 

   provides Internet gain access to companies, families, and even mobile users. provides internet
    access to customers.
   bandwidth drives the price, so internet is typically what the customer needs 

  **The Internet Highway**
  1) connect from another which gives it the highway name(typically forming a backbone)
  2) Backbones usually consist of satellite, copper wire, or even fiber-optic media.
  3) Media is a term that means cables or lines, and it's the physical means of connecting
    your home to the internet.

  **Satellites**
  1) Customers who live in remote locations, such as farms, deserts, and mountainous areas, 
    may require a satellite Internet service.
  2) transmitting and receiving data from satellite orbiting the earth
  3) allows for flexibility with limited environmental impact, and allows for independence from 
    local vendors

  **Fiber Optics**
  1) is a transmission medium used to transmit light instead of electrical voltage, like copper.
  2) travels at the speed of light
  3) immune to electromagnetic interference
  4) very reliable
  5) there are fiber cables that run along the ocean floor, connecting countries across the globe 
    through high speed Internet access. Pretty cool!
  
  **Copper Cables**
  1) ISPs will more likely supply home users with a copper medium, such as that used for DSL or cable broadband.
  2) electrical pulses through a copper wire
  3) Broadband is cheap and provides excellent Internet service to the home user and be fixed if there are breaks.
  4) it uses existing home media, some users are given routers and/or modems
  5) susceptible to electromagnetism(noise)
  6) requires regeneration to prevent attenuation

### ___focus on:___

1) Internet Service Provider - ISP; a company such as AT&T, Verizon, Comcast, or Spectrum that provides Internet access to companies, families, and even mobile users

2) Bandwidth - the amount of data that can be sent through an internet connection in a given amount of time

3) Media - cables or lines; the physical means of connecting to the internet

4) Satellite Internet service - a system which transmits and receives data from a satellite orbiting about 22,000 miles above the earth

5) Fiber optics - a transmission medium used to transmit light instead of electrical voltage, like copper

6) Attenuation - the process where the signal loses its distinct signature as it travels further down the copper wires, to the point the signal is no longer recognizable

### The Internet
**What is the Internet?**
The Internet is a worldwide system of computers and networks linked together. These computers and networks,
which are scattered across the globe, vary in shape and size. They cooperate with each other in order to 
exchange data through a wide variety of network technologies. Words, images, sound files and software can 
all be transmitted through the Internet via the telephone system, copper wires, cables, optical fibers or radio waves. 
What is most unique about the Internet is that no one owns it and there is no formal managing organization.

  **History of the Internet**
  1) internet began as a project for DOD in 1962
  2) ARPA, or the Advanced Research Projects Agency, 
   was responsible for designing a computer network for military use.
  3) the goal was to maintain functionality even if connection were severed
  4) ARPANET was to be a mean to send and receive transmissions
  5) completed in 1969
  6) in 1981 National Science Foundation Network or NSFNET was founded by the university of california
  7) in 1990 NSFNET became known as the Internet.

   **Internet Protocol (IP) Address**
    each computer has a unique IP in order to connect to the internet

   **Internet Service Provider**
   An ISP is a company that provides access to the Internet.

  **Communication (TCP/IP)**
  1) TCP/IP or Transmission Control Protocol/Internet Protocol is a communication protocol suite that 
    is particularly important for the Internet to function.
  2) a set of rules for how data should be processed on the internet

  **Domain Name System (DNS)**
  1) is a distributed database comprised of all the websites on the Internet and their corresponding IP addresses.
  2) A web address is often referred to as a URL or uniform resource locator.
  3) URL: the top-level, domain name, domain name and host name
  
  **ICANN or Internet Corporation for Assigned Names and Numbers**
  1) is an organization that performs Internet related tasks. It coordinates the DNS, IP Addresses and other unique 
   identifiers that enable to Internet to function smoothly.

  **Process for Retrieving a Web Page**
  1) open the browser
  2) connect to the web
  3) make a request in the form of packets through your modem
     1) A modem is a device that converts digital signals to analog signals 
      and back to digital signals for the transfer of data.
  4) type in the URL 
  5) your ISP will send your request onto the DNS
  6) When a match is found, you will be directed to the website's IP address
     1) A server is a computer connected directly to the Internet in which data 
      like web pages can be stored and accessed
     2) Because packets can take a variety of paths, they can avoid congestion and 
       reach their destination faster.
  7) you will see the page 
### ___focus on:___
  1) internet creation process
  2) retrieve a web page

### trends in Networking
**Networking**
**Wi-Fi 6 & Wi-Fi 7**
**5G**
**Automation**
**1. AI and Machine Learning**
**2. SD-WAN**
**3. Open Source Networking**
### ___focus on:___




##Ch 2. Network Standards & the OSI Model
###Lesson 1 - Organizations that Create Networking Standards

  **What are Networking Standards?**
  1) A networking standard is a document that has been developed to provide 
     1) technical requirements, 
     2) specifications and guidelines that must be employed consistently to ensure
        1) devices, equipment and software which govern networking are fit for their intended purpose.

  2) Standards ensure quality, safety and efficiency.

  **Organizations that Create Networking Standards:**
    
  **American National Standards Institute (ANSI)**

   1) US based organization
   2) **organization responsible for US standards and assessment systems.**
      1) organization responsible for US standards and assessment systems.
      2) These standards govern the computer and technology industry.
      3) the main body responsible for coordinating and publishing information 
       on standards in the networking and technology Industry in the United States.
   3) **American Standard Code for Information Exchange (ASCII)**
      1) This standard is responsible for the codes used to represent text used in computers, 
       telecommunication equipment and other digital devices.

  **Telecommunications Industry Association (TIA)**
  
   1) Formerly known as the Electronic Industries Alliance (EIA) EIA no longer exists
   2) formed to govern the electronic manufacturers' industry in the United States.
   3) It ensures the compatibility and interchangeability through structured cabling 
    between equipment from different manufacturers.
      1) unshielded twisted pair cable systems CAT3 through CAT5
      2) standard TIA-568-C which governs telecommunications cabling standards.
         1) nearly all voice, video and data networks
        

  **International Standards Organization (ISO)**
   1) standards organization represented internationally by 17 national standards organizations 
    and is based in Geneva Switzerland.
      1) These standards cover things like manufactured products in network technology.
      2) networking where Ethernet technology forms the foundation of most
             local area networks (LANs)
         1) the ISO/IEC/IEEE 8802-3:2017
            1) governs the telecommunications and information exchange between systems.

  **International Telecommunications Union (ITU)**

  1) an arm of the United Nations consisting of three sectors:
     1) Radio Communication (ITU-R) which sets standards for fair use in radio frequency (RF)
     2) Telecommunication Standardization (ITU-T) which standardizes telecommunication operations 
      internationally
     3) Telecommunication Development (ITU-D) which manages communications operations in 
      developed countries.
        The ITU formulates and publishes standards within the electronic communication and 
        broadcasting technologies, including the Internet.
     
  **Internet Society (ISOC)**

  1) non-profit international organization responsible for the standards that govern the Internet 
    as well as education and development policies.
     1) standard under this organization is the SO/IEC 27033-1:2015.
        1) This provides an overall document that describes and provides the concepts and 
          guidelines that **_govern network security_**.
        
  **Internet Assigned Numbers Authority (IANA)**

  1) American organization that is responsible for: 
     1) globally coordinating the autonomous system number allocation 
     2) global IP address allocation 
     3) root zone management in DNS (Domain name Service) 
     4) space and internet number and IP related symbols
  2) If you use the Internet at all, or belong to any network, this is one of 
     those standards bodies that govern our environment constantly.
  3) They assign IP address blocks to the **Regional Internet Registries (RIRs)** 
     who in turn allocate them by region globally.
     1) the IP range of addresses which are utilized in your country/area have been
        set by the IANA and RIR authorities
     
  **International Corporations for Assigned Names and Numbers (ICANN)**

  1) sets standards that ensure the stability, interoperability and security of the Internet.
  2) the ICANN is able to perform some IANA functions

### ___focus on:___
1) American National Standards Institute (ANSI)
2) Telecommunications Industry Association (TIA), formerly the Electronic Industries Alliance (EIA)
3) International Standards Organization (ISO)
4) International Telecommunications Union (ITU)
5) Internet Society (ISOC)
6) Internet Assigned Numbers Authority (IANA)
7) International Corporation for Assigned Names and Numbers (ICANN).

###Lesson 2 - Internet Packet: Definition & Explanation

**Basic Principles**
 1) Internet packets: to accomplish high speed delivery data and communication information gets grouped in 
 small packages.
 2) data packets are formatted, addressed, and sent using common internet protocols, 
   such as the Transmission Control Protocol/ Internet Protocol(TCP/IP)

**Key Terms**
1. **network address :** which are unique identifiers applicable to specific network computer; 
      the network address identifies the data packet's intended recipient
2. **network protocol :** which establishes the guidelines and conventions to send and 
     receive messages formatted as data packets
3. **data packet :** which is essentially a container used to convey data or information via TCP/IP or similar protocol; 
                     the data packet contains (among other information) the IP address of the intended recipient, source data, 
                      and network information.
4. **packet-switching:** sending and receiving data packets.

**Data Packet Description**
1) data packet composed of binary data(ones and zeros) formatted to allow movement across a network.
2) transmitted data arrives as individual data packet and contains:
   1) a **header**: packet origin and destination
   2) **message body:** the payload or data
   3) **footer:** contains ending or termination instructions.
   the header and footer both contain error checking algorithms to ascertain reception accuracy.
3) when received the packet are reassembled into its original form
   1) removal of the header and footer information
4) concatenation of individual packets placing them in their proper order. 

**Data Packet Composition**
An IP presently has 2 basic versions: IPv4 and IPv6. Though IPv6 is more advanced and faster than 
IPv4, many organizations still use IPv4.

Typically, an IPv4 packet is composed of the 14 fields shown in the table appearing on your screen
right now. It's important to note that bit distribution among fields may vary but will equal a 
total packet length of 32 bits.

Each of the 14 fields indicated by name in Table 1 are numbered and briefly described in the 
itemized list here:

1. **Version** - which is the IP version in use
2. **IHL** - which stands for IP header length 
3. **Type-of-service** - which indicates the level of importance or criticality 
4. **Total length** - which is the length in bytes of the complete packet 
5. **Identification** - which is an integer value used for rebuilding due to fragmentation 
6. **Flags** - which is a 3-bit field used to control fragmentation 
7. **Fragment offset** - which indicates the position of fragment's data relative to the beginning
of the original datagram (message)
8. **Time-to-live** - which is a counter measuring time before discarding 
9. **Protocol** - which indicates the upper-layer protocol receiving incoming packets 
10. **Header checksum** - which is used to verify IP header integrity 
11. **Source address** - which identifies the sending node 
12. **Destination address** - which identifies the receiving node 
13. **Options** - which enables additional support such as security 
14. **Data** - which is the datagram (message) contents

IPv6 packet is also composed of 14 fields but they are divided between a set of headers, 
 the basic or fixed IPv6 header, and the IPv6 extension headers. The basic or fixed header 
 consists of 8 fields that contain data that is necessary for routing and delivery.

The following 8 fields describe the fixed headers:

1. Version - the Internet protocol in a 4-bit sequence 
2. Traffic class - the precedence of the IPv6 packet 
3. Flow label - the packet's sequential flow 
4. Payload length - the size of the data collected by a particular packet 
5. Next header - the Extension Header type 
6. Hop limit - the field that keeps the packet from going into an infinite loop 
7. Source address - the origin address of the package 
8. Destination address - the recipient address of the packet

The Extension Header contains supplementary information used by network devices to decide how 
to direct or process an IPv6 packet. The following list describes the 6 extension headers:

1. Routing - defines strict source routing and loose source routing for the packet 
2. Fragmentation - specifies how to perform IPv6 fragmentation and reassembly services 
3. Authentication - provides authentication, data integrity, and anti-replay protection 
4. Encapsulating Security Payload - provides data confidentiality, data authentication, and anti-replay protection for ESP packets 
5. Hop-by-hop options - specifies delivery parameters at each hop on the path to the destination host 
6. Destination options - specifies packet delivery parameters for either intermediate destination devices or the final destination host
**Packet Loss**

### ___focus on:___
###Lesson 3 - OSI Model: Using Open Systems Interconnection to Send and Receive Data
### ___focus on:___
###Lesson 4 - Application Layer of the OSI Model: Definition, Functions & Protocols
### ___focus on:___
###Lesson 5 - Presentation Layer of the OSI Model: Definition, Functions & Protocols
### ___focus on:___
###	Lesson 6 - Session Layer of the OSI Model: Functions, Protocols & Examples
### ___focus on:___
###	Lesson 7 - Transport Layer of the OSI Model: Functions, Security & Protocol
### ___focus on:___
###Lesson 8 - Network Layer of the OSI Model: Functions, Design & Security
### ___focus on:___
###	Lesson 9 - Data Link Layer of the OSI Model: Protocol, Functions & Design
### ___focus on:___
###	Lesson 10 - Physical Layer of the OSI Model: Definition, Components & Media
### ___focus on:___
###	Lesson 11 - Internet Connectivity and Communication Standards
### ___focus on:___

##Ch 3. Transmission & Network Media
##Ch 4. The Transmission Control Protocol/Internet Protocol Model
##Ch 5. TCP/ IP Mail Service & Network Troubleshooting
##Ch 6. Network Topologies & Ethernet Standards
##Ch 7. Network Hardware
##Ch 8. Wide Area Network (WAN)
##Ch 9. Wireless Network
##Ch 10. Virtual Networks
##Ch 11. Network security
##Ch 12. Voice & Video Communication Over IP