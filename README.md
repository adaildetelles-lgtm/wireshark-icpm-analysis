# Wireshark ICMP Traffic Analysis

## Objective
This project demonstrates basic network traffic analysis using Wireshark in a virtual laboratory environment.

The objective was to capture and analyze ICMP packets generated between virtual machines.

---

## Lab Environment

### Virtual Machines
- Kali Linux
- Metasploitable 2

### Tools
- Wireshark
- Ping
- VirtualBox

---

## Network Configuration

Both virtual machines were configured on the same virtual network to allow communication between hosts.

---

## Traffic Generation

ICMP traffic was generated using the ping command from Kali Linux to Metasploitable 2.

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

<img width="1366" height="643" alt="image" src="https://github.com/user-attachments/assets/74591c3d-b0d0-4b61-a053-0928f4d494d6" />


### Ping Communication

<img width="1366" height="643" alt="image" src="https://github.com/user-attachments/assets/9d66d734-abee-4557-ae4e-53549dc91dad" />


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
