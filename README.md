# day-09
Network Scanning Basics (Nmap)
# Day 9 – Network Scanning Basics (Nmap)

## 1. Open Ports Observed
The scan showed some open ports on my system such as 22 (SSH), 80 (HTTP), and 631 (IPP). These ports represent services running on the system.

## 2. Service Detection Results
Using the -sV option, Nmap detected service names and versions running on the open ports. For example, SSH service and HTTP server versions were identified.

## 3. Why Open Ports Can Increase Security Risks
Open ports allow services to communicate with the network. If these services have vulnerabilities, attackers can exploit them to gain unauthorized access to the system.

## 4. New Concept Learned
I learned how Nmap can scan systems to detect open ports and running services, which is useful for both attackers and security professionals during reconnaissance.
