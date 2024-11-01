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

The type of a network is caracterized by its **size** : 
- **Small Home Networks** : Small home networks connect a few computers to each other and to the internet.
- **Small Office and Home Office Networks** : The SOHO network allows computers in a home office or a remote office to connect to a corporate network, or access centralized, shared resources.
- **Medium to Large Networks** : Medium to large networks, such as those used by corporations and schools, can have many locations with hundreds or thousands of interconnected hosts.
- **World Wide Networks** : The internet is a network of networks that connects hundreds of millions of computers world-wide.
## What is Internet ? 

Internet is a giant network with billions of devices separated in multiples smaller networks.

The first version of Internet was **ARPANET** in 1969 for the US defense.
But it's only on **1989** that was created the **World Wide Web** by Tim Berners-Lee and we started using it for information storage and sharing

A network can be of two types : 
- **public** network (Internet)
- **private** network (your messenger application).

![[Pictures/Fig4.png]]
*A diagram of how Internet works (very) simply.*
## Types of Devices

There is a large variety of devices thant can be connected to Internet, not only your PC.
#### Mobile Devices

 - **Smartphone** : Smartphones are able to connect to the internet from almost anywhere. Smartphones combine the functions of many different products together, such as a telephone, camera, GPS receiver, media player, and touch screen computer.
 - **Tablet** : Tablets, like smartphones, also have the functionality of multiple devices. With the additional screen size, they are ideal for watching videos and reading magazines or books. With on-screen keyboards, users are able to do many of the things they used to do on their laptop computer, such as composing emails or browsing the web.
 - **Smartwatch** : A smartwatch can connect to a smartphone to provide the user with alerts and messages. Additional functions, such as heart rate monitoring and counting steps, like a pedometer, can help people who are wearing the device to track their health.
 - **Smart Glasses** : A wearable computer in the form of glasses, such as Google Glass, contains a tiny screen that displays information to the wearer in a similar fashion to the Head-Up Display (HUD) of a fighter pilot. A small touch pad on the side allows the user to navigate menus while still being able to see through the smart glasses.
![[Pictures/Fig11.png]]
#### Connected Home Devices

- **Security System** : Many of the items in a home, such as security systems, lighting, and climate controls, can be monitored and configured remotely using a mobile device.
- **Appliances** : Household appliances such as refrigerators, ovens, and dishwashers can be connected to the internet. This allows the homeowner to power them on or off, monitor the status of the appliance, and also be alerted to preset conditions, such as when the temperature in the refrigerator rises above an acceptable level.
- **Smart TV** : A smart TV can be connected to the internet to access content without the need for TV service provider equipment. Also, a smart TV can allow a user to browse the web, compose email, or display video, audio, or photos stored on a computer.
- **Gaming Console** : Gaming consoles can connect to the internet to download games and play with friends online.
![[Pictures/Fig10.png]]
#### Other Connected Device

- **Smart Cars** : Many modern cars can connect to the internet to access maps, audio and video content, or information about a destination. They can even send a text message or email if there is an attempted theft or call for assistance in case of an accident. These cars can also connect to smartphones and tablets to display information about the different engine systems, provide maintenance alerts, or display the status of the security system.
- **RFID Tags** : Radio frequency identification (RFIDs) tags can be placed in or on objects to track them or monitor sensors for many conditions.
- **Sensors and Actuators** : Connected sensors can provide temperature, humidity, wind speed, barometric pressure, and soil moisture data. Actuators can then be automatically triggered based on current conditions. For example, a smart sensor can periodically send soil moisture data to a monitoring station. The monitoring station can then send a signal to an actuator to begin watering. The sensor will continue to send soil moisture data allowing the monitoring station to determine when to deactivate the actuator.
- **Medical Devices** : Medical devices such as pacemakers, insulin pumps, and hospital monitors provide users or medical professionals with direct feedback or alerts when vital signs are at specific levels.
![[Pictures/Fig9.png]]
## How the devices are identified in a Network ? 

A device have two ways to be identified : 
- an **IP** address
- a **MAC** (Media Access Control) Address.
#### IP address

IP : Internet Protocol
![[Pictures/Fig5.png]]
*An IP address is divided into **4 octets** (numbers from 0 to 255) separated by **dots**.*

