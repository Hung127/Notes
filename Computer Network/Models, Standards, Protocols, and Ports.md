# Networking model
Describe architecture, component and design used to establish communication between source and destination systems.
Data packets follow the protocols of network model.
## OSI model (Open System Interconnection)
A conceptual framework used to describe the functions of a networking system
![[Pasted image 20250710205157.png]]
These are layers. Data flows across those layers when communicating over the network
1. **Application**: Users and application interact directly with software application
2. **Presentation**: Ensure that data is in a usable format and is where data encryption occurs
3. **Session**: Control the flow of information between different computers including authentication and re-connections
4. **Transport**: Manage the delivery and errors checking of data packets. Data is usually transported using TCP
5. **Network**: Responsible for interpreting the addresses and directing the path that data will take
6. **Data link**: Define the format of data on network, correct errors that may have happened in the **Physical** layer
7. **Physical**: Electrically || optically transmit raw, un-structured data over a physical medium
## TCP/IP model (Transmission Control Protocol/Internet Protocol)
A set of standards that allow computers to communicate on a network. This model is based on OSI model
![[Pasted image 20250710210149.png]]
# Networking standard
Define the rules for data communications needed for interoperability of networking technologies and processes
Standards are widely accepted protocols that engineers use to make sure the things they build integrate with existing devices and technology.
## De jure (formal standard)
Developed by an official industry or government body
EX: HTTP, HTML, IP,...
## De facto standard
Result from marketplace domination or practice
EX: QWERTY keyboard, Windows OS,...
![[Pasted image 20250710212404.png]]
# Protocol
A set of rules the describe how data is transmitted across different devices in the same network
Typically created according to industry standard
## Primary action
![[Pasted image 20250710212938.png]]
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two primary internet protocols
![[Pasted image 20250710213242.png]]
## TCP/IP suite
![[Pasted image 20250710213326.png]]
Together, these protocols provide a complete networking solution
## IoT network model
![[Pasted image 20250710213634.png]]
## Crypto Classic protocol
![[Pasted image 20250710214540.png]]
# Ports
![[Pasted image 20250710214743.png]]
This is some ports services [[Protocol table]]
# Socket
![[Pasted image 20250710215112.png]]