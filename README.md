# Securing Networks

## Objective
The objective of this project was to gain practice in using network monitoring tools to identify active network attacks and use additional tools to mitigate and prevent future network attacks. Virtual Machines (VM) were used to minic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned & Steps Used
- Locate and Modify the ARP Tables
  - PowerShell was used to run various commonds such as, "arp -a" to display the ARP cache, “arp -s” to add IP address in the APR table and “arp -d” to clear cache.

- Identifying Indicators of a Network Attack
  - I established VMs to simulate and perform well known and frequent attacks that could occur. These attacks include, “ICMP Flood attack,” “PING of Death,” and “Distributed Denial of Service” (DDoS) attacks.


- Using Network Security Assessment Tools
  - I established a shell environment to use tools, such as nmap and traceroute, to perform security actions crucial for securing a network. In addition, other tools were used including “OpenSSL,” to implement Transport Layer Security (TLS) protocols to help provide communication security over a network. Image 1 shows me using Wireshark to capture packets for security monitoring purposes.

![image](https://github.com/user-attachments/assets/62afed8e-d236-4440-858d-808a08dbad84)

Image 1: Wireshark

## Objective
The main objective of this project is to configure firewalls and test firewall security in a network. The purpose of this testing is to find vulnerabilities within the firewall, simulate attacks, and ensure firewall effectiveness.

- Configuring Defender Firewall-Ports
  - Firewalls can be configured in many ways to secure network traffic such as configuring the Firewall to block protocols such as TCP. Practice using the command terminal was also used to modify and proxy servers and test the capability of a Honeypot.
  - Using Firewall protocols along with commands in the command line, I was able to simulate intrusion detection attempts. *See Image 2*
 
![image](https://github.com/user-attachments/assets/fafe229f-9746-49a1-9461-0abf0d026674)

Image 2: Intrusion detection