An IP address is calculated trought the **IP addressing & subnetting**. They can be the same for multiples devices but can only be used only by **one device** on the same network.

A device often have 2 IP addresses : 
- a **public IP** that is used to identify a device on Internet to send data (like a website or the content of a message) to him.
- a private IP that is used to differentiate a device amongst others.

Today, it's become harder to get an IP address that is not used. The numeration system of 4 octets can create $2^{32}$ IPs (4.29 billions) while we have, in 2024, more than 200 billions devices connected to Internet in the world.

To solve this shortage, IPv6 was created. It seems harder to implement, but : 
- we can create $2^{128}$ IPs (more than 340 trillions) what solves the problem
- it's more efficient due to new methodologies

![[Pictures/Fig6.png]]
*Comparison between IPv4 and IPv6*
#### MAC address

Devices on a network will all have a physical network interface, which is a microchip board found on the device's motherboard. This network interface is assigned a unique address at the factory it was built at, called a **MAC** (**M**edia **A**ccess **C**ontrol) address.

The first six characters represent the company that made the network interface, and the last six is a unique number.

![[Pictures/Fig7.png]]
*A MAC address is divided into **6 octets** (from 00 to ff) separated by "**colons"***

MAC addresses is that they can be faked or spoofed in a process known as **"spoofing"**.
**Example :** 
A firewall is configured to allow any communication going to and from the MAC address of the administrator. If a device were to pretend or "spoof" this MAC address, the firewall would now think that it is receiving communication from the administrator when it isn't.
## What is a Data ? 
#### Data Types

We can sort datas by how they were collected : 
- **Volunteer Data**: Data actively provided by users or individuals (e.g., filling out forms, answering surveys, or providing feedback).
- **Inferred Data**: Data derived by analyzing existing information to make conclusions or predictions about individuals, without them explicitly providing it (e.g., behavior patterns or preferences inferred from usage data).
- **Observed Data**: Data collected through passive observation of user behavior, actions, or interactions, without direct input from the use (e.g., website clickstreams, GPS locations, or sensor readings).
#### Bits and Bytes

In computing, a **bit** (short for binary digit) is the **smallest unit of data**. A bit can have one of two possible values: **0** or **1**. These values represent a **binary** system, where 0 typically stands for *false* or *off*, and 1 stands for *true* or *on*.

Bits are the foundation of all digital data. Multiple bits can be **combined** to represent more complex data types such as numbers, characters, or instructions. 
###### Bits Groups

**8 bits = 1 byte** : A byte can represent **256** different values (from 0 to 255 in decimal).
- `00000000` in binary is equal to `0` in decimal.
- `11111111` in binary is equal to `255` in decimal.
###### Characters in binary

- **ASCII** uses 7 or 8 bits for each character, such as `A` = `01000001`.
- **Unicode** uses variable-length encoding (16, 32 bits, etc.) to represent a broader range of characters from different languages, such as the Japanese `あ` = `00110000 01000010` or the musical symbol `𝄞` = `00000000 00011101 00010001 00011110`.
#### Data transfer ways

They are many ways to transfer a data : 
- **Electrical signals -** Transmission is achieved by representing data as electrical pulses on copper wire.
- **Optical signals -** Transmission is achieved by converting the electrical signals into light pulses.
- **Wireless signals -** Transmission is achieved by using infrared, microwave, or radio waves through the air.
## Debit and Bandwidth
#### Debit

In networking, **debit** refers to the rate at which data is transferred across a network connection over a specific period of time. It is typically measured in **bits per second (bps)** or its multiples (*Kbps*, *Mbps*, *Gbps*, etc.).

**Debit (Throughput)** is **real**: It refers to the actual amount of data that _is_ being transferred over a network in practice. It’s the real-world measure of how much data can flow per second. Debit is usually lower than the theoretical bandwidth due to network conditions, device limitations, or errors in transmission.

In short, debit indicates how fast data moves from one point to another. For example, if an internet connection has a debit of 100 Mbps, it means up to 100 megabits of data can be transferred every second over that connection.
#### Bandwidth

