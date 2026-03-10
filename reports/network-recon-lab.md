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
- Practice vulnerability scanning
- Learn web server scanning
