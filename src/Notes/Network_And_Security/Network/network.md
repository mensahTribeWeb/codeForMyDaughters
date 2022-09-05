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
### ___focus on:___
### Network Architecture
### ___focus on:___
### Types of Networks: LAN, WAN, WLAN, MAN, SAN, PAN, EPN & VPN
### ___focus on:___
### What is an Internet Service Provider(ISP) 
### ___focus on:___
### The Internet
### ___focus on:___
### trends in Networking
### ___focus on:___




##Ch 2. Network Standards & the OSI Model
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