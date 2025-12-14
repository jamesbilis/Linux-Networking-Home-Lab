# Adapter Modes Test

## NAT (VMnet8)
- Adapter type: NAT
- IP address range: 192.168.240.0/24
- Default gateway present: Yes
- Internet access: Yes
- Ping 8.8.8.8: Success
- Use case:
  Provides internet access to the VM through the host using NAT.

## Host-Only (VMnet1)
- Adapter type: Host-Only
- IP address assigned: Yes
- Default gateway present: No
- Internet access: No
- Ping 8.8.8.8: Failed
- Use case:
  Isolated network used for secure labs and testing without internet access.

## Summary
Switching between NAT and Host-Only networking changes whether the VM has
a default route and internet access. Host-Only mode isolates the VM from
external networks, while NAT allows outbound connectivity.
