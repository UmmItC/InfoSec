---
title: "L1 - Computer Systems and Network Protocol Essentials"
date: 2024-09-16T20:09:41+0800
tags: ["Computer Systems and Network Protocol Essentials", "Basic Concept", "L1", "School Course"]
---

## What the heck is Network?

## Networks of Many Sizes

Of the size, idk how to define it, there should no be a strict definition of the size of a network. You can say more than 300 devices is a small or even large network, that should not be the no absolute definition of the size of a network. But, we can still have a rough idea of the size of a network. here are some examples:

### Small Home / Office Networks

1. Typically involve a few devices (e.g., computers, printers, smartphones).

2. Often use a single router or switch to connect devices.

3. Network management is relatively simple and often handled by a single individual.

### Medium to Large Networks

1. Include more devices, potentially spanning multiple floors or buildings.

2. May require multiple routers, switches, and access points to manage network traffic.

3. Often involve more complex network management, including VLANs (Virtual Local Area Networks) and network segmentation.

### World Wide Network

1. Refers to the global network infrastructure, including the Internet.

2. Consists of a vast number of interconnected networks (ISPs, data centers, etc.).

3. Requires sophisticated protocols and systems to manage data traffic and connectivity on a global scale.

## Clients and Servers

In a network, **people (clients)** are like individuals who need access to various rooms (servers). They knock on doors (send requests) to enter these rooms and obtain the resources or services they require. 

For instance, when someone uses a web browser to visit a website or checks their email, they are acting as clients. On the other hand, **rooms (servers)** are like spaces that offer resources or services. These rooms have doors (ports) that open in response to requests from people (clients). 

When a request is made, the room provides the necessary information or service. However, if a room (server) receives too many requests at once—meaning many people are trying to enter simultaneously—it can become overwhelmed. Just like a room that is overcrowded might slow down or even be unable to accommodate more people, a server under heavy load may respond slowly or fail to provide the requested services altogether.

## Peer-to-Peer networks

Peer-to-Peer (P2P) networking is like a group chat in messaging apps like WhatsApp or Telegram. In a P2P network, every participant (or peer) can act both as a client and a server. This means that every person in the group chat has their own `room` (server) and can share resources or information directly with others without needing a central authority. When you send a message, it's sent directly from your `room` to your friend's `room,` and vice versa. There isn't a central server managing all the messages

instead, every peer handles its own communication and contributes to the network. This is different from the traditional client-server model, where clients request services from a centralized server. In the P2P model, every peer is equal and helps to manage and share resources within the network.

## End devices

An end device refers to a hardware component in a network that acts as either a source or destination for data transmission. These devices are integral to communication networks, allowing users to interact with the system. Examples of end devices include:

- **Computers** (workstations, laptops, desktops)
- **Mobile Devices** (smartphones, tablets)
- **Peripherals** (printers, scanners)
- **Servers** (file servers, web servers)

End devices can be classified into two main categories:

1. **Clients**: These devices request data from servers and display the received information. They typically run applications like web browsers.
  
2. **Servers**: These devices provide data and services to clients, such as hosting websites or managing emails.

End devices are often referred to as "end systems" or "end stations" because they sit at the edge of the network, directly interfacing with users. They are crucial for the functioning of the Internet and local networks, as they facilitate data communication between users and services

## Intermediary Network devices

In the world of networking, intermediary network devices and network media are key to keeping everything connected and working smoothly. 

**Intermediary network devices** are crucial for linking different networks together. They help data travel from one network to another, making sure it reaches the right place. These devices also connect individual devices, like computers and printers, to the network. Their main job is to manage data flow and provide the connections needed for the network to function properly.

**Network media** refers to the physical paths that data travels along. Choosing the right type of network media affects how fast and how far data can go. There are three main types of network media:

1. **Copper Cables**: These are common and include types like Ethernet cables (Cat5e, Cat6). They use electrical signals to send data. Copper cables are affordable and easy to install, but they have limits on speed and distance.

2. **Fiber Optic Cables**: These cables use light signals to transmit data, allowing for very high speeds and long distances. They are perfect for high-performance networks where speed and reliability are important.

3. **Wireless Media**: This includes technologies like Wi-Fi, Bluetooth, and cellular networks. Wireless media use radio waves to send data, providing flexibility and mobility. However, they can be affected by interference and may not offer the same speed and range as wired connections.

In short, intermediary network devices connect different networks and manage data flow, while network media provides the pathways for data transmission. Understanding these components helps in setting up and maintaining effective network systems.

## Network Media: Types and Functions

Network media are essential for transmitting data and connecting devices in a network. They provide the pathways that data travels along and help interconnect various devices.

There are three main types of network media:

1. **Copper Cables**: These use electrical signals to send data. They are common and include Ethernet cables like Cat5e and Cat6. Copper cables are cost-effective but are limited in speed and distance.

2. **Fiber Optic Cables**: These use light signals to transmit data, which allows for very high speeds and long-distance communication. Fiber optic cables are ideal for high-performance networks.

3. **Wireless Media**: This includes technologies like Wi-Fi, Bluetooth, and cellular networks. Wireless media use radio waves to transmit data, offering flexibility and mobility, though they can be affected by interference and generally have lower speed compared to wired options.

Each type of network media has its own strengths and is chosen based on the specific needs of the network.

I understand where you're coming from. In networking, "physical" and "logical" diagrams do indeed refer to different aspects of the network, but they aren't directly about security layers. Here's a clear explanation of these concepts:

## Network Components

When discussing network components, it's important to differentiate between network representations and the aspects of network topology. 

**Network Representations** involve using symbols and diagrams to illustrate how a network is organized and how its components interact. These diagrams help in planning, managing, and troubleshooting networks.

1. **Symbols in Network Diagrams**:
   - **Symbols** represent various network devices and connections. For example, a symbol might represent a router, switch, or computer, while lines connecting these symbols represent network cables or wireless connections. Understanding these symbols is crucial for interpreting network diagrams correctly.

2. **Topology Diagrams**:
   - **Physical Topology**: This focuses on the actual layout of cables and devices. It shows how devices are physically connected to each other with cables. For example, it depicts how cables run from one device to another and how they are arranged in a data center or office.
   - **Logical Topology**: This deals with the flow of data within the network. It illustrates how data moves between devices and how the network is logically organized, regardless of the physical connections. This helps in understanding how network protocols and data routes are designed to facilitate communication.

**Physical vs. Logical Topology**

- **Physical Topology**: This is concerned with the actual physical setup. It includes details about the types of cables used, the placement of network hardware (like switches and routers), and the physical arrangement of these components. For example, it shows where LAN cables are plugged into switches and routers. The physical layer is more about how devices are physically connected and doesn't inherently involve security or authentication.

- **Logical Topology**: This is more about how data flows through the network and how network services are structured. It describes the paths data takes as it travels from one device to another, including how network traffic is routed and managed. Logical topology focuses on the abstract representation of the network, which helps in understanding data flow and network design.

**Security and Access**

While the physical topology itself does not directly address security, physical access to network devices can impact security. For instance:
- **Physical Access**: If someone can physically connect a device to the network (like plugging into a LAN port), they might gain unauthorized access if there are no proper security measures in place.
- **Logical Access**: Security measures are often more relevant here, involving authentication, encryption, and access control to manage and protect data flow within the network.

In summary, **physical topology** refers to the actual hardware and connections, while **logical topology** refers to how data flows within the network. Both are crucial for understanding network design and management, though they address different aspects of network organization and operation.

## LANS AND WANS

Local Area Networks (LANs) and Wide Area Networks (WANs) are two common types of networks used in modern computing. They differ in terms of their size, scope, and the technologies used to connect devices.

### Local Area Networks (LANs)

- **Size**: LANs are typically confined to a small geographic area, such as a single building or campus. They are used to connect devices like computers, printers, and servers within a limited area.

- **Scope**: LANs are designed for high-speed communication and are often used for sharing resources like files, printers, and internet access among users in a local setting.

- **Technologies**: LANs commonly use Ethernet cables or Wi-Fi to connect devices. They are usually managed by a single organization or individual and are relatively easy to set up and maintain.

### Wide Area Networks (WANs)

- **Size**: WANs cover a larger geographic area, such as multiple cities, countries, or even continents. They connect LANs over long distances, allowing users in different locations to communicate and share resources.

- **Scope**: WANs are designed for long-distance communication and often use public or private networks to connect devices across vast distances. They enable global connectivity and support services like internet access, email, and cloud computing.

- **Technologies**: WANs use a variety of technologies, including leased lines, satellite links, and virtual private networks (VPNs), to connect devices over long distances. They require more complex infrastructure and management compared to LANs.

## Internet Connections and Access Technologies

**1. Internet Service Provider (ISP)**
   - **Role**: An ISP is a company that provides individuals and organizations with access to the internet. They offer various types of internet connections, each with different speeds, capacities, and features.

**2. Types of Internet Access Technologies**

   - **Broadband Cable**:
     - **Description**: Uses coaxial cables to deliver high-speed internet. It is commonly used in homes and small offices.
     - **Features**: High speeds, reliable performance, often includes bundled TV services.

   - **Broadband Digital Subscriber Line (DSL)**:
     - **Description**: Uses telephone lines to provide internet access. It comes in different speeds, with higher speeds available for premium plans.
     - **Features**: Typically provides a separate channel for voice and data, but speeds are usually lower compared to cable.

   - **Wireless WANs (Wide Area Networks)**:
     - **Description**: Provides internet access over a broad area using wireless technology. Examples include fixed wireless and satellite internet.
     - **Features**: Can cover large areas and is useful in regions where traditional wired connections are unavailable.

   - **Mobile Services**:
     - **Description**: Provides internet access through cellular networks (e.g., 4G, 5G).
     - **Features**: Offers mobility and flexibility, allowing internet access from various locations using mobile devices.

   - **Business DSL**:
     - **Description**: A variant of DSL specifically designed for business use, offering higher speeds and better reliability compared to residential DSL.
     - **Features**: Enhanced performance, often includes service level agreements (SLAs) for guaranteed uptime and support.

   - **Leased Lines**:
     - **Description**: Dedicated high-speed lines leased from an ISP. They provide a continuous and exclusive connection between two locations.
     - **Features**: High reliability and speed, often used by businesses for critical applications requiring guaranteed bandwidth.

   - **Metro Ethernet**:
     - **Description**: Provides Ethernet connectivity over a metropolitan area network. It is used to connect multiple locations within a city or region.
     - **Features**: Scalable, high-speed connectivity, often used by businesses to link offices or data centers.

**3. Types of Internet Connections**

   - **Home and Small Office**:
     - **Common Technologies**: Broadband cable, DSL, wireless WANs, and mobile services.
     - **Features**: Generally focus on providing adequate speed and reliability for typical household or small business needs. Options vary based on location and availability.

   - **Business**:
     - **Common Technologies**: Business DSL, leased lines, metro Ethernet.
     - **Features**: Designed for higher performance, reliability, and scalability. Often include dedicated support and service level agreements to ensure continuous operation and address the higher demands of business environments.


## Converged Networks vs. Traditional Separate Networks

**Traditional Separate Networks**

In traditional networking setups, various types of communication—such as data, voice, and video—are handled by separate networks. Each type of network operates independently, with its own set of rules, infrastructure, and management practices. 

- **Data Networks**: Typically handle internet and intranet traffic, using technologies like Ethernet or Wi-Fi.
- **Voice Networks**: Often managed through dedicated telephone systems, such as Private Branch Exchanges (PBX) or traditional telephone lines.
- **Video Networks**: Handle video conferencing or broadcasting, usually requiring separate systems and bandwidth management.

This separation means that managing and maintaining multiple networks can be complex and costly. Each network requires its own hardware, configuration, and troubleshooting, leading to inefficiencies and higher expenses.

**The Converged Network**

A converged network integrates data, voice, and video services into a single network infrastructure. This means that all types of communication can be transmitted over the same network, using a unified set of rules and technologies.

- **Unified Infrastructure**: A converged network uses a single set of network devices (routers, switches, etc.) and cabling to handle all types of traffic. This simplifies network management and reduces costs.
- **Integrated Services**: Voice over IP (VoIP) and video conferencing can be delivered alongside traditional data services over the same network. This integration enhances communication efficiency and supports advanced features.
- **Enhanced Efficiency**: By consolidating various services, a converged network can optimize bandwidth usage and improve overall network performance. It also streamlines troubleshooting and maintenance tasks.

**Benefits of Converged Networks**

