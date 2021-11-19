# Notes 05: Networking & Content Delivery
## Networking 

What is a Network?
* A computer network is just two or more client machines that are connected together, using a network device, to share resources. A network can be logically partitioned to create subnets. A router or switch are used to connect the clients together and enable communications.

Definitions for Computer Networking: 
* Computer Network: It is the interconnection of multiple devices, generally termed as Hosts connected using multiple paths for the purpose of sending/receiving data or media.
![Note 05](https://user-images.githubusercontent.com/90662294/142615466-a972945f-a00a-4cf3-961b-6af3e20e84df.png)
  * The layout pattern using which devices are interconnected is called as network topology. Such as Bus, Star, Mesh, Ring, Daisy chain.
  ![network-topology](https://user-images.githubusercontent.com/90662294/142615593-d4bd8694-93ca-4d90-b3e9-c3bff0e454df.png)

* OSI (Open Systems Interconnection)Model Layers: 
  * Layer 7 - Application: 
    * The application layer is the OSI layer closest to the end user, which means both the OSI application layer and the user interact directly with the software application.
  * Layer 6 - Presentation: 
    * The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them.
  * Layer 5 - Session
    * The session layer controls the dialogues (connections) between computers. It establishes, manages and terminates the connections between the local and remote application.
  * Layer 4 - Transport
    * The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source to a destination host, while maintaining the quality of service functions.
  * Layer 3 - Network
    * The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks".
  * Layer 2 - Data Link
    * The data link layer provides node-to-node data transfer—a link between two directly connected nodes
  * Layer 1 - Physical
    * Responsible for the transmission and reception of unstructured raw data between a device and a physical transmission medium.
* Protocol: the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model. Few of such protocols are TCP, IP, UDP, ARP, DHCP, FTP and so on.
* Unique Indentifiers of Network: Host Name: Each device in the network is associated with a unique device name known as Hostname.
* IP Address (Internet Protocol Address): To identify each device in the world-wide-web, Internet Assigned Numbers Authority (IANA) assigns IPv4 (Version 4) address as a unique identifier for each device on the Internet. However there is also an IPv6 (Version 6) scheme available that has more addresses available. _ipconfig_
* Classless Inter-Domain Routing (CIDR): A common method to describe networks is Classless Inter-Domain Routing (CIDR). The CIDR address is expressed as follows:
  * An IP address (which is the first address of the network)
  * Next, a slash character (/)
  * Finally, a number that tells you how many bits of the routing prefix must be fixed or allocated for the network identifier
  * For example, the CIDR address is 192.0.2.0/24. The last number (24) tells you that the first 24 bits must be fixed. The last 8 bits are flexible, which means that 28 (or 256) IP addresses are available for the network, which range from 192.0.2.0 to 192.0.2.255. The fourth decimal digit is allowed to change from 0 to 255.
  * There are two special cases:
    * Fixed IP addresses, in which every bit is fixed, represent a single IP address (for example, 192.0.2.0/32). This type of address is helpful when you want to set up a firewall rule and give access to a specific host.
    * The internet, in which every bit is flexible, is represented as 0.0.0.0/0
* MAC Address (Media Access Control Address): Also known as physical address, is the unique identifier of each host and is associated with the NIC (Network Interface Card).
  * MAC address is assigned to the NIC at the time of manufacturing.
  * Length of the MAC address is : 12-digit/ 6 bytes/ 48 bits
* Port: Port number is a 16-bit integer, hence we have 216 ports available which are categorized as shown below:
  * Well known Ports 0–1023
  * Registered Ports 1024–49151
  * Ephemeral Ports 49152–65535
  * Number of ports: 65,536
  * Range: 0–65535
* Socket: The unique combination of IP address and Port number together are termed as Socket.
* DNS Server (Domain Name System Server): DNS is basically a server which translates web addresses or URL (ex: www.google.com) (Links to an external site.) into their corresponding IP addresses. We don’t have to remember all the IP addresses of each and every website.
* ARP (Address Resolution Protocol): It is used to convert the IP address to its corresponding Physical Address(i.e.MAC Address).
  * used by the Data Link Layer to identify the MAC address of the Receiver’s machine.
* RARP ( Reverse Address Resolution Protocol): As the name suggests, it provides the IP address of the device given a physical address as input. But RARP has become obsolete since the time DHCP has come into the picture.
* The Internet: a global network of smaller networks interconnected using communication protocols that are standardized. The Internet standards describe a framework known as the Internet protocol suite. This model divides methods into a layered system of protocols.
  * These layers are as follows:
    1. Application layer (highest) — concerned with the data(URL, type, etc), where HTTP, HTTPS, etc comes in.
    2. Transport layer — responsible for end-to-end communication over a network.
    3. Network layer — provides a data route.
* The World Wide Web:  a system of Internet servers that support specially formatted documents. The documents are formatted in a markup language called HTML(that supports links, multimedia, etc). These documents are interlinked using hypertext links and are accessible via the Internet.
  * To link hypertext to the Internet, we need:
    1. The markup language, i.e., HTML.
    2. The transfer protocol, e.g., HTTP.
    3. Uniform Resource Locator (URL), the address of the resource.
* URI (Uniform Rosource Identifier): like an address providing a unique global identifier to a resource on the Web. Uniform Resource Locator (URL) is the most commonly used form of a URI.
  * The URL consists mainly of two parts:
    1. The protocol used in the transfer, e.g., HTTP.
    2. The domain name.














