# Wireshark ICMP Traffic Analysis

## Objective
This project demonstrates basic network traffic analysis using Wireshark in a virtual laboratory environment.

The objective was to capture and analyze ICMP packets generated between virtual machines.

---

## Lab Environment

### Virtual Machines
- Kali Linux
- Ubuntu Linux

### Tools
- Wireshark
- Ping
- VirtualBox

---

## Network Configuration

Both virtual machines were configured on the same virtual network to allow communication between hosts.

---

## Traffic Generation

ICMP traffic was generated using the ping command from Kali Linux to Ubuntu.

Example:

```bash
ping <target-ip>
```

---

## Wireshark Analysis

The following filter was used:

```txt
icmp
```

The capture showed:
- ICMP Echo Request packets
- ICMP Echo Reply packets
- Successful communication between hosts

---

## Security Analysis

ICMP traffic is commonly used for:
- Connectivity testing
- Network diagnostics
- Host discovery

Although ICMP is legitimate traffic, abnormal ICMP activity may indicate:
- Network scanning
- Reconnaissance activity
- ICMP flood attacks

---

## Evidence

### ICMP Packet Capture
(Add screenshot here)

### Ping Communication
(Add screenshot here)

---

## Skills Practiced

- Network packet analysis
- Wireshark filtering
- ICMP protocol analysis
- Virtual lab configuration
- Basic network troubleshooting

---

## Lessons Learned

This lab helped develop foundational skills in packet analysis and network visibility using Wireshark.
