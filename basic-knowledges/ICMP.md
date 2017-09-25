The Internet Control Message Protocol (ICMP) is a supporting protocol in the Internet protocol suite. It is used by network devices, including routers, to send error messages and operational information indicating, for example, that a requested service is not available or that a host or router could not be reached

ICMP is defined in [RFC 792](https://tools.ietf.org/html/rfc792)

# ICMP datagram structure

The ICMP packet is then encapsulated in an IPv4 packet. The packet consists of header and data sections.

## Header

The ICMP header starts after the IPv4 header and is identified by IP protocol number '1'. All ICMP packets have an 8-byte header and variable-sized data section. The first 4 bytes of the header have fixed format, while the last 4 bytes depend on the type/code of that ICMP packet.

1 byte: type
1 byte: code
2 bytes: checksum
4 bytes: the rest of header base on type/code

[Type & Code](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol#Control_messages)


**Checksum:** Error checking data, calculated from the ICMP header and data, with value 0 substituted for this field. The Internet Checksum is used, specified in [RFC 1071](https://tools.ietf.org/html/rfc1071).

## Data

ICMP error messages contain a data section that includes a copy of the entire IPv4 header, plus the first eight bytes of data from the IPv4 packet that caused the error message. This data is used by the host to match the message to the appropriate process. If a higher level protocol uses port numbers, they are assumed to be in the first eight bytes of the original datagram's data.

The variable size of the ICMP packet data section has been exploited. In the "Ping of death", large or fragmented ping packets are used for denial-of-service attacks. ICMP data can also be used to create covert channels for communication. These channels are known as ICMP tunnels.