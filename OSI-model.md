# OSI-model
## Description
>[!important]
>This liste of Ports/Protocols is organized using the [OSI model](https://en.wikipedia.org/wiki/OSI_model).
>
>If you want a more detailled document go visite [osi-model.com](https://osi-model.com/) *source: [b1nary](https://github.com/b1nary)*
## OSI LAYER 1 - Physical Layer
- **Copper Cables** Ethernet cables that transfer electricity pulses to transfer messages.
- **Optical Fiber** Glass tube equiped with LED/LASER technologie to transfer light signals
- **Wireless** Wireless technologie uses antenas to transfer a signal threw the air.
## OSI LAYER 2 - Data Link Layer
- **IEEE 802.3**: Defines Ethernet standards.
- **MAC** (Media Acces Control): Unique physical ID.
- **ARP** (Address Resolution Protocol): Maps IP addresses to MAC addresses.
## OSI LAYER 3 - Network Layer
- **IPv4**: The fourth version of the Internet Protocol, using 32-bit addresses.
- **IPv6**: The sixth version of the Internet Protocol, using 128-bit addresses.
## OSI LAYER 4 - Transport Layer
### TCP (Transmission Control Protocol):
- **Port 80 - HTTP** Used for web traffic.
- **Port 443 - HTTPS** Secured version of HTTP.
- **Port 21 - FTP** (File Transfer Protocol): Used for file transfers.
- **Port 25 - SMTP** (Simple Mail Transfer Protocol): Used for email transmission.
- **Port 110 - POP3** (Post Office Protocol version 3): Retrieves emails from a server.
- **Port 143 - IMAP** (Internet Message Access Protocol): Manages and retrieves email messages. 
### UDP (User Datagram Protocol):
- **Port 53 - DNS** (Domain Name System): Resolves domain names to IP addresses.
- **Port 67/68 - DHCP** (Dynamic Host Configuration Protocol): Assigns IP addresses dynamically.
- **Port 161/162 - SNMP** (Simple Network Management Protocol): Monitors and manages network devices.
- **Port 514 - Syslog**: Event logging on a network.
### TCP & UDP:
- **Port 414 - InfoSeek**: Infoseek was a web search engine that gained popularity in the mid-1990s.
## OSI LAYER 5 - Session Layer
- **NetBIOS** (Network Basic Input/Output System): Manages sessions and provides session establishment, maintenance, and termination functions.
## OSI LAYER 6 - Presentation Layer
- **SSL/TLS** (Secure Sockets Layer/Transport Layer Security): Ensures the secure exchange of data by providing encryption and decryption services for application layer protocols.
## OSI Layer 7 - Application Layer
- **Port 80 - HTTP** (Hypertext Transfer Protocol) *Used for transmitting hypermedia.*
- **Port 443 - HTTPS** (Hypertext Transfer Protocol Secure): *A secure version of HTTP.*
- **Port 21 - FTP** (File Transfer Protocol): *Used for transferring files.*
- **Port 25 - SMTP** (Simple Mail Transfer Protocol): *Sends email messages.*
- **Port 110 - POP3** (Post Office Protocol version 3): *Retrieves emails from a server.*
- **Port 143 - IMAP** (Internet Message *Access Protocol): Manages and retrieves email messages.*
- **Port 53 - DNS** (Domain Name System): *Resolves domain names to IP addresses.*
- **Ports 67/68 - DHCP** (Dynamic Host Configuration Protocol): *Assigns IP addresses dynamically.*
- **Ports 161/162 - SNMP** (Simple Network Management Protocol): Monitors and manages network devices.
- **Port 514 - Syslog**: Event logging on a network.

