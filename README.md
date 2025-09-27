# SYN Flood Attack Dataset for WLAN Intrusion Detection

## Overview
This dataset contains real-world network traffic captured from a Raspberry Pi 5 configured as a WLAN access point under SYN flood attack conditions. It is designed for training and evaluating machine learning-based intrusion detection systems on resource-constrained edge devices.

## Dataset Description

### Experimental Setup
- **Hardware:** Raspberry Pi 5 (8GB RAM, ARM Cortex-A76 quad-core CPU @ 2.4GHz)
- **Role:** WLAN Access Point (hostapd + dnsmasq)
- **Network:** WPA2/WPA3 secured wireless network
- **Capture Tool:** tcpdump with optimized filters
- **Environment:** Controlled lab setup with attacker, victim server, and benign clients

### Dataset Characteristics
- **Traffic Types:** Malicious SYN flood attacks + Benign background traffic
- **Features:** Network traffic metrics including:
  - Packet rates (SYN, ACK, total packets)
  - Protocol statistics (TCP flags, connection states)
  - Connection metrics (SYN/ACK ratios, flow statistics)
- **Labels:** Binary classification
  - `0` = Benign traffic
  - `1` = Malicious (SYN flood attack)
- **Format:** CSV

### Use Cases
- Intrusion detection system development for edge devices
- WLAN security research
- Benchmark for lightweight ML models on Raspberry Pi
- Real-time attack detection in resource-constrained environments

## Access
 **Download Dataset:** [OneDrive Link](https://unhnewhaven-my.sharepoint.com/:f:/g/personal/sbrah2_unh_newhaven_edu/EmJ_T_3QkLdMuFV3jKzT_nUBn4yhAO3a8MT_5gdz7q_Wxg?e=zPacaw)

## Citation
If you use this dataset in your research, please cite:
