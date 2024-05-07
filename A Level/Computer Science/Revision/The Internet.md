

### Network topology

| Content                                                                                                                                                    | Additional information                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Understand:<br><br>- physical star topology<br>- logical bus network topology<br><br>and:<br><br>- differentiate between them<br>- explain their operation | A network physically wired in star topology can behave logically as a bus network by using a bus protocol and appropriate physical switching. |



### Types of networking between hosts

| Content                                                                                                                                 | Additional information                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Explain the following and describe situations where they might be used:<br><br>- peer-to-peer networking<br>- client-server networking. | In a peer-to-peer network, each computer has equal status. In a client-server network, most computers are nominated as clients and one or more as servers. The clients request services from the servers, which provide these services, for example file server, email server. |


### Wireless networking

|Content|Additional information|
|---|---|
|Explain the purpose of WiFi.|A wireless local area network that is based on international standards.<br><br>Used to enable devices to connect to a network wirelessly.|
|Be familiar with the components required for wireless networking.|Wireless network adapter.<br><br>Wireless access point.|
|Be familiar with how wireless networks are secured.|Strong encryption of transmitted data using WPA (Wifi Protected Access)/WPA2, SSID (Service Set Identifier) broadcast disabled, MAC (Media Access Control) address allow list.|
|Explain the wireless protocol Carrier Sense Multiple Access with Collision Avoidance (CSMA/CA) with and without Request to Send/Clear to Send (RTS/CTS).|Knowledge of Carrier Sense Multiple Access/Collection Detection (CSMA/CD) as used in, for example, Ethernet, is not required.|
|Be familiar with the purpose of Service Set Identifier (SSID).||

## The Internet

### The Internet and how it works

| Content                                                                                                            | Additional information |
| ------------------------------------------------------------------------------------------------------------------ | ---------------------- |
| Understand the structure of the Internet.                                                                          |                        |
| Understand the role of packet switching and routers.                                                               |                        |
| Know the main components of a packet.                                                                              |                        |
| Define:<br><br>- router<br>- gateway.<br><br>Consider where and why they are used.                                 |                        |
| Explain how routing is achieved across the Internet.                                                               |                        |
| Describe the term 'uniform resource locator' (URL) in the context of internetworking.                              |                        |
| Explain the terms ‘fully qualified domain name’ (FQDN), ‘domain name’ and ‘IP address’.                            |                        |
| Describe how domain names are organised.                                                                           |                        |
| Understand the purpose and function of the domain service and its reliance on the Domain Name Server (DNS) system. |                        |
| Explain the service provided by Internet registries and why they are needed.                                       |                        |

### Internet security

|Content|Additional information|
|---|---|
|Understand how a firewall works (packet filtering, proxy server, stateful inspection).||
|Explain symmetric and asymmetric (private/public key) encryption and key exchange.||
|Explain how digital certificates and digital signatures are obtained and used.||
|Discuss worms, trojans and viruses, and the vulnerabilities that they exploit.||
|Discuss how improved code quality, monitoring and protection can be used to address worms, trojans and viruses.||

## The Transmission Control Protocol/Internet Protocol (TCP/IP) protocol

### TCP/IP

|Content|Additional information|
|---|---|
|Describe the role of the four layers of the TCP/IP stack (application, transport, network, link).||
|Describe the role of sockets in the TCP/IP stack.||
|Be familiar with the role of MAC (Media Access Control) addresses.||
|Explain what the well-known ports and client ports are used for and the differences between them.||

### Standard application layer protocols

