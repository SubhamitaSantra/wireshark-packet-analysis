# Network Packet Capture with Wireshark

## Objective
Capture live network traffic and identify basic protocols using Wireshark on macOS.

## Tools
- Wireshark (macOS ARM)
- Terminal (for ping)

## Steps
1. Installed Wireshark and selected active network interface.
2. Captured live packets while:
   - Visiting http://example.com
   - Pinging google.com
   - Browsing other websites
3. Stopped capture after 1 minute and saved as `.pcap`.

## Protocols Identified
- **DNS** – Domain resolution (e.g., A google.com)
- **ICMP** – Ping traffic (echo request/reply)
- **TCP** – Transport layer (SYN, ACK packets)
- **HTTP** – Web requests (GET from example.com)

## Files
- `network-capture.pcap` – Packet capture file
- `README.md` – This report

## Outcome
Basic hands-on experience with network protocols and packet analysis.
