#Network And System Security

##Ch 1. Introduction to Network Security
   
##Ch 2. Information Security Overview
##Ch 3. Network Encryption
##Ch 4. Network Firewall Systems
##Ch 5. Wireless Network Security
##Ch 6. Web Application Security

##Ch 7. Network Authentication

###Network Traffic

**Network traffic** is similar to road traffic on lake shore drive where there can be interruptions and blocks if there is a
large amount of data travelling through the network and the network capacity is unable to support the density of packets of data passing through. 
Network monitoring tools help to visualize the entire network and identify the locations where there are traffic blocks.

An **IP scanner** helps identify all devices connected to the network. Removing unwanted devices will help reduce traffic on the network and improve 
network efficiency. Network logs can help identify the cause of the slowness - for example a processing delay can in turn lead to a queuing delay 
and a delay in transmission.

A **bandwidth tool** can help identify points where transmission is less than optimal. Some methods to increase the bandwidth include channel 
bonding and link aggregation where multiple ports can be combined. Using wired instead of wireless connections can also help increase network 
effectiveness since the number of devices connecting on the wireless can reduce the network capacity.

**Network filtering** by IP addresses and dynamic packet filtering help direct critical traffic and block unwanted traffic thus increasing the 
capacity of the network. This method is especially useful for a quick fix when there is not much time and an immediate need to get the network 
to an improved performance level.

### ___focus on:___
    -in order to fix your slow connection when building a website set up filters ahead of say a big sale or 
    during a time you will have increased traffic
    - when we ask to shut off the extra devices you both are not using it's to limit 
    network traffic to increase the throughput and to increase bandwidth
    - try an Ip scanner if you notice the network becomes slower than usual 
    - I use task manager as a networking tool in order to visualize what's effecting 
    the network
    - double your bandwidth by combining two or more ports by bandwidth channel bonding and 
     link aggregation

###Practice Monitoring and Auditing Network Traffic
-download Nagios Core
-with Nagios Core You will analyze hosts, services, 
evaluate dashboard reports, view a network map, and discover
security threats to the network.
-login
-tactical Overview
    -unhandled problems
    -any moving green arrows means someone is attempting to hijack 
        that systems DNS
-Next network outages
    -None indicates a good sign
-Reports to Alerts
    -A green box means the service is OK (like a message/FYI);
    -Yellow indicates a warning: it wouldn't hurt to take a deeper look at the issue
    -Red is a critical error and a hard stop
-Back to Services
    -Under Problems -> Services, 
    take a look at the critical (red-shaded) services.
    -NOAA
    -verify what you have enabled
    -Host Commands(right of screen)
        -list of commands that can be used
        -If you believe these errors are not 100% right, 
            you can click a link to Disable notifications for the host.
    -Locate host on a map
        -In order to see a graphical layout of the network, click the 
        link Locate host on map.
        -This is a powerful feature of an IDS/IPS system.
        -It is an excellent visual that shows the full layout 
            of the network and hosts.
        -From here, you can click any of the hosts and drill in further.
    -Service Groups
        -From the left-hand menu, click Summary under the Service Groups menu.
        -From this screen, you can also drill into detail.
        -Websites (HTTP). Click on the link labeled 1 unhandled to see detail about this warning.
        -we can check your YouTube usage 

### ___focus on:___
    -possible network analytics and summary data that Nagios
    provides which you can build upon this foundation

### Kerberos Encryption Types

-The Need to Be Safe
    -in the news we keep seeing the things senseless violence and violence
    at schools. these situations are sad, but  we must address them
    -I see we are in a technological revolution, so we have tools
        that can assist us such as kerberos and encryption
-Encryption
    -it protects information and protects it from malicious intent
    -information is transformed with mathematically based algorithms
    - abstract keys
    -encryption is everywhere banks, your YouTube account, your amazon purchases 
-Kerberos
    -est. 1980 
    -MIT
    -front-line network authentication method
    -is the individual authorized for general information
    -does individual have rights to the particular resources to the system
    -supported by mongodbDB(database), RedHat Linux, Microsoft sharepoint
    -Kerberos provides strong authentication, meaning that it can't easily be broken or compromised. 
    -It has become an industry standard for network access and authentication.
-Types of Kerberos Encryption
    -**DES (Data Encryption Standard)** - Once thought of as strong, this encryption type has been broken, 
        and is now considered insecure.
    -**Arc four (also known as RC4)** - It is an encryption type known for its simplicity and ease of calculation. 
        It has been broken, and is considered insecure.
    -**AES (Advanced Encryption Standard)** - It is one of the strongest algorithms available today. 
        It is considered strong enough for sensitive political and military applications.
    -**Camellia** - It is a modern day encryption algorithm that is also considered strong,
        even though it has relatively short keys.
