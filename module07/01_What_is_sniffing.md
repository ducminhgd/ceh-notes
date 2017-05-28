# Sniffing and eavesdropping

Sniffing is a process of monitoring and **capturing all data packets** passing through a given network using sniffing tools.

Sniffers operate at the **Data Link layer** of the OSI model. Networking layers in the OSI model are designed to work indenpendently of each other; if a sniffer sniffs data in the Data Link layer, the upper OSI layer will not be aware of the sniffing.

## Sniffing types

### Passive sniffing:

Passive sniffing means sniffing through a **hub**, on a hub the traffic is sent to all port.

It involves only monitoring of packets sent by others without sending **any additional data packets** in the traffic network

In a network that use hubs to connect sytems, all **hosts on the network** can see all traffice therefore attacker can easily capture traffice going through the hub

Hub usage is out-dated today. Most modern networks use **switches**.

### Active sniffing

**Active sniffing** is used to sniff **switch-based network**

Active sniffing involves **injecting address resolution packets (ARP)** into the network to flood the switch's Content Addressable Memory (CAM) table, CAM keeps track of which host is connected to which port.

## How an attacker hacks the network using sniffers

1. An attacker connects his computer to a switch port.
2. He runs discovery tools to learn about network topologys
3. He identifies victim's machine to target his attacks.
4. He poisons the victim machine by using ARP proofing techniques.
5. The traffice destined for the victim machine is redirected to the attacker.
6. The hacker extracts password and sensitive data from the redirected traffic.

## Hardware Protocol Analyzer

## PRISM: Planing tool for Resource Integration, Synchronization and Management