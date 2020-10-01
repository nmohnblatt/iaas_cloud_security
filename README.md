# COMP0057 UCL Research in Information Security

## Literature Review: Establishing Cross-VM Communication Channels in IaaS Public Clouds

Please download `main.pdf` to read the full report.

### Abstract:
In this survey, we consider the security of Infrastructure-as-a-Service clouds. Users of these services launch virtual machines (VMs) on shared hardware. We consider what could happen if an attacker registers as a legitimate user and attempts to break isolation boundaries between VMs. We find that researchers have managed to force the co-location of two attacker VMs, and force the co-location of an attacker’s VM with that of a target. We investigate techniques that abuse the shared hardware to establish cross-VM communication channels. We find that state-of- the-art techniques allow to build covert channels robust enough to support a fully functional SSH connection.