# task6

ICMP Packet Capture with Wireshark

## Description
This repository contains the steps and results of capturing ICMP packets using Wireshark while pinging `google.com`. The capture file is saved in `.pcapng` format for further analysis.

## Prerequisites
- **Kali Linux** or any Linux distribution with Wireshark installed
- Basic command line knowledge
- Internet connection for pinging

## Steps to Capture ICMP Packets

1. **Open Wireshark**:
   - Launch Wireshark from the applications menu or run:
     ```bash
     wireshark &
     ```

2. **Select the Network Interface**:
   - Choose `eth0` (or the relevant interface) and start capturing packets.

3. **Ping Google**:
   - Open a terminal and run:
     ```bash
     ping -c 4 google.com
     ```

4. **Observe the Captured Packets**:
   - Ensure that Wireshark displays four ICMP Echo Request and four Echo Reply packets.

5. **Stop the Capture**:
   - Click the red square button in Wireshark to stop capturing.

6. **Save the Capture**:
   - Go to `File` > `Save As...`, and save the file as `ping.pcapng`.

