# Day 03 — TCP vs UDP and Common Ports

## What is TCP?
TCP is a reliable protocol that ensures data is delivered correctly.
It uses handshakes and confirmations.

Examples: HTTP, HTTPS, FTP, SSH

## What is UDP?
UDP is a fast protocol that does not guarantee delivery.
It is used when speed is more important than accuracy.

Examples: DNS, VoIP, Streaming

## Key Differences

| Feature | TCP | UDP |
|---------|-----|-----|
| Connection | Yes | No |
| Reliable | Yes | No |
| Speed | Slower | Faster |

## Common Ports

| Port | Service |
|------|----------|
| 22 | SSH |
| 21 | FTP |
| 25 | SMTP |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 3389 | RDP |
| 445 | SMB |

## Why this matters in SOC
- Brute force attacks often target SSH (22) and RDP (3389)
- Phishing emails use SMTP (25)
- Malware uses suspicious ports

## Learning Link
https://www.youtube.com/watch?v=H7-NRoqKZ0U

## My Notes
Knowing ports helps me understand network alerts quickly.
