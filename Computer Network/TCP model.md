## What is internet TCP/IP stack ?
Transmission Control Protocol/Internet Protocol(TCP/IP) is a practical network model developed by the Department of Defense (DoD) in the 1960s to support communication between different network devices on the internet. 

TCP is a set of communication protocols that supports network communication.

The TCP model is subdivided into five layers, each containing specific protocols.

![[Pasted image 20231212162840.png]]


1. **Application** : It contains all the higher-level protocols. Ex – HTTP, SMTP, DNS.
	
2. **Transport** : Its functionality is almost the same as the OSI transport layer. It  
	enables peer entities on the network to carry on a conversation. Ex – TCP, UDP  
	(User Datagram Protocol).
	
3. **Network Access/Link layer** : Decides which links such as serial lines or classic Ethernet must be used to meet the needs of the connectionless internet layer. Ex – Sonet, Ethernet. 
	
4. **DLL** : 
	-  Data framing: Adds header information to data packets to ensure they are delivered to the correct destination
	- Error control: Handles problems that occur as a result of bit transmission errors
	- Data flow: Ensures data flows at a pace that doesn't overwhelm devices that send and receive data
	
5. **Network Layer** :
	The network layer adds IP address/logical address to the data segments to form IP packets and finds the best possible path for data delivery.
	
	 **Common protocols used in the Network layer are :**
	 - **IP(Internet Protocol)**: IP uses the receiver’s IP address to determine the best path for the proper delivery of packets to the destination. When a packet is too large to send over a network medium, the sender host’s IP splits it up into smaller fragments. The fragments are reassembled into the original packet on the receiving host. IP is unreliable since it does not ensure delivery or check for errors.
	 
	- **ARP(Address Resolution Protocol):** ARP is used to find MAC/physical Addresses from the IP address.
	
	- **ICMP(Internet Control Message Protocol):** ICMP is responsible for error reporting.