### ___focus on:___
    -Encryption strength is a measure of how easily an algorithm can be broken by a brute force attack.
    - brute force attack is a attack that trys all possibilities until the correct answer(key) is found
    - Algorithms like AES and Camellia rely on the fact keys are so large trying them in a short time isnt reasonable. 
    - why using longer and complex passwords you remember is a better choice

###What Is a Virtual Private Network (VPN)?
    -**VPN**: Virtual Private Network
    -a network that is completely isolated from the rest of the internet
    -It provides people, businesses, governments, and military organizations 
    to remotely use network resources securely.
    -VPNs use site-to-site and remote access methods to work
    -VPNs provide a vertual service
    -VPNs provide secure access to your LAN(local area network)
    -example redfins home office and remote worker
    
    -Different Types of VPNs
        -site to site VPN and remote access VPN
         -site-to-site VPN: 
            -two or more networks joined together
            -sophisticated encryptions are utilized
        -remote access VPN
            -allows a user to access a private network
            -resources can be accessed on remote devices
            -can save money by limiting trips to the resource and allows you to access information 
                a secured rmote 
    -How Do VPNs Work?
        -if there is no encryption, then there is no VPN
        -VPNs use tunneling protocols such as 
            -Point-To-Point-Tunneling-Protocol(PPTP)
            -Layer 2 Tunneling Protocol (L2TP)
            -Secure Socket Layer (SSL)
            -IPSEC
        -these provide secure authentication and encryption of network traffic
        -Tunneling protocols encapsulate the information
        -Without encryption, banks can be held liable in court and face serious fines, even prison

### ___focus on:___  
    -VPNs provide access to network resources anywhere in the world through the use of encryption.
    -Organizations usw site to site VPNs to share imformation in real time
    -remote access VPNs to gain information from their own private network
    -B2B B2C etc would not be possible without VPNs secure encryption and tunneling protocols
    -we are in a technilogical Revolution(2021)

###VPN Encryption: Types & Protocols
    -What is VPN Encryption?
        -vpns ensure secure commuunication
        -its like speaking in private or in code so others around dont eavesdrop
        -VPNs allow private connection through public network like the internet.
        -the data is scrambled

    -Types of VPNs and Functionality
        -we start with authentication in the form of a greeting( acknowledgment that you are who you say you are)
        -the conversation is conducted in a private area(a session)
        -next the secret code(encryption) you will understand with a password(key)
        -"we make sure we know who we're talking to, we set up a private channel for our conversation, and in case somebody is listening in, we speak in code."
   -Protocols Used in VPN Encryption
        -protocols: the ground rules to communicate over a network authentication and encryption
        -protocol stack: a group of protocols working together
        -Three main suites
            -IPsec (Internet Protocol Security)
                -Transport Mode: encrypts message being sent
                -tunnel Mode: encrypts message and everything else
            -L2TP (Layer 2 Tunneling Protocol)
                -creates a secure tunnel between two endpoints and often works 
                in conjunction with IPsec which handles the encryption.
            -PPTP (Point-to-Point Tunneling Protocol) 
                -is widely used and is supported on Windows, Mac and Linux platforms
            -SSL (Secure Socket Layer)
                -create a secure connection between an Internet user and a shopping site 
                or online service provider. 
### ___focus on:___
    -transport your data via a VPN use linux to establish a server
    -VPN (Virtual Private Network) technology to protect the 
        confidentiality and integrity of your data.
    -authentication: always assure your speaking to the correct person
    -encryption: scramble your data but have a key
    -protocols: assure everyone is playing by the rules

###Security Perimeter: Definition, Solutions & Devices
    -Bad guys are out there
        -cannot be seen
        -no time preference
        -any location city, state, country
        - but a network must be established for your internal external imformation
    -Understanding Security Perimeters
        -perimeter
            -is the border between one network and another
        -security perimeter
            -can be defined as placing the necessary safeguards at the entrance of a 
                privately owned network to secure it from hackers.
    -Network security is an essential element for any buisness who must access the 
            internet and the world wide web.
    -three basic questions to ask 
        1. How can an attacker gain access to a company's network?

        2. What tools can we use to prevent an attacker from gaining access to a 
            network?

        3. What can we do if an attacker gained access to a company's network?
    -Understanding Access
        -hackers: are individuals who attempt to acess your imformation illegally
        -the will use the means of the internet
        -edge router: the networks entry points, the device in which all network traffic 
            must pass in order to get into the network.
        -acess control: locks to the edge router, they are included on the acess control
            list. its similiar to a firewall(basically the same thing)
        -firewall: access controls, used to manage traffic into a network.
    -Preventing Access
        -intrusion detection and intrusion prevention:
            systems are pieces of equipment that monitor the network for unusual movement and sound an 
            alarm if something unusual is detected
    -Addressing Acess
        -the intrusion network will alarm you of a intrusion and attempt to isolate 
        the attack.
        - the isolation will allow you to continue operations, while external problems will
            be addressed.
