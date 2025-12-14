# Phase 3 – Network Adapter Modes

## Goal
Understand how different VMware network adapter modes affect
connectivity, isolation, and routing behavior.

## Adapter Modes Tested
- NAT
- Host-Only

## Observations
- NAT mode provides internet access while keeping the VM isolated
  behind the host’s virtual router.
- Host-Only mode isolates the VM from the internet and external
  networks, allowing only host-to-VM communication.
- Changing adapter modes directly impacts IP assignment, routing,
  and DNS resolution.

## Decision
NAT mode was selected for the lab to allow internet access while
still enabling controlled experimentation with IP addressing,
DHCP reservations, and network segmentation.

## Key Takeaway
Understanding adapter modes is critical before implementing
advanced networking concepts such as VLANs and routing.

