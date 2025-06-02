# Wireshark Packet Capture Report

**Name**: Subhamita Santra  
**Date**: June 2025  
**Capture File**: `network_capture.pcap`

## Summary

Captured live traffic for 1 minute while browsing websites and using the `ping` command.

## Protocols Identified

| Protocol | Description            | Example Packet Info                            |
|----------|------------------------|------------------------------------------------|
| HTTP     | Website data transfer  | GET /index.html HTTP/1.1 to example.com        |
| DNS      | Domain lookup          | Query A google.com                             |
| ICMP     | Ping traffic           | Echo request/reply from 8.8.8.8                |

## Observations

- DNS requests happened before each website visit.
- HTTP traffic showed site content requests.
- ICMP packets were generated using `ping`.
