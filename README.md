# DMZ_NAPT
DMZ(demilitarized zone) and IP masquerade (NAPT: Network Address Port Translation) 
provide WAN-to-LAN and LAN-to-WAN translation services.

DMZ translates a single-IP WAN server to a single-IP LAN server.

<img src=dmz.png height=200 width=800>

IP masquerade or NAPT translates a single-IP WAN server with several ports 
to multiple LAN servers with ports.

<img src=napt.png height=200 width=800>
https://en.wikipedia.org/wiki/Port_forwarding#/media/File:NAPT-en.svg

NAPT table shows mapping between a WAN IP with ports and LAN IPs with ports.
