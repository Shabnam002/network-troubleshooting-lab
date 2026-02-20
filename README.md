# Basic Network Troubleshooting Lab - Kali Linux VM
Basic network troubleshooting lab performed using Kali Linux in a virtual environment

# Overview 
This project demonstrates a hands-on network troubleshooting exercise performed in a virtual lab using Kali Linux. The objective was to simulate real IT support scenarios and verify connectivity from the local network to the internet, including DNS resolution.

# Objectives
Verify network configuration and connectivity 
Test communication with the gateway 
Confirm internet accessibility 
Validate DNS resolution 
Practice structured troubleshooting methodology

# Environment
Kali Linux (Virtual Machine)
VirtualBox NAT Networking 
Terminal-based networking tools

# Troubleshooting Stepd
1. Network Configuration Check
   Verified that the system had a valid IP address and active interface
`ip a`

2. Gateway Connectivity Test
   Confirmed communication with the gateway
   `ping -c 4 10.0.2.15`

3. Internet Connectivity Test
   Tested external connectivity using public DNS servers
   `ping -c 4 1.1.1.1`
   `ping -c 4 9.9.9.9`

4. DNS Resolution Test
   Verified domain name resolution
   `ping -c 4 google.com`
   `nslookup google.com`

# Results
Valid IP address obtained 
Gateway reachable 
Internet connectivity confirmed 
DNS functioning correctly
No connectivity issues detected

# Conclusion
The lab provided practical experience in diagnosing network connectivity issues using a systematic approach.The exercise reflects foundational skills required for entry-level IT Support and NOC roles.

# Evidence
Screenshots of each step are included in this repository.
     
   
