![[Pasted image 20250713222820.png]]
# IP protocol and IP addresses
## IP protocol
Works with layer 3 devices that use the *IP header* to identify and process network traffic that flows in the form of packets. All routers inspect the destination address of each packet, but firewalls also inspect the sources address to identify the source of the traffic
## IP addresses
- Uses quad dot notation
- Decimal range form 0 to 255
# IP
IP is a usable, rout-able -> can be routed outside the network it originated in
>[!NOTE]
>IP is rout-able but addresses vary
>But not all IP addresses are rout-able
>

Routing is the path for data, which travels in the form of packets within or outside a network. These packets contain information and a header information at the beginning called *IP header*
# IP header
![[Pasted image 20250713224923.png]]
>[!NOTE]
>	TTL is an 8-bit field. It can contain value from 0 to 255.
>	TTL be set at 64 for most normal traffic
>	TTL is measured in hops for the IP protocol, but in some protocol like DNS, it can be measured in seconds

![[Pasted image 20250713231034.png]]

![[Pasted image 20250713231345.png]]
# Packet analyzers
## Wireshark
Caputre packet
1. Frame
2. Layer 2 data
3. Layer 3 data
4. Source IP address
5. Destination IP address
IP addresses also have components like: network masks, IP address prefixes and default gateway.
# Network mask (subnet mask)
![[Pasted image 20250713235619.png]]
# Broadcast IP addresses
![[Pasted image 20250713235858.png]]
# IP address prefix
![[Pasted image 20250714000004.png]]
# Default gateway
![[Pasted image 20250714000042.png]]
The default gateway is the ip of router in the network (usually) [[Routers and Routing Tables]]