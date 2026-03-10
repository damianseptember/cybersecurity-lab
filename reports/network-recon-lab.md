# Network Reconnaissance Lab Notes

## Objective
Learn how to scan a target machine and identify open ports using Kali Linux.

## Lab Environment
Host Machine: Windows Desktop  
Attacker Machine: Kali Linux VM  
Target Machine: Ubuntu VM  
Hypervisor: VirtualBox

## Commands Used

Check IP address of target machine

ip a

Basic port scan

nmap -sS <target-ip>

Service version detection

nmap -sV <target-ip>

## What I Learned
- How machines communicate on the same network
- How to identify open ports
- How to identify running services
- How attackers perform reconnaissance

## Next Steps
## Scan Results

Target IP: 192.168.220.3

The Kali Linux machine performed several Nmap reconnaissance scans against the Ubuntu target machine.

Commands executed:

nmap -sS 192.168.220.3  
nmap -sV 192.168.220.3  
nmap -A 192.168.220.3  

Results:

- Host was successfully discovered on the network.
- All 1000 scanned TCP ports were closed.
- No active services were detected.
- Network distance: 1 hop.

This confirms successful connectivity between the attacker machine (Kali Linux) and the target machine (Ubuntu) within the virtual lab environment.
- Practice vulnerability scanning
- Learn web server scanning
