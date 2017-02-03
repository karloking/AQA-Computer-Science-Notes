#TCP/IP

>You should be able to :
>* Describe the role of the four layers of the TCP/IP
>stack (application, transport, network, link).
>* Describe the role of sockets in the TCP/IP stack.
>* Be familiar with the role of MAC (Media Access
>Control) addresses.
>* Explain what the well-known ports and client ports
>are used for and the differences between them.

|Layer Name | Description |
|:---------:|:------------|
|Application | Encodes the data being sent|
|Transport |  Splits the data into manageable chunks, adds port number information. Provide error checking and acknowledgement of packets sent and can retransmit packets if required. |
|Network | Adds IP addresses stating where the data is from and where it is going |
| Link | Adds MAC address information to specify which hardware device the message came from, and which hardware device the message is going to|

##Sockets
**Sockets:** - is an endpoint of communication flow on a computer network that uniquely identifies an application and device. 

A socket can be referred to by a process (a running computer program) by using a socket descriptor, a type of handle (abstract reference, often represented internally as an integer). A process first requests that the protocol stack create a socket, and the stack returns a descriptor to the process so it can identify the socket. 

## MAC Addressses
**MAC Addresses:** It provides a unique identifier for every node on a local area network (LAN), encoded into network interface card in the format of two hex digits seperated by colons, e.g. `02:32:45:77:89:ab`

##Well Known Ports

|Port | Protocol | Description |
|:---------:|:------------:|:---------|
| 21 |  File Transfer Protocol (FTP) | a protocol for handling file uploads and downloads |
|  25 | Simple Mail Transfer Protocol (SMTP) |  a protocol for sending emails |
|  80 & 8080 | HyperText Transfer Protocol (HTTP)| a protocol for transmitting and displaying web pages |
|  110 | Post Office Protocol v3 (POP3) | |
|  143 | Internet Message Access Protocol (IMAP)||
|  443 | HyperText Transfer Protocol over SSL/TLS (HTTPS)||
|  666 | Doom Multiplayer game||
|  989 | Secure FTP (SFTP) ||
|  23 | Telnet ||

  
 
