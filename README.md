
# Table Of Content

- [What is a router?](https://github.com/amaitou/NetPractice#what-is-a-router)
- [What is a switch?](https://github.com/amaitou/NetPractice#what-is-a-switch)
- [Difference between routing, router, switching, and switch?](https://github.com/amaitou/NetPractice#difference-between-routing-router-switching-and-switch)
- [Subnetting & how it works?](https://github.com/amaitou/NetPractice#subnetting--how-it-works)
- [IP overlap](https://github.com/amaitou/NetPractice#ip-overlap)
- [How does a router works](https://github.com/amaitou/NetPractice#how-does-a-router-works)
- [Default router](https://github.com/amaitou/NetPractice#default-router)
- [Resources](https://github.com/amaitou/NetPractice#resources)

# Net_Practice

The project comprises 10 levels (exercises) involving non-functioning network diagrams. Each level has a goal to achieve, representing issues that need to be resolved for the network to run properly. <br />

This document aims to provide an overview of fundamental networking concepts, focusing on routers, switches, routing, switching, subnetting, and IP overlap. It is designed for beginners to gain a basic understanding of these topics as well to find it easy to solve `NetPractice`'s Levels.

---
- ### **What is a router?**

	A router is a networking device that connects different networks together and forwards data packets between them. It operates at the network layer of the OSI (Open Systems Interconnection) model. Routers use routing tables to determine the best path for data to travel from the source to the destination across multiple networks. They are essential for enabling communication between devices on different networks, such as connecting a home network to the internet.

	---

- ### **What is a switch?**

	A switch is a networking device that operates at the data link layer (Layer 2) of the OSI model. Its primary function is to connect devices within the same local area network (LAN). Switches use MAC (Media Access Control) addresses to forward data packets to the correct destination device within the same network segment. Unlike routers, switches do not make decisions based on IP addresses or perform routing between different networks.

	---

- ### **Difference between routing, router, switching, and switch?**

	- `Routing` -> Routing refers to the process of determining the best path for data to travel from a source to a destination across an interconnected network. It involves making decisions based on network metrics like distance, bandwidth, and congestion to ensure efficient data transmission.

		---

	- Router -> A router is a physical or virtual device responsible for forwarding data packets between different networks. It uses routing protocols and maintains routing tables to make intelligent decisions about data transmission.

		---

	- `Switching` -> Switching is the process of forwarding data packets within the same local network. It occurs at the data link layer and uses MAC addresses to direct packets to the appropriate destination device.

		---

	- `Switch`: A switch is a physical or virtual device that facilitates switching. It connects multiple devices within a local network and directs data packets based on the MAC address.

	---
- ### **Subnetting & how it works?**

	Subnetting is a technique used to divide a larger IP network into smaller, more manageable sub-networks called subnets. It helps in efficient utilization of IP addresses and allows for better network organization and security.

	__How subnetting works__:

	IP addresses are divided into two parts: the network portion and the host portion. The division between these portions is determined by a subnet mask.
	Subnet masks are used to identify how many bits represent the network part and how many bits represent the host part of the IP address.
	By borrowing bits from the host portion, an administrator can create multiple subnets, each with its own range of IP addresses.
	Subnetting allows network administrators to control traffic flow, manage security, and optimize the use of IP addresses within the network.

	> for more information check this [playlist](https://www.youtube.com/watch?v=BWZ-MHIhqjM&list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE&pp=iAQB)

	---

- ### **IP overlap**

	IP overlap occurs when two or more networks have IP address ranges that conflict with each other. This conflict results in communication issues between devices in these networks since the routers are unable to differentiate between the intended destinations.

	IP overlap is usually unintended and can happen during network mergers, when setting up new networks without proper planning, or due to misconfiguration. Resolving IP overlap involves reconfiguring the conflicting IP address ranges to ensure uniqueness and proper 

	---

- ### **How does a router works?**

	A router works by examining the destination IP address of incoming data packets and using its routing table to determine the best path for the packet to reach its destination. The routing table contains information about various network destinations and the associated next-hop routers or interfaces.

	`The basic steps of how a router works are as follows`:

	- **Receiving Data** -> When a data packet arrives at a router, it reads the destination IP address from the packet header.
		
		---
	
	- **Looking Up in Routing Table** -> The router consults its routing table to find the entry that matches the destination IP address.
	
		---
	
	- **Determining Next Hop** -> Based on the routing table entry, the router determines the next-hop router or interface through which the packet should be forwarded.
	
		---

	- **Forwarding** -> The router forwards the packet to the determined next-hop router or directly to the destination device if it is on a directly connected network.
	
		---
	
	- **Repeat Process** -> This process continues until the packet reaches its final destination.

	> Routers use various routing protocols, such as OSPF (Open Shortest Path First) or BGP (Border Gateway Protocol), to exchange routing information with other routers, ensuring that they have up-to-date information about network topology and available paths.

	---

- ### **Default router**

	A default router, also known as a default gateway, is a special type of router that serves as the entry and exit point for traffic between a local network and external networks, such as the internet. When a device on a local network wants to communicate with a device on another network (outside the local network), it sends the data packets to the default router. The default router then takes care of forwarding the packets to the appropriate destination on the external network.

	---
- ### **Resources**

	- [Understanding IP Address Overlaps](https://www.youtube.com/watch?v=vM1sO_huJvw&t=193s)
	- [Understanding Subnetting](https://www.youtube.com/watch?v=5WfiTHiU4x8&list=PLIhvC56v63IKrRHh3gvZZBAGvsvOhwrRF)
	- [Understanding Subnneting 2](https://www.youtube.com/watch?v=BWZ-MHIhqjM&list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE&pp=iAQB)
	- [Network Fundamentals](https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi&pp=iAQB)
	- [Routing Tables in Computer Network](https://www.geeksforgeeks.org/routing-tables-in-computer-network/)
	- [Understanding Default Routes](https://www.juniper.net/documentation/us/en/software/junos/is-is/topics/concept/default-route-understanding.html#:~:text=A%20default%20route%20is%20the,of%20the%20device's%20local%20subnets.)

	---
- ### **Contact Me**

* [Twitter][_1]
* [Instagram][_2]

[_1]: https://twitter.com/amait0u
[_2]: https://www.instagram.com/amait0u