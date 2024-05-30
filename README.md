# cybersecurity_bootcamp

NETWORKING FUNDAMENTALS FOR CYBERSECURITY : <br>
Network : is a connection of multiple network devices via any medium.<br>
Networking : is communication or transmisson of data between devices.<br>
Internetworking : is connecting more than two networks. Example : youtube videos connect many people as you can keep sharing videos. <br>
Need of networking : we can share resources over LAN or WAN, we can connect laptops with printer for printouts, most importantly we can share data.<br>
Point-to-Point (P2P) model : in this model only two devices are connected to each other.<br>
Client-Server model : clients request services or resources from servers which fulfill their requests.<br>
Computer network : is a system of interconnected computers that use a set of common communication protocols for the purpose of sharing resources.<br>
Types of computer network : Personal Area Netwok (PAN) : in bluetooth. Local Area Network (LAN) : in homes,small office. Campus Area Network (CAN) : connecting two or more LANs in university campuses (small geographical area). Metropolitan Area Network (MAN) : connection of two or more LANs in big campuses (large geographical area). Wide Area Network (WAN) : geographical communication in internet.<br>
Topology : arrangement of networking devices over a network.<br>
Bus Topology : all devices are connected to a single back bone cable. One device failure creates problem in entire network.<br>
Star Topology : all devices are connected to a central hub or switch. Hub or switch fails creates problem in entire network.<br>
Tree Topology : combination of star and bus topology.<br>
Mesh Topology : each device is connected to every other device.<br>
Hybrid Topology : collection of two or more topology.<br>
Ring Topology : connects device in circular manner where each device is connected to two other devices on either side in a closed loop. Data transfer happens in clock-wise format.<br>
Dual Ring Topology : connects devices with help of two rings where data transfer happens in clock-wise as well as anti-clock-wise.<br>
Switch : is a device that connects multiple devices in a network. It transmits data to only required devices. <br>
Hub : is a device that connects multiple devices in a network. It transmits data to all the connected devices. <br>
Server : is heart of the network that stores and shares information with other computers, they send the information and handle the requests.<br>
Ping : is used to test the reachability of a device. It sends a packet of data to the destination IP address and waits for the response. <br>
Data : information that is transmitted over a network. <br>
Packet/Frame : data is broken down into smaller units with additional information like destination and source address etc so that data reaches its destination accurately. It is called as packet in Network Layer but frame in Data Link Layer. <br>
OSI (Open System Interconnection) model : consists of 7 layers which works towards transfer of data from one network to another network across the globe between sender and receiver. It is developed by ISO (International Organization for Standerization). <br>
Lower Layer : Physical, Data-link, Network, Transport. They are used to send the packet. <br>
Upper Layer : Session, Presentation, Application. They are used to create the packet. <br>
(7)Application Layer : It is used to create services for interface. Example : HTTP, FTP. <br>
(6)Presentation Layer : Designs format of data like encode/decode, encrypt/decrypt, compresses/decompresses. <br>
(5)Session Layer : It establishes, maintains and terminates a connection between applications. <br>
(4)Transport Layer : Divides data into segments. Provides reliable or connectionless delivery using protocols like Trasmission Control Protocol or User Datagram Protocol between sender and receiver. <br>
(3)Network Layer : It decides the best path for data packets to travel.<br>
(2)Data Link Layer : It makes the data error free, maintains the same speed of data transfer between sender and receiver. Data is the form of frames. <br>
(1)Physical Layer : It makes the data in the form of 0 or 1 (bits). It decided to send the data to receiver in wire or wireless mode. <br>
Bandwidth : amount of data that can be transmitted within a time period. <br>
Wired media : uses wire for data transmission. <br>
Wireless media : uses electromagnetic waves for data transmission. <br>
Types of Wired media : Twisted Pair has two types Unshielded (less secure) and Shielded (more secure as there is a foil to protect data). Lan cable or ethernet cable which are used to connect devices within Local Area Network are made from Twisted Pair and have RJ 45 connector (made of 8 pins which help for data transmission). Fibre Optic Cable uses light source to send and recieve data signals it is fast and most secure among all as it is made of glass core plate and breaking it will not allow data transfer hence difficult to hack. Coaxial Cable has higher bandwidth compared to Twisted Pair and cost-effective and easy to install compared to Fiber Optic Cable. <br>
Cross cable : Used to connect similar devices. Straight cable/Patch cable : Used to connect dissimilar devices. <br>
ISP (Internet Service Provider) Network : is the one which delivers internet connectivity. Wired is fast and secure compared to wireless. <br>
Rack Technology : is technology used to organize networking devices like servers so it becomes easier for maintenance in data centres and server rooms. <br>
NIC : Network Interface Card also called as network adapter card which helps to connect to the network. It is used to perform all network related functions. <br>
MAC Address : Media Access Control is 48 bit or 12 digit (hexadecimal). It is permanent address given to each device, cannot change. It is inside the NIC. It is used to communicate within the local network. <br>
IP Address : Internet Protocol is unique address that identifies a device on the internet. Static IP Addressing : manual IP assigned by Network Admin to Host, it is fixed. Dynamic IP Addressing : it is temporary, assigned from the pool of available addresses by Dynamic Host Configuration Protocol (DHCP). <br>
IP Version : IPv4 (Internet Protocol Version 4) is 32 bit, represent it using decimal number and is used for small network. IPv6 (Internet Protocol Version 6) is 128 bit, represent it using hexadecimal number and is used for large network. <br>
DNS : Domain Name System DNS is essential because it allows us to use easy-to-remember domain names (like "google.com") instead of having to remember the numerical IP addresses (such as "172.217.3.78" for Google) for every website we want to visit. It converts domain name to ip address. It can also convert back. <br>
SMTP : Simple Mail Transfer Protocol is used for sending the mail. <br>
POP : Post Office Protocol is used to receive the mail. <br>
IMAP : Internet Message Access Protocol is used for to receive the mail, this is most suitable in case of access from multiple devices. <br>
TCP : Transmission Control Protocol is used to send/receive packets to website or another pc. It is secure and reliable. <br>
UDP : User Datagram Protocol is used to send/receive packets when heavy data is used like video streaming. It is less secure and fast. <br>
Telnet : it is a protocol used for remote access. It is insecure as there is no encryption. <br>
SSH : Secure SHell protocol is used to create secure connection between two devices as it encrypts the data. <br>
ICMP : Internet Control Message Protocol is used for control purposes like error reporting by network devices, example : requested service is not available. <br>
RDP : Remote Desktop Protocol used to connect remotely to another computer developed by Microsoft. <br>
HTTP : Hypter Text Transfer Protocol is used for web access. <br>
HTTPS : Hypter Text Transfer Protocol Secure is used for web accces securely. <br>
Router : networking device that forwards data packets between computer networks and it determines the best path for the information to travel depending on packet priority and available bandwidth. <br>
Routing Tables : shows where the data packet should go. <br>
Routing Matrices : sets the criteria which help to choose the best path for data packets to go like bandwidth,cost,etc. <br>
Static Routing vs Dynamic Routing : In Static Routing it is fixed manually and there is no adaptability which is suitable for small networks whereas in Dynamic Routing it automatically updates based on network changes,i.e, there is network adaptability and can be used for larger networks. <br>
Transmission : process where user can send data using network devices or process of sharing information between devices. <br>
Types of Transmission modes: Simplex Mode : it is one way communication where device can only send data, example is keyboard. Duplex Mode : we can send and receive data. Half Duplex Mode : user cannot send and receive data simultaneously, example is walkie-talkie. Full Duplex Mode : device can send and receive data simultaneously, example is video calls. <br>
POE : Power Over Ethernet is an inbuilt power suppy along with ethernet cable which eliminates the need of using extra cables for power supply. It ensures smooth transmission of data at it does not overheat, saves power. <br>
Wireless Network : use to connect and manage wireless end devices. Uses radio frequency to send/receive data, encryption technology to secure data, it is less secure compared to wired, it covers only small area. <br>
Wireless Frame : It is the one which makes data exchange possible in the air in wireless network. <br>
Wireless Authentication Method : a protocol where no need to enter any authentication, access points accepts the request without any questions. <br>
Wired Equivalent Privacy (WEP) : It is security protocol where authentication option is available, it encrypts the wireless frame with help of cipher algorithm. <br>
Wifi-Protected Access (WPA/WPA-2) : is security protocol which is more secure for wireless network. WPA-2 is more secure than WPA as it supports Advance Encryption System (AES).<br>
Antenna : is used to send and receive signals. <br>
Wireless Lan Controller (WLC) : it helps in smooth performance of wireless network by managing access points (access points are the one which helps in connecting a laptop to wifi without wire). <br>
Virutalization : it is the act of creating a virtual version of something like running Kali linux operating system on a predefine Windows operating system. <br>
Cloud Computing : helps for secure storage services online like google drive where you can access your file from any device as long as you have the account. <br>
IPsec : Internet Protocol Security which helps for secure data transfer in public networks due to encryption. This is used to set up VPN. <br>
Socket : helps in communication for different applications in computer network, just like phone helps in communication between two people, socket helps in communication for computer networks through IP addresses. <br>
SSL : Secure Socket Layer helps in securing connections between clients and servers by encrypting TCP/IP. <br>
TLS : Transport Layer Security is the advance version of SSL. <br>
