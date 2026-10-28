# Assigning Static IPs to Server and Client

Accessed ethernet properties.  
Accessed IPv4 properties  
Assigned static IP address to server: 192.168.10.10  
Assigned subnet mask 255.255.255.0  
Assigned a loopback DNS server address: 127.0.0.1 to tell the server to look at itself for DNS lookup.  

![Alt Text](images/1.png)

# Assigning Static IP to Client and connecting to DNS server

Process repeated for the Client Computer  
DNS Address Assignment: 192.168.10.10 to tell client to look to server for DNS lookup.

![Alt Text](images/2.png)

To test connection, the firewall was disabled.  
Risk was minimal because both computers are isolated on the same network

![Alt Text](images/3.png)

# Test Connection

Connection was tested by pinging the server from the client computer using server IP address  

![Alt Text](images/4.png)

# Installing Active Directory Domain Service (AD DS) Role

Server Manager -> Manage -> Add Roles and Features -> Active Directory Domain Services  

![Alt Text](images/5.png)

# Promote Server to Domain Controller

Assigned the server as the domain controller  
Assigned root name "homelab.local"  
Assigned a Directory Services Restore Mode (DSRM) password  

# Resolve server domain name to its static IP for client computer

Command "nslookup" on Client computer to make sure it resolves to the server IP

![Alt Text](images/7.png)

# Add Client to Domain

Access Client System Properties  
Select "domain" and assigned server domain name  

![Alt Text](images/8.png)

[← Back to Main Portfolio](README.md)
