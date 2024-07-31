# Subnetting
Subnets – also referred to as a netmask

Definition: It is the subdivision of an IP network

Standard: 255.255.255.0

Every section in a netmask represents an octet.

An example: 192.168.1.6/24

*   Represents any private IP address between 192.168.1.0 to 192.168.1.255 except 192.168.1.6 (As it is being hosted on that particular address)

*   Subnets can increase efficiency, as traffic does not need to travel through unnecessary routers to reach its destination
*   Subnets allow certain parts of the network to of a higher bandwidth priority than others
*   Increases cost and complexity of the network, as more routers and switches are required to config and partition the network into subnets, thus overall cost increases.
*   Different types of subnets
    *   utilises different network masks and contains amounts of hosts
    *   Bigger subnets will contain bigger “network size”; thus network scanning will be more complicated

Netmask sets the boundaries for the size of the subnet; the private IP can vary between the netmask (aside from the locked down bits)

Multiple subnets are possible within a single subnet; its a partition to contain specific sections of a network, thus different subnets can be created at different “destinations” with its own host limit