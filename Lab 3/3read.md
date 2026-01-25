LAB 3: Study and Simulation of Basic Networking Devices Using Cisco Packet Tracer
OBJECTIVE:
To study the working of hub, switch, bridge, router, and repeater.
To understand the OSI layers of different networking devices.
To design and simulate a network using Cisco Packet Tracer.
To verify communication between computers using ping.
THOERY:
1. Hub
A hub is a simple networking device used to connect multiple computers within a network. It operates at the Physical Layer of the OSI model. When a hub receives data from one device, it broadcasts the signal to all connected devices without checking the destination. Because of this broadcasting behavior all devices share the same bandwidthm, which increases the chances of data collisions and reduces overall network efficiency. In this experiment the hub demonstrates how data transmission occurs without any filtering or intelligent decision making.
2. Switch
A switch is an advanced networking device used to connect devices within a LAN. It operates at Data Link Layer of the OSI model. Unlike a hub a switch forwards data only to intended destination by using MAC addresses which significantly reduces collisions and improves network performance.
3. Bridge
A bridge is a networking device used to connect two or more LAN segments. It also opiates at the Data Link Layer of the OSI model. A bridge filters network traffic by learning MAC addresses and allows only necessary data to pass between network segments. This helps reduce unnecessary traffic and enhances network performance.
4. Router
A router is Network Layer device used to connect different IP networks and enable communication between them. Unlike switches which operates within a single network, routers forward data packets between multiple networks based on IP addresses.
It has multiple interfaces, each assigned a unique IP address belonging to the network it connects to. These interface IP addresses act as the default gateway for devices in their respective networks. When a device needs to communicate with a device in another network, the data is first sent to the default gateway, and the router forwards the packet to the destination network.
5. Repeater
A repeater is a networking device used to extend the coverage area of a network. It operates at the Physical layer of the OSI model. The repeater receives weak or distorted signals, regenerates them, and retransmits them to restore signal strength over long distances. 
OUTPUT:
1. Hub
Step 1: PC0 sends a message










Step 2: Hub receives the message 













Step 3: Hub broadcasts the message












Step 4: PC1 receives the message, but other devices ignore the reply since it is not intended for them. (Shown in Packet Tracer by red X marks on their links)

















Step 5: PC1 responds the message to PC0





















2. Switch
Step 1: PC0 sends a message








Step 2: Switch receives the message








Step 3: The switch checks its MAC address table and forwards the message to PC1 and then          PC1 accepts the message. 








3. 
3. Bridge
Step 1: Ping to check if connection works.









Step 2: Ready to send message.









Step 3: Message sent to switch first.









Step 4: Switch sends the message to the Bridge.










Step 5: The Bridge forwards the message to the switch connected to the destination computer.









Step 6: The switch now forwards the message to the destination computer.










4. Router
Step 1: Ping to check if the connection works








Step 2: Message ready to send








Step 3: The Source sends the message to the switch it’s connected to.











Step 4: Switch sends the message to the router.










Step 5: The Router sends to the switch that the destination is connected to.










Step 6: Then the message is received by the destination computer.








5. Repeater
Step 1: Ping to check the connection.








Step 2: Message ready to send.









Step 3: The Source sends the message to the switch it’s connected to.










Step 4: The Repeater receives the message and sends it to the switch destination computer is connected to.









Step 5: Then the message is received by the destination computer.










DISCUSSION:
In this experiment, basic networking devices, including hubs, switches, bridges, repeaters, and routers, were studied and implemented using Cisco Packet Tracer. The hub and repeater were observed to work at the physical layer, where they forward or regenerate signals without controlling network traffic.
The switch and bridge operating at the data link layer, forwarded data using MAC addresses, which improved network efficiency by reducing unnecessary traffic. The router working at the network layer connected two different IP networks by using proper IP addressing and default gateway configuration. This experiment helped in understanding the functions of different networking devices and their roles in data communication within and between networks.

CONCLUSION:
This experiment helped in understanding the operation of basic networking devices, including hubs, switches, bridges, repeaters, and routers. It showed how hubs and repeaters extend the network, switches and bridges manage traffic within a network, and routers connect different IP networks. Overall, the experiment clarified the role of each device and its operation at different OSI layers.
