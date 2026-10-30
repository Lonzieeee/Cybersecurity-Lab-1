# Cybersecurity Lab 1 – Week 1

## Project Overview

This repository documents the setup of a cybersecurity testing lab using Oracle VirtualBox and Kali Linux.

The lab provides an isolated virtual environment for learning and practising cybersecurity concepts.

## Lab Environment

- **Virtualisation Platform:** Oracle VirtualBox
- **Attacking Machine:** Kali Linux
- **Network Type:** NAT Network
- **Network Name:** CyberLab-NAT
- **Network Subnet:** 10.0.0.0/24
- **Kali Linux IP Address:** 10.0.0.2/24
- **Default Gateway:** 10.0.0.1
- **DNS Server:** 8.8.8.8

## Configuration and Implementation

The following tasks were completed:

1. Installed Oracle VirtualBox.
2. Created a NAT Network named `CyberLab-NAT` using the subnet `10.0.0.0/24`.
3. Installed Kali Linux as the attacking machine.
4. Configured Kali Linux with the static IP address `10.0.0.2/24`.
5. Configured network connectivity and verified internet access.
6. Tested connectivity using ping commands.
7. Enabled bidirectional shared clipboard and drag-and-drop.
8. Configured shared folders between the host and Kali Linux virtual machine.
9. Created a virtual machine snapshot named `Kali-Week1-Setup`.

## Network Connectivity Tests

The following tests were performed successfully:

- `ping -c 4 8.8.8.8` – Verified internet connectivity.
- `ping -c 4 google.com` – Verified DNS resolution and internet connectivity.

Both tests completed successfully with no packet loss at the time of testing.

## Repository Structure

```text
Cybersecurity-Lab-1/
├── README.md
├── documentation/
└── screenshots/
```

## Evidence

Screenshots showing the virtual network configuration, Kali Linux IP address, connectivity tests, shared folder settings and virtual machine snapshot will be provided in the `screenshots` directory.

## Conclusion

The Week 1 cybersecurity lab environment was successfully configured using VirtualBox and Kali Linux. The Kali Linux virtual machine has the required static IP address, network connectivity and shared-folder configuration.

