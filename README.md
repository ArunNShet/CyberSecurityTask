# Task 1: Scan Your Local Network for Open Ports

## Objective
The goal of this task was to scan my local network using Nmap to find open ports on connected devices. This helps understand which services are running and possible security risks.

## Tools Used
- Nmap
- Command Prompt / Terminal

## What I Did
1. Installed Nmap from the official website.
2. Found my local IP range using `ipconfig` (Windows).
3. Ran this command to scan for open ports: nmap -sS 192.168.141.60
4. Noted the IP addresses and open ports found on each device.
5. Researched what services usually run on those ports.
6. Saved the scan result to a file (`task1.txt`).

## Outcome
- Learned how to use Nmap for scanning.
- Understood how to find open ports and detect exposed services in a network.
