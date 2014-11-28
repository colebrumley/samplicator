samplicator
===========

This simple program listens for UDP datagrams on a network port, and sends copies of these datagrams on to a set of destinations. Optionally, it can perform sampling, i.e. rather than forwarding every packet, forward only 1 in N. Another option is that it can "spoof" the IP source address, so that the copies appear to come from the original source, rather than the relay. Currently only supports IPv4.

It can been used to distribute e.g. Netflow packets, SNMP traps (but not informs), or Syslog messages to multiple receivers.

This is a Docker Automated build from the Google Code source.
