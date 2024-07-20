<h1>Laboratorio 3</h1>

Perform NetBIOS enumeration
Perform NetBIOS enumeration using Windows command-line utilities
Perform NetBIOS enumeration using NetBIOS Enumerator
Perform NetBIOS enumeration using an NSE Script
Perform SNMP enumeration

Perform SNMP enumeration using snmp-check
Perform SNMP enumeration using SoftPerfect Network Scanner
Perform SNMP enumeration using SnmpWalk
Perform SNMP enumeration using Nmap
Perform LDAP enumeration

Perform LDAP enumeration using Active Directory Explorer (AD Explorer)
Perform LDAP enumeration using Python and Nmap
Perform LDAP enumeration using ldapsearch
Perform NFS enumeration

Perform NFS enumeration using RPCScan and SuperEnum
Perform DNS enumeration

Perform DNS enumeration using zone transfer
Perform DNS enumeration using DNSSEC zone walking
Perform DNS enumeration using Nmap
Perform SMTP Enumeration

Perform SMTP enumeration using Nmap
Perform RPC, SMB, and FTP enumeration

Perform SMB and RPC enumeration using NetScanTools Pro
Perform RPC, SMB, and FTP enumeration using Nmap
Perform enumeration using various enumeration tools

Enumerate information using Global Network Inventory
Enumerate network resources using Advanced IP Scanner
Enumerate information from Windows and Samba hosts using Enum4linux


A NetBIOS name is a unique computer name assigned to Windows systems, comprising a 16-character ASCII string that identifies the network device over TCP/IP.

########################
ntbstat -a
""      -c
net use
Netbios Enumerator

nmap -sV -v --script nbstat.nse
type nmap -sU -p 137 --script nbstat.nse
nmap -sU -p 161
snmp-check

Network Scanner

########################

snmpwalk -v1 -c public
nmap -sU -p 161 --script=snmp-sysdescr
nmap -sU -p 161 --script=snmp-interfaces