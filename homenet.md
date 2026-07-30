# Home Network Documentation

## Physical Network Topology
<img width="1193" height="1594" alt="Physical Network Topology" src="https://github.com/user-attachments/assets/32827ba0-8181-4410-a164-18e7c7d3749e" />

## Logical Network Topology
<img width="1490" height="1028" alt="Logical Network Topology" src="https://github.com/user-attachments/assets/a0c78df0-52f4-4326-96d7-a3e4d867df90" />

## Network Addressing Information

| Device | IP Address |
| ------ | ---------- |
| Router/Firewall | 192.168.10.1 |
| Switch | 192.168.10.2 |
| Wireless Access Point | 192.168.10.3 |
| Printer | 192.168.10.5 |
| Laptops | DHCP |
| Smart Phones | DHCP |
| Tablet | DHCP |
| TV | DHCP |
| Indoor Wireless Security Cameras | DHCP |
| Smart Lock | DHCP |

Note: No network segmentation or subnets yet, to be done in the  near future.
No server yet, server setup and configuration still ongoing

## Network Device Inventory

| Device | Information |
| ------ | ----------- |
| Mini-PC | Protecli Vault (*specs*) (*serial number*) |
| Switch | Cisco  POE Multi-layer Switch (*specs*) (*serial number*) |
| Wireless Access Point | Ubiquiti UniFi 6+ (*specs*) (*serial number*) |

## Network Services

OPNSense - Installed OPNSense on the mini-PC to serve as the network router and firewall

DNS - Unbound DNS as recursive DNS server, incorporated with OPNsense, installed on the mini-PC

UniFi Network Server - used to manage the wireless access point and the connected devices, installed on the main laptop

## Revision History

homenet version 1.0

