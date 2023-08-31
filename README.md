# Network_scanner
Basic ARP network scanner to identify targets on a local network

Python can be used to build a simple ICMP (Internet Control Message Protocol) scanner to identify potential targets on the network. However, ICMP packets can be monitored or blocked as the target organization would not expect a regular user to “ping a server”. On the other hand, systems can be configured to not respond to ICMP requests. These are the main reasons why using the ARP (Address Resolution Protocol) to identify targets on the local network is more effective.

# Pre-req
You will need to install scapy before running
sudo apt install python3-scapy

You will also need to update the ip_range in the code to match your local network

# Usage
python3 networkscanner.py
