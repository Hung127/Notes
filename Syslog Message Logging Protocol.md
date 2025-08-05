# What is Syslog protocol
Syslog: the standard abbreviation for message logging
Separates the:
- Software that generate messages
- The system that stores them
- Software that reports and analyzes messages
# Message format
Includes vendor-specific extensions: each message is labeled with a code that indicates the software type generating the message
Displays facility codes and severiry levels
![[Pasted image 20250805234826.png]]
# The Syslog protocol
![[Pasted image 20250805235054.png]]
# Syslog layers
![[Pasted image 20250805235134.png]]
# Syslog key players
![[Pasted image 20250805235238.png]]
# Syslog message component
![[Pasted image 20250805235338.png]]
## Facility codes
![[Pasted image 20250805235455.png]]
![[Pasted image 20250805235515.png]]
## Severity levels
Applied severity levels from 0 to 7
Set Syslog message severity levels to only identify significant messages
![[Pasted image 20250805235718.png]]
![[Pasted image 20250805235743.png]]
![[Pasted image 20250805235827.png]]
![[Pasted image 20250805235904.png]]