- **Cost Savings**: Reduces the need for separate infrastructure and maintenance for different types of communication.
- **Simplified Management**: One network to manage instead of multiple, making administration and support more straightforward.
- **Improved Communication**: Seamless integration of voice, video, and data improves collaboration and operational efficiency.
- **Scalability**: Easier to expand and adapt to new technologies or increased demand with a unified network approach.

In summary, while traditional separate networks handle data, voice, and video communication through distinct systems, a converged network integrates all these services into a single infrastructure. This approach simplifies network management, reduces costs, and enhances overall communication efficiency.

## Key Characteristics of a Reliable Network Architecture

To ensure a network is dependable and performs well, it should have the following four fundamental characteristics:

1. **Fault Tolerance**
   - **Definition**: The ability of a network to continue functioning properly even when there is a failure in some of its components.
   - **Importance**: Fault tolerance minimizes downtime and ensures that services remain available if hardware or software issues occur. This is typically achieved through redundancy, such as backup servers, multiple network paths, and failover mechanisms.

2. **Scalability**
   - **Definition**: The capability of a network to grow and accommodate increasing numbers of users, devices, or data traffic without compromising performance.
   - **Importance**: Scalability ensures that a network can handle growth efficiently. As demands increase, a scalable network can be expanded with minimal disruption and without needing a complete redesign.

3. **Quality of Service (QoS)**
   - **Definition**: The ability to prioritize certain types of network traffic to ensure that critical applications receive the necessary bandwidth and performance.
   - **Importance**: QoS is crucial for maintaining the performance of high-priority applications such as VoIP or video conferencing. By managing bandwidth allocation and reducing latency, QoS helps to ensure that network services are reliable and meet the required performance standards.

4. **Security**
   - **Definition**: The measures and protocols in place to protect the network from unauthorized access, attacks, and other security threats.
   - **Importance**: Security is vital for safeguarding sensitive data and ensuring the integrity of network operations. This includes implementing firewalls, encryption, access controls, and regular security updates to defend against potential threats.

**Summary**

A reliable network architecture is defined by its **fault tolerance** (ability to handle failures gracefully), **scalability** (capacity to grow and adapt), **Quality of Service (QoS)** (ensuring performance for critical applications), and **security** (protecting against threats). These characteristics are essential for creating a robust and dependable network environment that can support business operations and user needs effectively.

## Current Trends in Networking

As technology evolves, several key trends are shaping the future of network management and usage. Here are four significant trends currently impacting networks:

1. **Bring Your Own Device (BYOD)**
   - **Description**: BYOD refers to the practice where employees use their personal devices (such as smartphones, tablets, and laptops) for work purposes.
   - **Impact**: This trend increases flexibility and productivity, as employees can work from anywhere using their preferred devices. However, it also presents challenges in terms of security and network management. Organizations need to implement robust policies and security measures to protect data and ensure that personal devices do not introduce vulnerabilities into the network.

2. **Online Collaboration**
   - **Description**: Online collaboration tools and platforms enable teams to work together remotely, sharing documents, projects, and communications in real time.
   - **Impact**: These tools facilitate more efficient teamwork and streamline workflows, particularly in remote or hybrid work environments. Popular tools include platforms like Microsoft Teams, Slack, and Google Workspace. Ensuring these tools are integrated seamlessly into the network and managing their performance is crucial for maintaining productivity.

3. **Video Communications**
   - **Description**: Video communication technology, such as video conferencing and virtual meetings, has become increasingly common for personal and professional interactions.
   - **Impact**: Video communications enhance real-time collaboration and can reduce the need for travel. However, they require significant bandwidth and network reliability to ensure clear, uninterrupted video and audio. Networks must be optimized to handle the high data demands of video streaming and conferencing.

4. **Cloud Computing**
   - **Description**: Cloud computing involves using remote servers hosted on the internet to store, manage, and process data, rather than relying on local servers or personal devices.
   - **Impact**: Cloud computing offers scalability, flexibility, and cost savings by allowing organizations to access powerful resources and services on-demand. It supports various applications, from file storage to complex data processing. Networks need to be robust and secure to handle cloud traffic and protect data in transit and at rest.

**Summary**

These trends—**Bring Your Own Device (BYOD)**, **Online Collaboration**, **Video Communications**, and **Cloud Computing**—are transforming how networks are used and managed. They drive greater flexibility and efficiency but also require careful attention to security, bandwidth management, and overall network performance to ensure a smooth and secure user experience.

