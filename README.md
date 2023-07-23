# Computer Networking

Index of Content:
- [Internet](#internet)
    - [How is Internet Connected](#how-are-these-computers-connected)
- [World Wide Web (WWW)](#world-wide-web-www)
- [Difference between Internet and WWW](#difference-between-internet-and-www)
- [OSI Model](#osi-model)

- ### Internet

    - The Internet is a vast, global network of interconnected computer networks that communicate with each other using a standard set of protocols. It enables users to access a wealth of information, communicate with others across the globe, and engage in various forms of online activity.
    
    - At its core, the Internet is essentially a network of networks that connects millions of computers and devices worldwide. Each network may consist of a variety of different devices, such as servers, routers, switches, and modems, which all work together to transmit data and facilitate communication.

    - #### How are these Computers connected:
        - These Computers are connected to each other on the Internet through a combination of physical and logical connections.
        - At a physical level, the Internet is made up of a vast network of fiber optic cables, copper wires, and wireless connections that span the globe. These physical connections are maintained by a variety of entities, including Internet service providers (ISPs), telecommunications companies, and other infrastructure providers.
        - At a logical level, the Internet is composed of a series of interconnected networks, each with its own unique IP address. These networks are connected to each other through routers, switches, and other networking equipment that helps to direct traffic and ensure that data is sent to the correct destination.
        - When you connect to the Internet, your computer or device is assigned an IP address that is used to identify it on the network. This IP address is then used to send and receive data across the Internet, allowing you to access websites, send emails, and engage in other online activities.

- ### World Wide Web (WWW)

    - The **World Wide Web** is an **interconnected network of millions of computers and servers** all around the world that communicate with each other using a common set of **rules and protocols**, allowing people to access and share information and resources over the internet. 
    - The Web is made up of **billions of web pages** that are **stored** on these **computers and servers** and can be accessed through web browsers using unique addresses called **URLs** (Uniform Resource Locators).
    - When you access a website on the Web, your computer sends a request to the server where that website is stored, and the server sends back the information you requested.

- ### Difference between Internet and WWW

    - **Definition**: The internet is a global network of interconnected computer networks that allows communication between devices, while the World Wide Web is a collection of multimedia resources that are accessed through the internet using web browsers.
    - **Function**: The internet provides the infrastructure for communication between devices, while the World Wide Web provides a way to access and share information and resources, including text, images, videos, and other content.
    - **Scope**: The internet is a much broader concept than the World Wide Web, as it includes many other types of communication beyond accessing websites and resources, such as email, messaging, file transfer, and more.
    - **Summary**: the internet is the underlying global network of interconnected devices, while the World Wide Web is a specific application of the internet that allows users to access and share information and multimedia resources through web browsers.
    
- ### OSI Model

	- The OSI model is a conceptual framework that standardizes the functions of a communication system into seven distinct layers. Each layer represents a specific set of tasks and protocols that work together to enable communication between network devices. Here are the key points for each layer (from 7th layer to 1st layer): 
        - **Application Layer**:
            - The topmost layer that interacts directly with the **end-user** applications.
            - Provides services and protocols for tasks such as email, file transfer, and web browsing.
            - Examples of application layer **protocols** include HTTP, FTP, SMTP, and DNS.
            - Examples of application layer: Browsers, Messaging apps etc.
        - **Presentation Layer**:
            - Responsible for **data formatting**, **encryption**, and **compression**.
            - Converts the data received from the application layer into a standard **machine readable** binary format for transmission.
            - Handles encryption and decryption to ensure data security.
            - Example formats include ASCII, JPEG, and MPEG.
        - **Session Layer**:
            - Establishes, manages, and terminates communication sessions between applications.
            - Synchronizes dialogue between the sender and receiver.
            - Handles session checkpointing, recovery, and security.
        - **Transport Layer**:
            - Ensures reliable, error-free, and orderly delivery of data between end systems.
            - Establishes and terminates connections between devices.
            - Segments and reassembles data into manageable units.
            - Examples of transport layer protocols are TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
        - **Network Layer**:
            - Focuses on the **logical addressing** and **routing** of data across multiple networks.
            - Translates logical addresses (e.g., IP addresses) into physical addresses (e.g., MAC addresses).
            - Routing protocols, such as IP (Internet Protocol), operate at this layer to determine the optimal path for data transmission.
        - **Data Link Layer**:
            - Responsible for the **reliable transmission** of data between directly connected network nodes.
            - Divided into two sublayers: the Logical Link Control (LLC) sublayer and the Media Access Control (MAC) sublayer.
            - LLC provides flow control and error checking.
            - MAC controls access to the physical medium and handles addressing (e.g., MAC addresses).
        - **Physical Layer**:
            - The lowest layer of the OSI model.
            - Deals with the physical **transmission** of data over the network.
            - Concerned with the electrical, mechanical, and physical aspects of network interfaces.
            - Examples of physical layer components include cables, connectors, network interface cards (NICs), and modulation techniques.
	- The OSI model serves as a reference for understanding network protocols and their interactions. In practice, most networks use the **TCP/IP** protocol suite, which combines several OSI layers into fewer layers.