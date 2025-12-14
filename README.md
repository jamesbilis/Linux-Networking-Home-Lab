# Linux Networking & Systems Administration Home Lab

This repository documents a self-directed Linux networking home lab focused on
system administration, virtual networking, and network segmentation using
Ubuntu Server and VMware Workstation.

The goal of this lab was to build a realistic virtual environment, understand
how networking components interact across layers, and practice troubleshooting
and documentation in a reproducible way.

---

## Lab Environment

- Hypervisor: VMware Workstation
- Operating System: Ubuntu Server
- Networking: VMware NAT (VMnet8), Host-Only (VMnet1), LAN Segments
- Tools: Netplan, NetworkManager, iproute2, systemd utilities

---

## Objectives

- Establish a Linux network baseline
- Compare VMware adapter modes and routing behavior
- Configure static IPs and DHCP reservations
- Implement VLAN-based network segmentation
- Design and test inter-network routing concepts
- Practice Linux networking troubleshooting and documentation

---

## Lab Documentation

The lab was completed in phases and documented step-by-step:

- **01 – Network Baseline**  
  Established interface configuration, routing, and connectivity validation.

- **02–03 – Adapter Modes**  
  Tested NAT vs Host-Only networking to understand isolation and routing effects.

- **04 – DHCP Reservations**  
  Implemented a DHCP reservation at the hypervisor level and verified persistence.

- **05 – VLAN Configuration**  
  Designed VLAN-based segmentation and validated Layer 2 isolation.

- **06 – Summary**  
  Consolidated architecture decisions, lessons learned, and troubleshooting insights.

All documentation is available in the `docs/` directory.

---

## Key Concepts Demonstrated

- Linux network interface configuration and validation
- DHCP reservations vs static IP configuration
- VLAN tagging and VLAN-equivalent segmentation
- Layer 2 vs Layer 3 responsibilities
- Multi-homed routing concepts
- Troubleshooting DNS, routing, and interface state
- Infrastructure decision-making based on platform limitations

---

## Notes

This lab was intentionally stopped after completing segmentation and routing
design due to hypervisor limitations. The focus was on understanding architecture,
behavior, and troubleshooting rather than forcing a specific implementation.

---

## Status

Completed – December 2025  
Future enhancements may include firewall rules, routing policies, or cloud-based
networking extensions.
