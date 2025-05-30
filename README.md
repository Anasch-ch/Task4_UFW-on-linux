# Task4_Setup and Use a Firewall onLinux

# UFW (Uncomplicated Firewall) on Linux.

##Objective

Configure and test basic firewall rules to allow or block traffic using UFW (Uncomplicated Firewall) on Kali Linux.
--Steps and Results
1. Check current firewall status and rules
2.  Enable UFW firewall
3.  Verify firewall status after enabling
4.  List current firewall rules with numbering
5.  Block inbound traffic on port 23 (Telnet)
6.  Test the blocked port (Telnet)
7.  Allow SSH traffic on port 22
8.  Remove the block rule on port 23 (restore original state)
9.  Final list of active rules

##Summary
UFW was installed and enabled on Kali Linux.

A rule was created to block incoming traffic on port 23 (Telnet), which was confirmed by the inability to connect via Telnet.

Another rule was added to allow incoming SSH traffic on port 22, ensuring secure remote management.

The block on port 23 was removed to restore the original firewall state.

The firewall by default blocks all incoming connections unless explicitly allowed.

Firewall filtering is based on rules specifying ports and protocols, which control whether traffic is allowed or denied.

How Firewalls Filter Traffic
Firewalls examine incoming and outgoing network packets and apply rules to allow or deny traffic based on parameters like:

Source and destination IP address

Port number (e.g., 22 for SSH, 23 for Telnet)

Protocol (TCP/UDP)

Direction (inbound/outbound)

This filtering helps secure systems by controlling network access and minimizing exposure to potential attacks.


#For detailed report ..,kindly refer above Task4.txt file...
Thankyou....
