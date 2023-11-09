
# QUIC (Quick UDP Internet Connections)

https://fasterdata.es.net/data-transfer-tools/quic-quick-udp-internet-connections

QUIC (Quick UDP Internet Connections, pronounced quick) is an experimental transport layer network protocol designed by Google.  The overall goal is to reduce latency compared to that of TCP.  Think of QUIC as being similar to TCP+TLS+HTTP/2 implemented on UDP.  Because TCP is implemented at the lowest levels of machinery (operating systems, routing firmware), making changes to TCP is next to impossible given the amount of upgrades that would need to occur.  Since QUIC is built on top of UDP, it suffers from no such limitations and can be integrated into end host applications.  