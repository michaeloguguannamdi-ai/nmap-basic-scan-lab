# Nmap Basic Network Scanning Lab

## Objective
Learn how to use Nmap to identify open ports and detect services
running on a local machine.

## Tools Used
- Kali Linux
- Nmap 7.99
- Python HTTP Server

## Lab Activities
1. Performed an initial scan of localhost.
2. Observed the status of the scanned ports.
3. Started a temporary Python HTTP server on port 8080.
4. Used Nmap service detection to identify the service.
5. Saved scan results for documentation.

## Commands Used

### Initial Scan
nmap 127.0.0.1

### Service Detection
nmap -sV -p 8080 127.0.0.1

## Findings
- The initial scan showed the scanned TCP ports were closed.
- A temporary HTTP server was started on port 8080.
- Nmap detected port 8080 as open.
- The service was identified as a Python HTTP server.

## Conclusion
This lab demonstrated basic port scanning and service detection
using Nmap on a local machine.
