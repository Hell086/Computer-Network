LAB 4:Subnetting and Supernetting using Cisco Packet Tracer
OBJECTIVE:
To design and simulate a subnetting and supernetting using Cisco Packet Tracer.
To verify communication between computers using the ping command.
SOFTWARE REQUIRED:
Cisco Packet Tracer
THOERY:
1. Subnetting:
Subnetting is a technique used in computer networks to divide a large network into smaller subnets. It helps in efficient utilisation of IP addresses, reduces network congestion, and improves security and management. By borrowing bits from the host portion of an IP address, subnetting creates multiple logical networks within a single network address. It is commonly used in organisations to separate departments or segments while using the same base network.
2. Supernetting:
Supernetting is the opposite of subnetting, where multiple smaller networks are combined into a larger network. It is used to reduce the number of routing table entries and simplify routing. Supernetting works by borrowing bits from the network portion of the IP address, allowing several contiguous networks to be represented as a single route. This technique is widely used in large networks and on the Internet to improve routing efficiency and scalability.






NETWORK DESIGN:
Base network 192.168.1.0/24 required number of subnets is 4 and number of IP addresses per subnet=64
Subnet Table:
Subnet
Network address
Broadcast Address
1st usable
Last usable
1
192.168.1.0/26
192.168.1.63/26
192.168.1.1/26
192.168.1.62/26
2
192.168.1.64/26
192.168.1.127/26
192.168.1.65/26
192.168.1.126/26
3
192.168.1.128/26
192.168.1.191/26
192.168.1.129/26
192.168.1.190/26
4
192.168.1.192/26
192.168.1.254/26
192.168.1.193/26
192.168.1.253/26

Supernet Table:
Device
IPV4 Subnetmask
Broadcast Address
Default gateway
Router0
(FastEthernet0/0)	
192.168.0.1	
255.255.252.0
PC6
192.168.0.10
255.255.252.0
192.168.0.1
PC7
192.168.1.10
255.255.252.0
192.168.0.1
PC8
192.168.2.10
255.255.252.0
192.168.0.1
PC9
192.168.3.10
255.255.252.0
192.168.0.1

NETWORK TOPOLOGY:
Subnetting:
We have two subnets connected to a single router. One consisting PC0,1,2 and another consisting PC3,4,5
Circut:

OUTPUT:
1. Subnetting:
Step 1: Ping to check if the connection works.



Supernetting:
We have single supernet connected to a router . Supernet consisting of  PC6,7,8,9 connected to a switch
Circuit:

Supernetting:
Step 1: Ping to check if the connection works







DISCUSSION:
In this lab experiment, subnetting and supernetting were performed using Cisco Packet Tracer to understand IP address allocation and routing. Subnetting helped to divide a large network into smaller sub-networks, making IP address usage more efficient and reducing network congestion. Supernetting was used to combine multiple networks into a single network, which reduced routing table size and simplified routing. The configurations were tested in the simulator, and successful packet transmission confirmed correct implementation of the concepts.
CONCLUSION:
The subnetting and supernetting lab using Cisco Packet Tracer provided practical knowledge of IP address management and routing efficiency. The experiment reinforced theoretical concepts and demonstrated how proper network design improves performance and scalability. Overall, the lab helped build a strong foundation in designing and managing computer networks.