## Networking Technologies for the Home

As technology continues to advance, various networking technologies are becoming increasingly important for home connectivity. Here’s an overview of key technologies and trends:

### **Technology Trends in the Home**

1. **Smart Home**
   - **Description**: Smart home technology refers to a network of interconnected devices and systems that can be controlled remotely. This includes smart lighting, thermostats, security cameras, and home assistants like Amazon Alexa or Google Home.
   - **Impact**: Smart home devices enhance convenience, energy efficiency, and security by allowing homeowners to automate and remotely manage various aspects of their home. Effective networking is crucial for ensuring these devices communicate seamlessly and operate reliably.

### **Networking Technologies**

1. **Powerline Networking**
   - **Description**: Powerline networking uses existing electrical wiring in a home to connect devices to the network. This technology involves plugging adapters into electrical outlets to create a network connection through the home's wiring.
   - **Advantages**: 
     - Utilizes existing electrical infrastructure, reducing the need for additional cabling.
     - Can extend network connectivity to areas of the home where Wi-Fi signals might be weak.
   - **Considerations**: Performance can be affected by the quality of the electrical wiring and potential interference from other devices on the same circuit.

2. **Wireless Broadband**
   - **Wireless Internet Service Provider (WISP)**:
     - **Description**: WISP provides internet access via wireless signals instead of traditional wired connections. This is often used in areas where wired infrastructure is limited or unavailable.
     - **Advantages**: 
       - Flexible and can cover large areas without needing extensive cabling.
       - Useful for rural or remote locations where traditional broadband might not be feasible.
   - **Wireless Broadband Service using Cellular Technology**:
     - **Description**: Utilizes cellular networks (e.g., 4G, 5G) to deliver internet services. This can be an alternative to traditional broadband for both urban and rural areas.
     - **Advantages**:
       - Provides high-speed internet access using cellular towers.
       - Ideal for mobile users or as a backup internet connection.
     - **Considerations**: Performance can vary based on signal strength and network congestion. 

**Summary**

For modern homes, networking technologies like **powerline networking** and **wireless broadband** offer versatile solutions for connecting devices and providing internet access. As homes increasingly adopt **smart home** technologies, effective and reliable network connectivity becomes essential. Understanding these technologies helps homeowners make informed decisions about their networking needs and ensures seamless connectivity throughout their living spaces.

## Network Security: Threats and Solutions

In the realm of network security, it’s crucial to understand both the various threats that can compromise network integrity and the solutions available to mitigate these risks. Here’s a detailed look at common security threats and effective security solutions.

### **Security Threats**

1. **Viruses, Worms, and Trojan Horses**
   - **Viruses**: Malicious software that attaches itself to legitimate files and programs, spreading when those files are shared or executed.
   - **Worms**: Standalone malicious programs that replicate themselves to spread across networks without needing to attach to other files.
   - **Trojan Horses**: Malicious software disguised as legitimate applications. They often create backdoors for unauthorized access.

2. **Spyware and Adware**
   - **Spyware**: Software designed to gather information about a user without their consent, often by tracking their online activities.
   - **Adware**: Software that automatically delivers unwanted ads, sometimes bundled with spyware. It can slow down systems and compromise privacy.

3. **Zero-Day Attacks**
   - **Description**: Attacks that exploit vulnerabilities in software or hardware that are not yet known to the vendor or the public.
   - **Impact**: Since there are no patches or fixes available at the time of the attack, these threats can be particularly dangerous and hard to defend against.

4. **Hacker Attacks**
   - **Description**: Unauthorized access attempts by individuals or groups to exploit vulnerabilities for various malicious purposes, such as data theft or system damage.
   - **Impact**: Hackers may steal sensitive data, disrupt services, or cause other forms of damage.

5. **Denial of Service (DoS) Attacks**
   - **Description**: Attacks that flood a network or server with excessive traffic, overwhelming its resources and rendering it unavailable to legitimate users.
   - **Impact**: Can cause downtime and disrupt services, affecting business operations and user access.

6. **Data Interception and Theft**
   - **Description**: Unauthorized access to data as it is transmitted over a network, often through methods such as packet sniffing or man-in-the-middle attacks.
   - **Impact**: Can lead to the exposure of sensitive information, including personal and financial data.