### ___focus on:___
    1) set up a parimeter by setting up the essential equipment and technologies to prevent
        an outside attack against a network.
    2)hackers are those who will try to gain acccess of someone networks
    3)hacker will try to access the network through edge routers
    4) lock down the router with access controls(works like firewalls)
    5)when a hacker gains access the next line of defense will be intrusion detection
        and intrusion prevention.
    6) when the systems alarm is sound intrusion prevention will attempt isolation 
        this prevents the entire network from being compromised.

###Types of Risk & Creating Contingency Plans
    -Introduction to Risks
        "The business world is ruthless."
        -uncontrolled risk is scary 
        -make contingency plans to deaL with potential risk
        - prepare for the non preparation 
        -you know how I say to many variable those are the risk you prepare for
    -Risk and the Risk Matrix
        -Risk is prevelent in all aspects of life
        -Risk is the danger involved in any situation, weather know or not
        -when I day traded if I didnt prepare for the risk I could have lost alot of 
            money, market share of resources
        -risk matrix is a visual aid to better see how risk affects operatrtion
        -a risk rating: combines severity and likelihood of a risk happening to calculate the rating
    -Risk Measurements
        - plan for the probability of risk happening
        - make a contigency plan when risk may happen
    -Variance Risk
        -variance: is the measurement of the spread between numbers in a set.
        -used to determine if a project is under or oveer budget
    -Contingency Risk
        -future events that has possibility of happening but cannot be predicted with certainty
        - adding additional aspect to what may go wrong in a project 
            -time
            -labor
            -bugs
        -plan for unforseeable circumstances that cannot be predicted
        - as a manager I determined the level of risk involved in setting up new displays
            i planned for staff, inventory, and budget
        -planning for occurences make the overall project managable
    -Unknowns
        - event that were not address when planning
    -A Risk Contingency Plan
        -this will enable managment to determine the potential risk involved , 
        then creating a alternatives
        - can still monitor the project to watch for trends that could lead to the execution
        of the risk contingency plan.

    steps for a contingency plan
        -Risk forecasting: projecting potential risks
        -Using a composite risk index: rates risks 1-5 based on severity and probability
        -Risk option evaluation: what options do we have to deal with the risk?
        -Contingency plan creation: put the plan in writing
        -Plan evaluation: evaluate the plan at various stages 
            of the project and make improvements
        -The risk matrix is continually updated to determine the ongoing threat from 
            risk addressed in the risk contingency plan.

### ___focus on:___

    -Risk is the danger involved in any situation, whether known or not.
    - A risk matrix is a visual aid to better see how risks affect operations. 
    -Variance is a common metric used in business to calculate risk. 
    -Contingency is a future event that has the possibility of happening but 
        cannot be predicted with certainty. 
    -Unknowns are events in a project's duration span that management was unable 
        to foresee as a risk event.
    -risk contingency plan, which will will enable management to determine the 
    potential risk involved, create alternative solutions to fixing the problem 
    if it should occur, and monitor the progress of a project to watch for trends 
    that could lead to the execution of the risk contingency plan
    
    -The steps include 
    1)risk forecasting, 
    2)using a composite risk index, 
    3)risk option evaluation, 
    4)contingency plan creation, 
    5)and plan evaluation.
        
 ###IT Disaster Planning & Recovery(DRP)
    recovering data and infrastructure in case of an Information 
    Technology (IT) system failure.
    
    businesses depend on electronic communications such as email and Voice Over IP (VOIP),
    and also for more critical operations like exchanging information and transmitting 
    data and payments.

    -What is an IT Disaster?
        -electronic data interchange(EDI): depends on hardware and software for day to day process 
        management and imformation comunication.

        -There are many ways in which sensitive data can be lost or destroyed, including hardware 
        crashes, human errors, viruses, hackers, or malware.
        -IT disasters should be avoided at all cost, securing data is esential to the organization

    -Internal Recovery Strategies
        all businesses should have a disaster recovery plan(DRP)
            1) creating an inventory of the hardware and software
            2)identifying critical information and plan to reqularly back up data
            3) having back-up computers and servers for re-installation
                and replication of critical software and data
            4) mirroring data and servers between two or more sites so
                that if one site fails the other site can take over
        *in the event of an IT disaster, the goal is to have the business up
            and running with minimal downtime and with little or no loss of data.
    -Vendor Supported Recovery Strategies
        -some buisnesses do not have the infustructure to maintain their
            own data
        -vedors provide software buisnesss owners can purchase to ensure
        that all data and 
    -Data Backup
    -Components of an DRP
##Ch 8. Network Auditing & Configuration


