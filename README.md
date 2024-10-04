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
- transmits eaw bit streams over physical medium e.g. cables, switches, NIC's


## 2. Data Link 
- Node - node data transfer 
- layer 1 is unordered 
- this layer puts the data into frames 
- MAC addresses - switches/bridges

## 3. Network Layer

- Determines how data is sent to recipient
- Manages routing through routers
- IP addresses/Routers

## 4. Transport

- TCP, UDP
- Provides reliable data transfer services to the upper layers 

## 5. Session Layer 

- Responsible for Establishing, Maintaining, Terminating session
- Session Managemnt Protocols

## 6. Presentation Layer

- Handles encryption
- AKA syntax layer
- Translates data between application and network layer
- SSL/TLS

## Application Layer

- End user layer
- Handles web browsing, file transfer, email
- HTTP(web), FTTP(File transfer), SMTP(mails)

## TCP/IP model 

![TCP/IP Model](/Images/TCP%3AIP%20model.png)

TOP
    Application - network applications and their protocols operate like HTTP, TLS, DNS
    Transport - End to end communication - TCP/IP
    Internet - Responsible for routing data between networks - IP
    Network Access Layer - Condensed format of Layer 1 and 2 of OSI model - encompasses physical and data link
BOTTOM