**Bandwidth** refers to the maximum capacity of a communication channel to transfer data. It represents the range of frequencies a signal can use, which affects how much data can be transmitted at once. The wider the bandwidth, the more data the channel can carry at higher speeds.

**Bandwidth** is **theoretical**: It refers to the maximum data capacity a network or communication channel _could_ handle. It's like the width of a highway—how many lanes are available for traffic, representing the potential for data transfer. However, this is just the upper limit and doesn't account for real-world factors like congestion, interference, or network inefficiencies.

In simpler terms, bandwidth is often used to describe the capacity of a network link, with higher bandwidth allowing for faster data transmission.
## Network Models
### OSI Model

The **OSI** (**O**pen **S**ystems **I**nterconnection) Model is a standardised model which we use to demonstrate the theory behind computer networking. In practice, it's actually the more compact TCP/IP model that real-world networking is based off; however the OSI model, in many ways, is easier to get an initial understanding from.

![[Pictures/Fig12.png]]
*The 7 layers of the OSI Model*

###### Layer 7 - Application :

The application layer of the OSI model essentially provides networking options to programs running on a computer. It works almost exclusively with applications, providing an interface for them to use in order to transmit data. When data is given to the application layer, it is passed down into the presentation layer.  
###### Layer 6 - Presentation :

The presentation layer receives data from the application layer. This data tends to be in a format that the application understands, but it's not necessarily in a standardised format that could be understood by the application layer in the _receiving_ computer. The presentation layer translates the data into a standardised format, as well as handling any encryption, compression or other transformations to the data. With this complete, the data is passed down to the session layer.
###### Layer 5 - Session :

When the session layer receives the correctly formatted data from the presentation layer, it looks to see if it can set up a connection with the other computer across the network. If it can't then it sends back an error and the process goes no further. If a session _can_ be established then it's the job of the session layer to maintain it, as well as co-operate with the session layer of the remote computer in order to synchronise communications. The session layer is particularly important as the session that it creates is unique to the communication in question. This is what allows you to make multiple requests to different endpoints simultaneously without all the data getting mixed up (think about opening two tabs in a web browser at the same time)! When the session layer has successfully logged a connection between the host and remote computer the data is passed down to Layer 4: the transport Layer.
###### Layer 4 - Transport :

The transport layer is a very interesting layer that serves numerous important functions. Its first purpose is to choose the protocol over which the data is to be transmitted. The two most common protocols in the transport layer are TCP (**T**ransmission **C**ontrol **P**rotocol) and UDP (**U**ser **D**atagram **P**rotocol); with TCP the transmission is _connection-based_ which means that a connection between the computers is established and maintained for the duration of the request. This allows for a reliable transmission, as the connection can be used to ensure that the packets _all_ get to the right place. A TCP connection allows the two computers to remain in constant communication to ensure that the data is sent at an acceptable speed, and that any lost data is re-sent. With UDP, the opposite is true; packets of data are essentially thrown at the receiving computer -- if it can't keep up then that's _its_ problem (this is why a video transmission over something like Skype can be pixelated if the connection is bad). What this means is that TCP would usually be chosen for situations where accuracy is favoured over speed (e.g. file transfer, or loading a webpage), and UDP would be used in situations where speed is more important (e.g. video streaming).

