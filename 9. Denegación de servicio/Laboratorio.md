Perform a DoS attack by continuously sending a large number of SYN packets
Perform a DoS attack (SYN Flooding, Ping of Death (PoD), and UDP application layer flood) on a target host
Perform a DDoS attack
Detect and analyze DoS attack traffic
Detect and protect against a DDoS attack


Lab 1: Perform DoS and DDoS Attacks using Various Techniques


In general, the following are categories of DoS/DDoS attack vectors:

Volumetric Attacks: Consume the bandwidth of the target network or service

Attack techniques:

UDP flood attack
ICMP flood attack
Ping of Death and smurf attack
Pulse wave and zero-day attack
Protocol Attacks: Consume resources like connection state tables present in the network infrastructure components such as load-balancers, firewalls, and application servers

SYN flood attack
Fragmentation attack
Spoofed session flood attack
ACK flood attack
Application Layer Attacks: Consume application resources or services, thereby making them unavailable to other legitimate users

Attack techniques:

HTTP GET/POST attack
Slowloris attack
UDP application layer flood attack
DDoS extortion attack


Tasks 1: Perform a DoS Attack (SYN Flooding) on a Target Host using Metasploit

nmap -p 21

msfconsole + wireshark

Task 2: Perform a DoS Attack on a Target Host using hping3

hping3 -S (Target IP Address) -a (Spoofable IP Address) -p 22 --flood
hping3 -d 65538 -S -p 21 --flood

CharGEN (Port 19)
SNMPv2 (Port 161)
QOTD (Port 17)
RPC (Port 135)
SSDP (Port 1900)
CLDAP (Port 389)
TFTP (Port 69)
NetBIOS (Port 137,138,139)
NTP (Port 123)
Quake Network Protocol (Port 26000)
VoIP (Port 5060)

Task 3: Perform a DoS Attack using Raven-storm

rst


Task 4: Perform a DDoS Attack using HOIC

Task 5: Perform a DDoS Attack using LOIC

Lab 2: Detect and Protect Against DoS and DDoS Attacks

Task 1: Detect and Protect Against DDoS Attacks using Anti DDoS Guardian


 
