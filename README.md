# Enterprise Network Homelab

## Freitag Financial Services (FFS)

This project simulates a small enterprise network built in my home lab using Proxmox, OPNsense, Windows Server, Windows 11, Kali Linux, and Metasploitable.

The goal was to take an initially flat network and redesign it into a segmented environment using VLANs, firewall policies, DHCP, DNS, and Active Directory.

Rather than simply creating separate subnets, I configured and tested communication policies between Corporate, Server, and Security networks. The Security VLAN contains intentionally untrusted systems and is isolated from the production-style Corporate and Server networks.

## Project Goals

- Segment a flat network using 802.1Q VLANs
- Configure inter-VLAN routing through OPNsense
- Implement firewall rules between security zones
- Maintain Active Directory and DNS functionality across VLANs
- Provide DHCP addressing to Corporate clients
- Isolate Kali Linux and Metasploitable from production-style systems
- Maintain Internet connectivity where appropriate
- Test and validate the final network design
- Troubleshoot real configuration and service conflicts encountered during implementation

## Network Topology

![Enterprise Network Topology](diagrams/network-topology.png)
