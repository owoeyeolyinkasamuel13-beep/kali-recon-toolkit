# Nmap Notes

## What is Nmap?
Nmap is a network scanning tool used to discover hosts, open ports, and running services on a target system.

## Basic Scan
Command used:
```bash
nmap scanme.nmap.org

What the command does?
This command scans the target host and checks for open ports and accessible services.

What I observed?
## What I observed
The first scan failed because the Kali virtual machine had no network connection. After checking VirtualBox settings, I found the network adapter was misconfigured. Once the adapter was corrected and internet access was restored, the scan completed successfully and returned open ports on the target.

What I learned?
Nmap helps identify exposed services on a system. Open ports can reveal possible entry points and help analysts understand a target’s attack surface.
