- Author:: [[community.infoblox.com]]
- Full Title:: Life as an [[IPv6]] Technology Laggard
- Category:: [[articles]]
- URL:: https://community.infoblox.com/t5/IPv6-CoE-Blog/Life-as-an-IPv6-Technology-Laggard/ba-p/11989
- ### Highlights first synced by [[readwise]] [[September 2nd, 2020]]
    - your branch traffic is tunneled through the service provider network and your employees often complain about the slowness of their applications and more frequent application connection resets. 
    - All of the operating systems on the nodes on your networks were IPv6-enabled and preferred to use IPv6 whenever possible. 
    - These IPv6-enabled nodes were sending out ICMPv6 multicast packets on the network. They were sending out ICMPv6 Neighbor Solicitation (NS) messages to perform Duplicate Address Detection (DAD) for their self-assigned link-local FE80::/10 addresses. They were sending Router Solicitation (RS) messages when they booted up to try to contact their local IPv6 router. 
    - These IPv6-enabled nodes also attempted to tunnel IPv6 packets over your IPv4-only core network 