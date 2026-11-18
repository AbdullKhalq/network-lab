# Introduction
A list of commands that I think are useful to me. I like to have a note of them so whenever I need them I can find them easily. Some command descriptions are written by me and others are generated with an AI model.

## PC/Desktop
Most commands are either in CMD or Powershell (Windows).



## Cisco IOS CLI

The first sections or so, mainly followed the process I made to create a SOHO network in Cisco Packet Tracer.

### First time booting configuring a router

1. `Router>enable`: is the Cisco IOS command used to move from User EXEC mode into Privileged EXEC mode
2. `Router#configure terminal`: moves you from Privileged EXEC mode into Global Configuration mode. This is where you change the router’s configuration, such as interfaces, routing, passwords, DHCP, and other global settings.
3. `Router(config)#hostname Router0`: Optionally changes name of the host. Currently, a router.

### Configuring an interface.

1. `Router0(config)#interface g0/0`: configures the chosen interface `g0/0`.
2. `Router0(config-if)#ip address 192.168.10.1 255.255.255.0`: configures the previously selected interface `g0/0` with the given IP address `192.168.10.1` followed by the subnet mask `255.255.255.0`.
3. `Router0(config-if)# no shutdown`: enables the interface. In other words, It could be said that it reverses the shutdown state.

### DHCP

- `Router(config)# ip dhcp excluded-address 192.168.10.1 192.168.10.20`: tells the Cisco router’s DHCP server not to give out addresses from `192.168.10.1` through `192.168.10.20`.
- `Router(config)# ip dhcp pool OFFICE`: creates a DHCP pool named OFFICE and enters DHCP pool configuration mode.

Information given by the DHCP

- `Router(dhcp-config)# network 192.168.10.0 255.255.255.0`
- `Router(dhcp-config)# default-router 192.168.10.1`
- `Router(dhcp-config)# dns-server 203.0.113.10`

### Port Address Translation (PAT)

Configuring PAT internal side

1. Router# configure terminal
2. `Router(config)# interface g0/0`
3. `Router(config-if)# ip nat inside`: sets the interface `g0/0` as the inside of NAT.
4. `Router(config-if)# exit`

Configuring PAT outside side

1. `Router(config)# interface g0/1`
2. `Router(config-if)# ip nat outside`: sets the interface `g0/1` as the outside of NAT.
3. `Router(config-if)# exit`

Making an Access Control List (ACL) that identifies the private addresses to translate.
1. `Router(config)# access-list 1 permit 192.168.10.0 0.0.0.255`: standard access control list (ACL) 1 entry that matches the entire 192.168.10.0/24 network.
    Here: 192.168.10.0 is the network being matched, and: 0.0.0.255 is the wildcard mask. It means: 0.0.0 → these octets must match exactly. .255 → the last octet can be anything
    So the ACL matches:
    192.168.10.0
    through
    192.168.10.255
2. `Router(config)# ip nat inside source list 1 interface g0/1 overload`: command configures PAT (Port Address Translation), also called NAT overload.  
    Translate source addresses matched by ACL 1 to the IP address assigned to g0/1, and allow many inside devices to share that one address by using different port numbers.  
    For example:  
        PC1: 192.168.10.21:5000  
        PC2: 192.168.10.22:5000  

    could become something like:  
    203.0.113.5:30001  
    203.0.113.5:30002  

    where 203.0.113.5 is the address on g0/1.


## General commands

- `exit`: Returns back one configuration level.