7. **Identity Theft**
   - **Description**: The unauthorized acquisition and use of someone’s personal information, such as Social Security numbers or credit card details, typically to commit fraud.
   - **Impact**: Can result in financial loss and damage to personal and professional reputations.

### **Security Solutions**

1. **Antivirus and Antispyware**
   - **Antivirus**: Software designed to detect, prevent, and remove malicious software like viruses and worms.
   - **Antispyware**: Software specifically designed to detect and remove spyware and adware.

2. **Firewall Filtering**
   - **Description**: Uses rules to control incoming and outgoing network traffic, blocking unauthorized access while allowing legitimate communication.
   - **Impact**: Provides a barrier between a network and potential threats from external sources.

3. **Dedicated Firewall Systems**
   - **Description**: Hardware or software systems specifically designed to offer advanced firewall protection, often providing more robust security features than basic firewalls.
   - **Impact**: Offers enhanced protection through more sophisticated filtering and monitoring capabilities.

4. **Access Control Lists (ACLs)**
   - **Description**: Lists of rules used to control access to network resources based on IP addresses, protocols, or ports.
   - **Impact**: Helps enforce security policies by specifying who can access what resources and under what conditions.

5. **Intrusion Prevention Systems (IPS)**
   - **Description**: Monitors network traffic for signs of malicious activity and can take automatic actions to prevent or block these threats.
   - **Impact**: Provides real-time protection by detecting and responding to potential intrusions.

6. **Virtual Private Networks (VPNs)**
   - **Description**: Creates a secure, encrypted connection over a public network (such as the internet) to protect data in transit and maintain privacy.
   - **Impact**: Ensures that communications between remote users and the network are secure from eavesdropping and interception.

**Summary**

Effective network security involves understanding and addressing various threats such as **viruses, spyware, zero-day attacks, hacker attacks, denial of service, data interception, and identity theft**. Implementing security solutions like **antivirus software, firewalls, ACLs, IPS, and VPNs** helps to protect against these threats and safeguard network integrity. By staying vigilant and proactive, organizations can maintain a secure network environment and protect their data and resources.


## Terms and Commands

### **1. Networking Terms**

| **Terms**                            |
|--------------------------------------|
| client                               |
| collaborative learning spaces        |
| global communities                   |
| human network                        |
| network collaboration services       |
| network of networks                  |
| peer-to-peer network                 |
| server                               |

### **2. Networking Devices and Technologies**

| **Devices and Technologies**          |
|---------------------------------------|
| broadband cable                       |
| broadband DSL                         |
| business DSL                          |
| cable                                 |
| cellular                               |
| dedicated leased line                 |
| dial-up telephone                     |
| DSL                                    |
| end devices                           |
| extranet                               |
| hardware                               |
| intermediary devices                  |
| internetworking devices               |
| Internet Service Provider (ISP)       |
| Intranet                               |
| leased lines                          |
| Local Area Network (LAN)              |
| logical topology diagrams             |
| medium                                 |
| Metropolitan Area Network (MAN)       |
| metro Ethernet                        |
| network access devices                |
| network interface card (NIC)          |
| network media                         |
| physical port, interface              |
| physical topology diagrams            |
| satellite                              |
| security devices                      |
| service provider (SP)                 |
| software                               |
| Storage Area Network (SAN)            |
| TelePresence endpoint                 |
| teleworkers                            |
| topology diagram                      |
| VoIP phones                           |
| Wide Area Network (WAN)               |
| Wireless LAN (WLAN)                   |

### **3. Networking Concepts and Security**

| **Concepts and Security**              |
|----------------------------------------|
| availability                           |
| circuit switched networks              |
| content security                       |
| converged network                      |
| data confidentiality                   |
| data integrity                         |
| delay                                  |
| Denial of Service (DoS)                |
| encrypting data                        |
| fault tolerance                        |
| hierarchical layered structure         |
| intelligent information network        |
| network architecture                   |
| network bandwidth                      |
| network congestion                    |
| network infrastructure security        |
| packet loss                            |
| packet switched networks               |
| packets                                |
| Quality of Service (QoS)               |
| queue                                  |
| redundancy                             |
| routing function                       |
| scalability                            |
| user authentication                    |
