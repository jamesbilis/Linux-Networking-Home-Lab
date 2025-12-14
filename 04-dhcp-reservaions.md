# DHCP Reservations

## DHCP Server
- VMware Workstation Pro NAT (VMnet8)

## Reservation Details
- Hostname: ubuntu-lab
- Interface: ens33
- MAC address: 00:0c:29:29:01:3f
- Reserved IP address: 192.168.240.50

## Configuration Method
The DHCP reservation was configured on the host system by editing
VMware’s `vmnetdhcp.conf` file and restarting the VMware DHCP and
NAT services.

## Verification
- Ubuntu network interface was switched to DHCP
- System was rebooted
- The same IP address (192.168.240.50) was assigned automatically

## Notes
DHCP reservations allow consistent IP addressing while keeping
configuration centralized on the DHCP server rather than the host OS.
