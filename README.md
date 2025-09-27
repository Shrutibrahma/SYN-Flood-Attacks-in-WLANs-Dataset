# SYN Flood Attack Dataset - Raspberry Pi WLAN

This dataset contains network traffic captured from a Raspberry Pi 5 configured as a WLAN access point during SYN flood attacks. The data includes both malicious traffic from an attacker machine and benign traffic from legitimate client devices in a controlled lab environment.

**Features:** Network traffic features including packet rates, protocol statistics, and connection metrics extracted from TCP traffic captured using tcpdump.

**Labels:** Binary classification (0 = benign, 1 = malicious) based on source IP behavior during SYN flood attacks.

**Use Case:** Training and evaluating intrusion detection systems for edge devices in WLAN environments.
