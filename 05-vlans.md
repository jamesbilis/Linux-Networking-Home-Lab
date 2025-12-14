# VLAN Configuration

## VLAN Design
- VLAN 10: Servers
- VLAN 20: Clients

## Virtual Machines
- Ubuntu-VLAN-Server
- Ubuntu-VLAN-Client

## VLAN Isolation Test
- VLAN 10 (Server) cannot reach VLAN 20 (Client)
- VLAN 20 (Client) cannot reach VLAN 10 (Server)

This confirms proper Layer 2 segmentation using 802.1Q VLAN tagging.

## Goal
Implement VLAN-based segmentation using Linux VLAN subinterfaces
and verify isolation between networks.