|Content|Additional information|
|---|---|
|Be familiar with the following protocols:<br><br>- FTP (File Transfer Protocol)<br>- HTTP (Hypertext Transfer Protocol)<br>- HTTPS (Hypertext Transfer Protocol Secure)<br>- POP3 (Post Office Protocol (v3))<br>- SMTP (Simple Mail Transfer Protocol)<br>- SSH (Secure Shell).||
|Be familiar with FTP client software and an FTP server, with regard to transferring files using anonymous and non-anonymous access.||
|Be familiar with how SSH is used for remote management.||
|Know how an SSH client is used to make a TCP connection to a remote port for the purpose of sending commands to this port using application level protocols such as GET for HTTP, SMTP commands for sending email and POP3 for retrieving email.||
|Be familiar with using SSH to log in securely to a remote computer and execute commands.||
|Explain the role of an email server in retrieving and sending email.||
|Explain the role of a web server in serving up web pages in text form.||
|Understand the role of a web browser in retrieving web pages and web page resources and rendering these accordingly.||

### IP address structure

|Content|Additional information|
|---|---|
|Know that an IP address is split into a network identifier part and a host identifier part.||

### Subnet masking

|Content|Additional information|
|---|---|
|Know that networks can be divided into subnets and know how a subnet mask is used to identify the network identifier part of the IP address.||

### IP standards

|Content|Additional information|
|---|---|
|Know that there are currently two standards of IP address, v4 and v6.||
|Know why v6 was introduced.||

### Public and private IP addresses

|Content|Additional information|
|---|---|
|Distinguish between routable and non-routable IP addresses.||

### Dynamic Host Configuration Protocol (DHCP)

| Content                                                 | Additional information |
| ------------------------------------------------------- | ---------------------- |
| Understand the purpose and function of the DHCP system. |                        |
DHCP, or the dynamic host configuaration protocol, is a protocol that assigns IP addresses dynamically to devices when they connect to a network. They assign addresses from a finite pool from which it is then removed, and when they disconnect the IP address is added back to the pool, as this prevents two devices from being assigned the same. Without the DHCP protocol, an admin would have to manually assign these addresses which makes the protocol very efficient in comparison. 
### Network Address Translation (NAT)

|Content|Additional information|
|---|---|
|Explain the basic concept of NAT and why it is used.||
Network address translation provides translation from private IP addresses to public ones. This allows many private IP addresses to exist on a network which prevents the need for unique IP addresses as they only need to be unique on that network. Only the public IP address needing to be registered with the DNS server. This is done using a lookup table.

### Port forwarding

|Content|Additional information|
|---|---|
|Explain the basic concept of port forwarding and why it is used.||

### Client server model

|Content|Additional information|
|---|---|
|Be familiar with the client server model.|Client sends a request message to server, server responds to request by replying with a response message to client.|
|Be familiar with the Websocket protocol and know why it is used and where it is used.|The Websocket specification defines an API (Application Programming Interface) establishing a full-duplex 'socket' connection between a web browser and a server over TCP. This means that there is a persistent connection between client and server, allowing both parties to send data at any time.|
|Be familiar with the principles of Web CRUD Applications and REST:<br><br>- CRUD is an acronym for:<br>    - C – Create<br>    - R – Retrieve<br>    - U – Update<br>    - D – Delete.<br>- REST enables CRUD to be mapped to database functions (SQL) as follows:<br>    - GET → SELECT<br>    - POST → INSERT<br>    - DELETE → DELETE<br>    - PUT → UPDATE.|Students should understand the principles:<br><br>- database connected to browser using REST – Representational State Transfer - which relies on HTTP request methods<br>- REST allows JavaScript to talk to server through HTTP<br>- REST API (Application Programming Interface) created and run on server, browser Javascript calls API<br>- JSON (JavaScript Object Notation) or XML can be used to transmit data between a server and web application<br>- Javascript referenced by HTML file, eg index.html, is run in browser.|
|Compare JSON (Java script object notation) with XML.|JSON compared with XML is:<br><br>- easier for a human to read<br>- more compact<br>- easier to create<br>- easier for computers to parse and therefore quicker to parse.|

### Thin- versus thick-client computing

|Content|Additional information|
|---|---|
|Compare and contrast thin-client computing with thick-client computing.|
Thin client offloads more duties to the server, so that less processing is done/less data is stored on device. 