With a protocol selected, the transport layer then divides the transmission up into bite-sized pieces (over TCP these are called _segments_, over UDP they're called _datagrams_), which makes it easier to transmit the message successfully. 
###### Layer 3 - Network :

The network layer is responsible for locating the destination of your request. For example, the Internet is a huge network; when you want to request information from a webpage, it's the network layer that takes the IP address for the page and figures out the best route to take. At this stage we're working with what is referred to as _Logical_ addressing (i.e. IP addresses) which are still software controlled. Logical addresses are used to provide order to networks, categorising them and allowing us to properly sort them. Currently the most common form of logical addressing is the IPV4 format, which you'll likely already be familiar with (i.e 192.168.1.1 is a common address for a home router).
###### Layer 2 - Data Link :

The data link layer focuses on the _physical_ addressing of the transmission. It receives a packet from the network layer (that includes the IP address for the remote computer) and adds in the physical (MAC) address of the receiving endpoint. Inside every network enabled computer is a Network Interface Card (NIC) which comes with a unique MAC (Media Access Control) address to identify it.

MAC addresses are set by the manufacturer and literally burnt into the card; they can't be changed -- although they _can_ be spoofed. When information is sent across a network, it's actually the physical address that is used to identify where exactly to send the information.

Additionally, it's also the job of the data link layer to present the data in a format suitable for transmission.

The data link layer also serves an important function when it receives data, as it checks the received information to make sure that it hasn't been corrupted during transmission, which could well happen when the data is transmitted by layer 1: the physical layer.
###### Layer 1 - Physical :

The physical layer is right down to the hardware of the computer. This is where the electrical pulses that make up data transfer over a network are sent and received. It's the job of the physical layer to convert the binary data of the transmission into signals and transmit them across the network, as well as receiving incoming signals and converting them back into binary data.
#### Encapsulation

![[Pictures/Fig13.png]]
*Encapsulation and headers of the OSI Mode*

When the message is received by the second computer, it **reverses** the process, starting at the physical layer and working up until it reaches the application layer, stripping off the added information as it goes. This is referred to as *de-encapsulation*.

The processes of encapsulation and de-encapsulation are very important, not least because of their practical use, but also because they give us a **standardised method for sending data**. This means that all transmissions will consistently follow the same methodology, allowing any network enabled device to send a request to any other reachable device and be sure that it will be understood, regardless of whether they are from the same manufacturer, use the same operating system, or any other factors.
### TCP / IP Model

![[Pictures/Fig14.png]]
*TCP/IP vs OSI*

When we talk about TCP/IP, we're actually talking about a **suite of protocols** (sets of rules that define how an action is to be carried out). TCP/IP takes its name from the two most important of these : the **T**ransmission **C**ontrol **P**rotocol that controls the flow of data between two endpoints, and the **I**nternet **P**rotocol, which controls how packets are addressed and sent.

**TCP** is a _connection-based_ protocol. In other words, before you send any data via TCP, you must first form a **stable connection** between the two computers. The process of forming this connection is called the _three-way handshake_.

When you attempt to make a connection, your computer first sends a special request to the remote server indicating that it wants to initialise a connection. This request contains something called a _SYN_ (short for _synchronise_) bit, which essentially makes first contact in starting the connection process. The server will then respond with a packet containing the SYN bit, as well as another "acknowledgement" bit, called _ACK_. Finally, your computer will send a packet that contains the ACK bit by itself, confirming that the connection has been setup successfully. With the three-way handshake successfully completed, data can be reliably transmitted between the two computers. Any data that is lost or corrupted on transmission is re-sent, thus leading to a connection which appears to be lossless.

![[Pictures/Fig15.png]]
*3-way handshake*

**History :**
It's important to understand exactly *why* the TCP/IP and OSI models were originally created. To begin with there was no standardisation, different manufacturers followed their own methodologies, and consequently systems made by different manufacturers were completely incompatible when it came to networking. The TCP/IP model was introduced by the American DoD in 1982 to provide a standard, something for all of the different manufacturers to follow. This sorted out the inconsistency problems. Later the OSI model was also introduced by the International Organisation for Standardisation ([ISO](https://www.iso.org/home.html)) ; however, it's mainly used as a more comprehensive guide for learning, as the TCP/IP model is still the standard upon which modern networking is based.
## Networking Tools
### Ping

Ping is a tool that is used to test the performance of the connection between to device (**not the load speed**). 
It's more used to know if a host is active and accepts requests from our device.
It use the **ICMP** (**I**nternet **C**ontrol **M**essage **P**rotocol).

**Syntax :** 
`$ ping 8.8.8.8

![[Pictures/Fig8.png]]
Here we are pinging a device that has the IP address of `8.8.8.8`. Ping informs us that we have sent 5 ICMP packets, all of which were received with an average time of `27.429` seconds.

**Common options :**
`-i 1` : time in seconds between each *ping* request
`-4` : restrict to IPv4
`-6` : restrict to IPv6
### Traceroute

Traceroute can be used to map the path your request takes as it heads to the target machine.  
  
The internet is made up of many, many different servers and end-points, all networked up to each other. This means that, in order to get to the content you actually want, you first need to go through a bunch of other servers. Traceroute allows you to see each of these connections, it allows you to see every intermediate step between your computer and the resource that you requested.

It works through the UDP protocol, 

**Syntax :** 
`$ traceroute 8.8.8.8

![[Pictures/Fig16.png]]
### WHOIS

Whois essentially allows you to query who a domain name is registered to.

A WHOIS search provides detailed information about a domain name, including:
- **Registrant Details**: Name, organization, and contact information of the domain owner (if public).
- **Registrar Information**: The company responsible for registering the domain.
- **Registration and Expiration Dates**: Key dates like the original registration date and renewal deadline.
- **Domain Status**: Indicates if the domain is active, expired, or restricted.
- **Nameservers**: Details on the DNS servers managing the domain's routing information.

This data is used for verifying ownership, security audits, or contacting domain owners directly.

**Syntax :** 
`$ whois 8.8.8.8

[Web Version](https://www.whois.com/whois)

![[Pictures/Fig18.jpg]]
![[Pictures/Fig17.jpg]]
### Dig

Ever wondered how a URL gets converted into an IP address that your computer can understand? The answer is a TCP/IP protocol called DNS (**D**omain **N**ame **S**ystem).

At the most basic level, DNS allows us to ask a special server to give us the IP address of the website we're trying to access. For example, if we made a request to www.google.com, our computer would first send a request to a special DNS server (which your computer already knows how to find). The server would then go looking for the IP address for Google and send it back to us. Our computer could then send the request to the IP of the Google server.

You make a request to a website. The first thing that your computer does is check its local "***Hosts File***" to see if an explicit IP => Domain mapping has been created. This is an older system than DNS and much less commonly used in modern environments; however, it still takes precedence in the search order of most operating systems. If no mapping has been manually created, the computer then checks its local DNS cache to see if it already has an IP address stored for the website; if it does, great. If not, it goes to the next stage of the process.

Assuming the address hasn't already been found, your computer will then send a request to what is known as a _recursive_ DNS server. These will automatically be known to the router on your network. Many Internet Service Providers (ISPs) maintain their own recursive servers, but companies such as Google and OpenDNS also control recursive servers. This is how your computer automatically knows where to send the request for information: details for a recursive DNS server are stored in your router or computer. This server will also maintain a cache of results for popular domains; however, if the website you've requested isn't stored in the cache, the recursive server will pass the request on to a _root name_ server.

Before 2004 there were precisely 13 root name DNS servers in the world. These days there are many more; however, they are still accessible using the same 13 IP addresses assigned to the original servers (balanced so that you get the closest server when you make a request). The root name servers essentially keep track of the DNS servers in the next level down, choosing an appropriate one to redirect your request to. These lower level servers are called _Top-Level_ _Domain_ servers.

Top-Level Domain (TLD) servers are split up into extensions. So, for example, if you were searching for google**.com** your request would be redirected to a TLD server that handled `.com` domains. If you were searching for wikipedia**.org** your request would be redirected to a TLD server that handles `.org` domains. As with root name servers, TLD servers keep track of the next level down: _Authoritative name servers_. When a TLD server receives your request for information, the server passes it down to an appropriate Authoritative name server.

Authoritative name servers are used to store DNS records for domains directly. In other words, every domain in the world will have its DNS records stored on an Authoritative name server somewhere or another; they are the source of the information. When your request reaches the authoritative name server for the domain you're querying, it will send the relevant information back to you, allowing your computer to connect to the IP address behind the domain you requested.

---

Dig allows us to manually query recursive DNS servers of our choice for information about domains : 
`dig google.com @1.1.1.1`

Here : 
- `google.com` is the domain name
- `1.1.1.1` is the IP address of the DNS server (Cloudflare here)

![Performing a DIG DNS lookup on google.com](https://muirlandoracle.co.uk/wp-content/uploads/2020/03/dig-demo.png)

This is a _lot_ of information. We're currently most interested in the `ANSWER` section for this room; however, taking the time to learn what the rest of this means is a very good idea. In summary, that information is telling us that we sent it one query and successfully (i.e. No Errors) received one full answer -- which, as expected, contains the IP address for the domain name that we queried.

Another interesting piece of information that dig gives us is the TTL (**T**ime **T**o **L**ive) of the queried DNS record. As mentioned previously, when your computer queries a domain name, it stores the results in its local cache. The TTL of the record tells your computer when to stop considering the record as being valid -- i.e. when it should request the data again, rather than relying on the cached copy.

The TTL can be found in the second column of the answer section:

![Results demonstrating that the TTL of the DNS record is 157](https://muirlandoracle.co.uk/wp-content/uploads/2020/03/TTL.png)

It's important to remember that TTL (in the context of DNS caching) is measured in _seconds,_ so the record in the example will expire in two minutes and thirty-seven seconds.
### nslookup

`nslookup` (Name Server Lookup) is a network utility used to query DNS (Domain Name System) servers, allowing you to resolve domain names into IP addresses and vice versa. It’s widely used in troubleshooting DNS issues and is available on most operating systems, including Linux, macOS, and Windows.

**Syntax :** 
`$ nslookup -type=MX google.com 1.1.1.1`

- `-type=MX` : the type of requested DNS record (optional)
- `google.com` : the domain name (**required**)
- `1.1.1.1` : the IP address of the DNS server to use (optional)

**DNS records types :**
- **A** : Maps a domain to an IPv4 address.
- **AAAA** : Maps a domain to an IPv6 address.
- **MX** : Mail servers for the domain.
- **CNAME** : An alias for a domain pointing to another domain.
- **TXT** : Text records, often used for domain verifications and SPF.

![[Pictures/Fig25.jpg]]
## HTTP

##### What is HTTP ? (HyperText Transfer Protocol)

HTTP is what's used whenever you view a website, developed by Tim Berners-Lee and his team between 1989-1991. HTTP is the set of rules used for communicating with web servers for the transmitting of webpage data, whether that is HTML, Images, Videos, etc.
##### What is HTTPS ? (HyperText Transfer Protocol Secure)

HTTPS is the secure version of HTTP. HTTPS data is encrypted so it not only stops people from seeing the data you are receiving and sending, but it also gives you assurances that you're talking to the correct web server and not something impersonating it.
### URL (Uniform Resource Locator)

![[Pictures/Fig19.png]]

**Scheme :** This instructs on what protocol to use for accessing the resource such as HTTP, HTTPS, FTP (File Transfer Protocol).  

**UserInfo :** Some services require authentication to log in, you can put a username and password into the URL to log in.  

**Hostname :** The domain name or IP address of the server you wish to access.  

**Port :** The Port that you are going to connect to, usually 80 for HTTP and 443 for HTTPS, but this can be hosted on any port between 1 - 65535.  

**Path :** The file name or location of the resource you are trying to access.  

**Query :** Extra bits of information that can be sent to the requested path. For example, /blog?**id=1** would tell the blog path that you wish to receive the blog article with the id of 1.  

**Fragment :** This is a reference to a location on the actual page requested. This is commonly used for pages with long content and can have a certain part of the page directly linked to it, so it is viewable to the user as soon as they access the page.
### Request

*Example Request :*
```http
GET / HTTP/1.1
Host: my-website.com
User-Agent: Mozilla/5.0 Firefox/87.0
Referer: https://my-website.com/
```

*Example Request :*
```http
HTTP/1.1 200 OK
Server: nginx/1.15.8
Date: Wen, 30 Oct 2024 13:01:52 GMT
Content-Type: text/html
Content-Length: 98

<html>
<head>
    <title>My Website</title>
</head>
<body>
    Welcome to my website !
</body>
</html>
```

**Note :** HTTP response contains a blank line to confirm the end of the HTTP response.
### Methods

**GET Request**
This is used for getting information from a web server.  

**POST Request**
This is used for submitting data to the web server and potentially creating new records  

**PUT Request**
This is used for submitting data to a web server to update information

**DELETE Request**  
This is used for deleting information/records from a web server.
### Status Codes

| Category                            | Description                                                                                                                                                                            |
| ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **100-199**<br>Information Response | These are sent to tell the client the first part of their request has been accepted and they should continue sending the rest of their request. These codes are no longer very common. |
| **200 - 299**<br>Success            | This range of status codes is used to tell the client their request was successful.                                                                                                    |
| **300 - 399**<br>Redirection        | These are used to redirect the client's request to another resource. This can be either to a different webpage or a different website altogether.                                      |
| **400 - 499**<br>Client Errors      | Used to inform the client that there was an error with their request.                                                                                                                  |
| **500 - 599** <br>Server Errors     | This is reserved for errors happening on the server-side and usually indicate quite a major problem with the server handling the request.                                              |
***Categories of HTTP status codes***

| Code and Title                   | Description                                                                                                                                                                                                                   |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **200** : OK                     | The request was completed successfully.                                                                                                                                                                                       |
| **201** : Created                | A resource has been created (for example a new user or new blog post).                                                                                                                                                        |
| **301** : Moved Permanently      | This redirects the client's browser to a new webpage or tells search engines that the page has moved somewhere else and to look there instead.                                                                                |
| **302** : Found                  | Similar to the above permanent redirect, but as the name suggests, this is only a temporary change and it may change again in the near future.                                                                                |
| **400** : Bad Request            | This tells the browser that something was either wrong or missing in their request. This could sometimes be used if the web server resource that is being requested expected a certain parameter that the client didn't send. |
| **401** : Not Authorised         | You are not currently allowed to view this resource until you have authorised with the web application, most commonly with a username and password.                                                                           |
| **403** : Forbidden              | You do not have permission to view this resource whether you are logged in or not.                                                                                                                                            |
| **405** : Method Not Allowed     | The resource does not allow this method request, for example, you send a GET request to the resource /create-account when it was expecting a POST request instead.                                                            |
| **404** : Page Not Found         | The page/resource you requested does not exist.                                                                                                                                                                               |
| **500** : Internal Service Error | The server has encountered some kind of error with your request that it doesn't know how to handle properly.                                                                                                                  |
| **503** : Service Unavailable    | This server cannot handle your request as it's either overloaded or down for maintenance.                                                                                                                                     |
***Most common HTTP status codes***
### Headers

##### Common Request Headers

﻿These are headers that are sent from the client (usually your browser) to the server.  

- **Host:** Some web servers host multiple websites so by providing the host headers you can tell it which one you require, otherwise you'll just receive the default website for the server.  

- **User-Agent:** This is your browser software and version number, telling the web server your browser software helps it format the website properly for your browser and also some elements of HTML, JavaScript and CSS are only available in certain browsers.  

- **Content-Length:** When sending data to a web server such as in a form, the content length tells the web server how much data to expect in the web request. This way the server can ensure it isn't missing any data.

- **Accept-Encoding:** Tells the web server what types of compression methods the browser supports so the data can be made smaller for transmitting over the internet.

- **Cookie:** Data sent to the server to help remember your information (see cookies task for more information).  

##### Common Response Headers

These are the headers that are returned to the client from the server after a request.

- **Set-Cookie:** Information to store which gets sent back to the web server on each request (see cookies task for more information).  

- **Cache-Control:** How long to store the content of the response in the browser's cache before it requests it again.  

- **Content-Type:** This tells the client what type of data is being returned, i.e., HTML, CSS, JavaScript, Images, PDF, Video, etc. Using the content-type header the browser then knows how to process the data.  

- **Content-Encoding:** What method has been used to compress the data to make it smaller when sending it over the internet.
### Cookies

Cookies are saved when you receive a "Set-Cookie" header from a web server. Then every further request you make, you'll send the cookie data back to the web server. Because HTTP is stateless (doesn't keep track of your previous requests), cookies can be used to remind the web server who you are, some personal settings for the website or whether you've been to the website before.
![[Pictures/Fig20.png]]
Cookies can be used for many purposes but are most commonly used for website authentication. The cookie value won't usually be a clear-text string where you can see the password, but a token (unique secret code that isn't easily humanly guessable).
## DNS
### Domains Hierarchy

![[Pictures/Fig21.png]]
##### Top Level Domains (TLD)
There are two types of TLD, gTLD (Generic Top Level) and ccTLD (Country Code Top Level Domain). 
Historically a *gTLD* was meant to tell the user the domain name's purpose; for example, a `.com` would be for commercial purposes, `.org` for an organisation, `.edu` for education and `.gov` for government. And a *ccTLD* was used for geographical purposes, for example, `.ca` for sites based in Canada, `.co.uk` for sites based in the United Kingdom and so on. Due to such demand, there is an influx of new gTLDs ranging from `.online` , `.club` , `.website` , `.biz` and so many more. For a full list of over 2000 TLDs [click here](https://data.iana.org/TLD/tlds-alpha-by-domain.txt).
##### Second Level Domains
Taking `wikipedia.org` as an example, the `.org` part is the TLD, and `wikipedia` is the Second Level Domain. When registering a domain name, the second-level domain is **limited to 63 characters** and the TLD and can only use **a-z, 0-9 and hyphens** (cannot start or end with hyphens or have consecutive hyphens).
##### Subdomains
A subdomain sits on the left-hand side of the Second-Level Domain using a period to separate it. For example, in the name `en.wikipedia.com` the `en` part is the subdomain. A subdomain name has the **same creation restrictions** as a Second-Level Domain, being limited to 63 characters and can only use a-z 0-9 and hyphens (cannot start or end with hyphens or have consecutive hyphens). You can use multiple subdomains split with periods to create longer names, such as `admin.en.wikipedia.org`. But the length must be kept to 253 characters or less. There is no limit to the number of subdomains you can create for your domain name.
### Records Types

**A Record**
These records resolve to IPv4 addresses, for example 104.26.10.229

**AAAA Record**
These records resolve to IPv6 addresses, for example 2606:4700:20::681a:be5

**CNAME Record**
These records resolve to another domain name, for example, `goog.le` has the domain name which returns a CNAME record `google.com`. Another DNS request would then be made to `google.com` to work out the IP address.

**MX Record**
These records resolve to the address of the servers that handle the email for the domain you are querying, for example an MX record response for `google.com` would look something like `smtp.google.com`. These records also come with a **priority flag**. The smaller the number, the higher the priority. This tells the client in which order to try the servers, this is perfect for if the main server goes down and email needs to be sent to a backup server.

**TXT Record**
TXT records are free text fields where any text-based data can be stored. TXT records have multiple uses, but some common ones can be to list servers that have the authority to send an email on behalf of the domain (this can help in the battle against spam and spoofed email). They can also be used to verify ownership of the domain name when signing up for third party services.
### DNS Request

![[Pictures/Fig22.jpg]]
*What happens when you make a DNS request.*

1. To start the process, you simply enter the address of the website you want to visit into your browser: `wikipedia.org`. This will trigger a DNS query.

2. When you request a domain name, your computer first checks its local cache to see if you've previously looked up the address recently. If not, a request to your Recursive DNS Server will be made.

3. A *Recursive DNS Server* (also called *DNS Resolver*) is usually provided by your ISP, but you can also choose your own. This server also has a local cache of recently looked up domain names. If a result is found locally, this is sent back to your computer, and your request ends here (this is common for popular and heavily requested services such as Google, Facebook, Twitter). If the request cannot be found locally, a journey begins to find the correct answer, starting with the internet's root DNS servers.

4. The root servers act as the DNS backbone of the internet. Their job is to redirect you to the correct Top Level Domain Server, depending on your request. If, for example, you request `wikipedia.org`, the root server will recognise the Top Level Domain of `.org` and refer you to the correct TLD server that deals with `.org` addresses.

5. The TLD server holds records for where to find the authoritative server to answer the DNS request. The authoritative server is often also known as the nameserver for the domain. For example, the name server for `wikipedia.org` is `ns0.wikimedia.org`, `ns1.wikimedia.org` and `ns2.wikimedia.org`. You'll often find multiple nameservers for a domain name to act as a backup in case one goes down.

6. An authoritative DNS server is the server that is responsible for storing the DNS records for a particular domain name and where any updates to your domain name DNS records would be made. 

7. Depending on the record type, the DNS record is then sent back to the Recursive DNS Server, where a local copy will be **cached for future requests** and then relayed back to the original client that made the request. DNS records all come with a **TTL** (Time To Live) value. This value is a number represented in **seconds** that the response should be saved for locally until you have to look it up again. Caching saves on having to make a DNS request every time you communicate with a server.



























##