# CCNA : Networking Cisco 200-301

# Basic Networking Terms

Network is the connection between two or more devices.

## Need of Networks

The need of the networks was that, the people needed to share resources. These resources were printers, documents files e.t.c. In old days the people were sharing the files by using sneakernet ( use of foot to go to each other house xD :) ) to transfer files. In corporate sector the, printers were one of the resources, if a pc had to use the printer then the files would be copied and pasted in the printer to print the files.

Now the networks provided the digital interface for us to share the resources across distance and in different devices.

## Basic Type of Network

The most basic type of network is the network between two devices like laptops. RJ45 Connector is the type of ethernet cable (utp unshielded twisted pair in this case) which are plugged in NIC’s to connect to internet. The network interface card is the card which can be used to connect to the network. 

MAC (Media Access Control )Address is the address assigned to the network interface card when it connects to any network within network segment. Its most common used is in IEEE 802 devices like ethernet,wireless and bluetooth devices.

## History of Networks

Now the internetr/netowkring didn’t started with the utp cable while it use the 10base5 cable which are not easy to use. In past we used tcables like thinknet and [thinnet .By](http://thinnet.By) the name we can understand in thicknet the cables were thick and in thinnet the cables are thin. In today’s world we used utp cables and the fibre optic cables.

## Server, Client, Protocol and Ports

As we know that the need of network is that we want to share resources. In this mechanism there are different roles. Like the devices which are providing the resources or certain services are called the servers and the devices which are being served are called client.

Now servers are really powerful devices having more power than clients while client devices can be of any specification. These servers are hosted across a network and clients connect to network to access the services. 

As humans communicate to each other in various languages, in same way the computers communicate with each other using different protocols. Now in case of humans the speech rate or pitch or frequency is same/different but humans vary and understand it. Servers cannot understand it so it uses different ports for different protocols to communicate with other devices or to serve services. HTTP uses 80, HTTPS uses 443 and FTP uses 20,21 port. One server can use multiple ports to serve multiple services.

## Configuring a Network

Now when connecting two PC’s we use a cross over cable, now with that cable we connect the two devices (PC) and each device has seperate MAC Address which can also be changed The IP Addresses are dynamically allocated by the DHCP Dynamic Host Configuration Protocol used by routers. If there is no DHCP then we have to manually assign it any IP or it can use the local special ip address to communicate to local networks.

After connecting the devices, one can ping other device to see its presence, its like “Hey server are you there?” and server replies “yeah im here” if server doesn’t replies then its dead or not listening on that port.

Now if we open configuration of server and turn http on and use client to open up web browser to go to http://{{IP_ADDRESS}} then server will serve me with the html pages. We can use the simulation feature in packet tracer to see the packets too which you can inspect later on,