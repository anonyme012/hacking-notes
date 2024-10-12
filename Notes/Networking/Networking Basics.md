## What is a Network  ? 

**A network is the connection between two devices or more that can exists in many shapes or sizes.**

A **device** can be : 
- a smartphone
- a PC
- a security camera
- a traffic light
- a TV
- a car
- etc.
## What is Internet ? 

Internet is a giant network with billions of devices separated in multiples smaller networks.

The first version of Internet was **ARPANET** in 1969 for the US defense.
But it's only on **1989** that was created the **World Wide Web** by Tim Berners-Lee and we started using it for information storage and sharing

A network can be of two types : 
- **public** network (Internet)
- **private** network (your messenger application).

![[Fig4.png]]
*A diagram of how Internet works (very) simply.*
## How the devices are identified in a Network ? 

A device have two ways to be identified : 
- an **IP** address
- a **MAC** (Media Access Control) Address.
#### IP address

IP : Internet Protocol
![[Fig5.png]]
*An IP address is divided into **4 octets** (numbers from 0 to 255) separated by **dots**.*

An IP address is calculated trought the **IP addressing & subnetting**. They can be the same for multiples devices but can only be used only by **one device** on the same network.

A device often have 2 IP addresses : 
- a **public IP** that is used to identify a device on Internet to send data (like a website or the content of a message) to him.
- a private IP that is used to differentiate a device amongst others.

Today, it's become harder to get an IP address that is not used. The numeration system of 4 octets can create $2^{32}$ IPs (4.29 billions) while we have, in 2024, more than 200 billions devices connected to Internet in the world.

To solve this shortage, IPv6 was created. It seems harder to implement, but : 
- we can create $2^{128}$ IPs (more than 340 trillions) what solves the problem
- it's more efficient due to new methodologies

![[Fig6.png]]
*Comparison between IPv4 and IPv6*
#### MAC address

Devices on a network will all have a physical network interface, which is a microchip board found on the device's motherboard. This network interface is assigned a unique address at the factory it was built at, called a **MAC** (**M**edia **A**ccess **C**ontrol) address.

The first six characters represent the company that made the network interface, and the last six is a unique number.

![[Fig7.png]]
*A MAC address is divided into **6 octets** (from 00 to ff) separated by "**colons"***

MAC addresses is that they can be faked or spoofed in a process known as **"spoofing"**.
**Example :** 
A firewall is configured to allow any communication going to and from the MAC address of the administrator. If a device were to pretend or "spoof" this MAC address, the firewall would now think that it is receiving communication from the administrator when it isn't.
## Ping (ICMP)

Don't started yet.
