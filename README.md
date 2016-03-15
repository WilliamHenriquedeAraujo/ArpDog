# ArpDog
This Dog barks when there's a strange MAC Address on the neighborhood.

# What is ArpDog?
It's a bunch of bash scripts that checks the ARP Table of SNMP devices and send a notification when detects a spoofed address.

# Requirements
SNMP enabled on monitored devices.

# What OID's are polled for the ARP table?
1.3.6.1.2.1.4.22 (ipNetToMediaTable) and 1.3.6.1.2.1.3 (AT - deprecated).

