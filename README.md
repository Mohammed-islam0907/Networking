# Networking

## Overview of computer network
- **Network: A group of devices connected to allow data to be shared**

## LAN & WAN
- LAN - home wifi for e.g. 
- LAN used for connecting devices in single locations

- WAN - e.g. internet 
- connects multiple LAN's

## Switches, Routers and Firewalls

- Switches connect devices and manages data within same network 
- Routers connect devices in different networks
- Firewalls Acts like a security guard - monitors and controls incoming and outgoing traffic based on security rules and protects network from unauthorised access

## IP & MAC address
 ### IP addresses:

- 2 types: IPv4, IPv6

### IPv4: four decimal numbers seperated by dots - 32 bit address

### IPv6: eight groups of four hexadecimal digits (numbers 0-9 & letters A-f) - 128 but address

## MAC Addresses 

- 48 bit address 
- displayed in hexadecimal format 
- Operate at the data link layer 
- helps devices communicate with each other on a local network
- node - node transfer
- Essential in making sure your device connects to the right router 


## Ports & Protocols

- **Ports: Facilitates communication between devices**
- like logical doors for devices 
- When computer wants to send/receive data it uses these ports

- **Protocols: Ensure devices communicate effectively by following same set of rules**
- like languages devices use to communicate with eachother
- 

## **Ports:**

1. **TCP: Transmission Control Protocol**
    - Like postman of the internet
    - ensures that data sent from one devices reaches another device 
    - Before data is sent, **connection must be established**
    - Requires "Handshake" - ensures both devices are ready to send and receive data   
    - **Reliable** - ensures all data is received on the other end
    - ensures data is delivered in correct order
    - checks for errors in data 
    - Used whenever 2 devices need to exchange data back and forth e.g. emails

2. UDP: User Datagram Protocol
    - Simple protocol to senfd and receive 
    - Prior communicatio not needed
    - fast but less reliable
    - Used for real -time applications e.g. Facetime/Games
    - DNS
    - VPN

![TCP vs UDP](Images/TCP%20vs%20UDP.png) 


## Introduction to the **OSI Model**

### **7 Layers:**

7. Application - Network services are given directly to applications
6. Presentation - Data is translated to readable format 
5. Sessions 
4. Transport - End to end communication - TCP/UDP
3. Network - Routing and forwarding data packets manages
2. Data Link - Node to node transfer (switches/ethernet)
1. Physical - Physical structure - Fibre, wireless.. 

![7 Layer](/Images/OSI.png)


## 1. **Physical** 
- Deals with the physical components of network communication like cables, switches, and routers.
- Ethernet, USB, Bluetooth, Fibre optic cables

## 2. Data Link 
- Ensures reliable transmission of data across physical network
- Manages how devices on a network can access 
- Switches -Switching

## 3. Network Layer

- Handles movement of packets from sender to receiver
- IP addresses, Routers - routing

## 4. Transport

- Provides reliable data transfer services to the upper layers 
- Establishes rnd to end communication and data reliability
- TCP, UDP
## 5. Session Layer 

- Responsible for Establishing, Maintaining, Terminating session
- Session Managemnt Protocols - NFS, SQL

## 6. Presentation Layer

- Makes sure data is in useable format 
- Where encryption occurs
- SSL/TLS

## Application Layer

- End user layer
- Provides network services to user
- Handles web browsing, file transfer, emails etc.
- HTTP(web), FTP(File transfer), SMTP(mails)

## TCP/IP model 

![TCP/IP Model](/Images/TCP%3AIP%20model.png)

- A simplified version of OSI model - used in intenret  communication
- 4 layers:
TOP
    Application - network applications and their protocols operate like HTTP, TLS, DNS
    Transport - End to end communication - TCP/IP
    Internet - Responsible for routing data between networks - IP
    Network Access Layer - Encompasses physical and data link layer of the OSI model 
BOTTOM


