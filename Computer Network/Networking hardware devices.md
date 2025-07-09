# Networking hardware devices 
Enable communication and interaction on a computer network:
- Cables
- Servers
- Desktops
- Laptops
- Tablets
- Smartphones
- IoT devices
Im gonna learn about network devices that connect or route (*hubs, switches, routers, bridges, gateways*).
# Server
A **powerful** computer or device that stores files and applications.
- Other devices on the same network can access to the server -> client
- Users can access server a file or application from anywhere (*if they have proper level of access, usually password-based*)
# Nodes and clients
A node is a network-connected device that can send or receive information
A client is a node that access to the network through a server
All devices that can send, receive and create information on a network is are nodes.
The nodes that access the server to get on the network are clients
The server controls the level of access that clients have -> if a client fails, the network remains unchanged.
# Client-server networks
- FTP sites
- Web server
- Web browser
# P2P network
- Files sharing sites
- Discussion forums
- Media streaming
- VoIP services (*Voice over IP services*)
# Devices
## Hubs and switches
### Hub
- Connects multiple devices together
- When data is sent to a hub, it broadcasts that data to all devices except the sender
### Switch
Similar to a hub but
- Keeps a table of MAC addresses
- When receive data -> look up for proper MAC address forward the data to the right place -> **Just send data to the intended recipient** -> *more efficient than a hub*
> [!NOTES]
> When a switch or a hub fails, it brings **the entire server** down.
## Routers and modems
### Routers
Interconnect different networks or sub-networks
- Manage traffic between networks by forwarding *data packets* to the intended IP addresses
- Allow multiple devices to use the same internet connection
Router connects to modem. A router uses internal routing to direct packets effectively
- Particularly, it uses internal routing table, which is a list of path to various network destinations
- Read the packets's header to determine its path
- Consult the routing table to figure out the most efficient path
- Forward the packet
### Modem
Convert data into easy to transmit format to transmit across the network
- Data reaches its destination, and the *receiver* modem converts the data to its original form
- Most common modems are cables and DSL
## Bridge and gateways
### Bridge
Join 2 separated networks -> they can communicate with each other and work as a single network.
![[Pasted image 20250709223420.png]]

Bridges can be wired || wireless
#### Wireless
Can support such connections
- Wifi to wifi
- Wifi to Ethernet
- Bluetooth to wifi
#### Wired
Maybe all 🤓
### Gateway
A hard/software that allows data to flow from one network to another.
The difference between gateways and (*routers and switches*) is that they use multiple protocols to connect multiple networks
![[Pasted image 20250709224258.png]]
## Repeaters and WAPs
### Repeater
- Receive a signal and *re-transmit* it
- *Extend* a wireless signal
- Connect to wireless routers
### Wireless access point (WAP)
- Allow wifi devices to connect to a *wired* network
- Usually connect to a *wired* router as a standalone device
- Act as a central wireless connection point for computers equipped with wireless network adapters
- Is plugged into a *wired* network switch.
- Read each computers's MAC address and forward that to the *wired* switch.
>[!NOTES]
> If the wired network is connected to a router with internet access, the wireless network will also have internet access
## Network interface cards (NICs)
Help for connecting individual devices to a network
![[Pasted image 20250709225236.png]]
![[Pasted image 20250709225254.png]]
## Firewalls, proxies, IDS, and IPS
### Firewall
A firewall monitors and controls incoming and outgoing network traffic based on some predetermined security rules.
![[Pasted image 20250709230332.png]]
- Can be soft/hardware
- Routers and OS have built in firewalls
### Proxy server
- Work to minimize security risks
- Evaluate requests from clients and forward requests to the appropriate server *if those requests meet security requirements*
- Hide an IP address
- Save bandwidth
	- Example: download files, updates for one user, reuse for more users if needed.
### IDS (Intrusion Detection System)
Monitor network traffic and report malicious activity
### IPS (Intrusion Prevention System)
Inspect network traffic and remove, detain or redirect malicious items based on rule set by the network admin
![[Pasted image 20250709232039.png]]