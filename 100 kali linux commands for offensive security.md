# *100 Kali Linux Commands for Penetration Testing.* 
### Reconnaissance & Information Gathering
1. `whois` - Retrieve domain registration and ownership information.
2. `dig` - Query DNS records and name servers.
3. `host` - Perform DNS lookups for domains and hosts.
4. `nslookup` - Query DNS servers for domain information.
5. `dnsenum` - Enumerate DNS records and domain information.
6. `dnsrecon` - Perform DNS reconnaissance and enumeration.
7. `theHarvester` - Gather publicly available information about domains and organizations.
8. `recon-ng` - Perform modular web-based reconnaissance.
9. `amass` - Discover domains, subdomains, and other attack-surface information.
10. `whatweb` - Identify technologies and software used by websites.
### Network Discovery & Scanning
11. `nmap` - Discover hosts, open ports, services, and operating system information.
12. `masscan` - Perform high-speed port scanning on authorized networks.
13. `rustscan` - Quickly identify open ports for further enumeration.
14. `unicornscan` - Perform asynchronous TCP and UDP network scanning.
15. `ping` - Test network connectivity using ICMP.
16. `traceroute` - Trace the network path to a destination.
17. `ip` - Display and manage network interfaces, addresses, and routes.
18. `ss` - Display network sockets and active connections.
19. `arp` - Display or modify the ARP cache.
20. `netdiscover` - Discover hosts on local networks using ARP.
### Network Service Enumeration
21. `nc` - Create network connections for testing and troubleshooting.
22. `ncat` - Establish network connections and transfer data.
23. `smbclient` - Access and interact with SMB/CIFS shares.
24. `smbmap` - Enumerate SMB shares and their permissions.
25. `rpcclient` - Interact with RPC services for authorized enumeration.
26. `enum4linux` - Gather information from Windows and Samba systems.
27. `nbtscan` - Scan systems for NetBIOS information.
28. `ldapsearch` - Query LDAP directories.
29. `snmpwalk` - Query SNMP-enabled devices for management information.
30. `onesixtyone` - Identify SNMP services using community-string testing.
### Web Reconnaissance & Enumeration
31. `curl` - Transfer data to and from web servers.
32. `wget` - Retrieve files and resources from web servers.
33. `httpx` - Probe HTTP services and identify web technologies.
34. `nikto` - Scan web servers for known vulnerabilities and configuration issues.
35. `gobuster` - Discover directories, files, DNS subdomains, and virtual hosts.
36. `ffuf` - Perform web fuzzing for directories, files, parameters, and virtual hosts.
37. `feroxbuster` - Discover web resources through recursive content enumeration.
38. `dirsearch` - Enumerate web directories and files.
39. `wapiti` - Scan web applications for common vulnerabilities.
40. `wafw00f - Identify and fingerprint web application firewalls.
### Vulnerability Assessment
41. `nuclei` - Scan targets for known vulnerabilities and security issues using templates.
42. `searchsploit` - Search the Exploit Database for publicly documented exploits.
43. `openvas` - Perform vulnerability assessments using the OpenVAS framework.
44. `lynis` - Audit Linux systems for security configuration issues.
45. `chkrootkit` - Check Linux systems for indicators of known rootkits.
46. `rkhunter` - Scan systems for possible rootkits and other suspicious modifications.
47. `unix-privesc-check` - Check Unix systems for potential privilege-escalation weaknesses.
48. `enum4linux-ng` - Perform detailed enumeration of Windows and Samba environments.
49. `legion` - Provide a graphical interface for network discovery and service enumeration.
50. `spiderfoot` - Automate OSINT collection from numerous public sources.
### Password & Credential Testing
51. `john` - Audit password strength by testing password hashes.
52. `hashcat` - Perform password recovery and auditing against captured hashes.
53. `hydra` - Perform authorized login and credential-strength testing against network services.
54. `medusa` - Perform parallelized network authentication auditing.
55. `ncrack` - Perform network authentication auditing.
56. `cewl` - Generate custom wordlists from words found on websites.
57. `crunch` - Generate custom wordlists from specified character sets and patterns.
58. `hashid` - Identify possible hash algorithms from hash strings.
59. `hash-identifier` - Identify possible hash types.
60. `unshadow` - Combine Unix password and shadow files for password auditing.
### Web Application Security Testing
61. `sqlmap` - Test web applications for SQL injection vulnerabilities.
62. `commix` - Test web applications for command-injection vulnerabilities.
63. `dalfox` - Analyze web parameters for potential XSS vulnerabilities.
64. `xsser` - Test web applications for cross-site scripting vulnerabilities.
65. `wpscan` - Assess WordPress installations for known vulnerabilities.
66. `joomscan` - Perform a security assessment of joomla installations.
67. `droopescan` - Scan supported CMS platforms for security-related information.
68. `davtest` - Test web servers for supported HTTP methods and file-upload capabilities.
69. `cadaver` - Interact with WebDAV-enabled servers.
70. `burpsuite` - Analyze and test web application traffic through an intercepting proxy.
### Exploitation & Frameworks
71. `msfconsole` - Access the Metasploit Framework's command-line interface.
72. `msfvenom` - Generate and transform Metasploit payloads for authorized testing.
73. `msfdb` - Manage the Metasploit database.
74. `setoolkit` - Perform authorized social-engineering security assessments.
75. `beef-xss` - Assess browser-side security using the BeEF framework.
76. `exploitdb` - Work with local Exploit Database resources when available.
77. `veil` - Generate payloads for authorized security testing and research.
78. `empire` - Provide a post-exploitation framework for authorized assessments.
79. `powershell-empire` - Access the Empire post-exploitation framework.
80. `metasploit-framework` - Access the installed Metasploit Framework components and resources.
### Wireless Security Testing
81. `airmon-ng` - Manage wireless interfaces for monitor mode testing.
82. `airodump-ng` - Capture and analyze wireless network traffic.
83. `aireplay-ng` - Perform authorized wireless packet-injection testing.
84. `aircrack-ng` - Analyze captured wireless traffic for security auditing.
85. `airdecap-ng` - Decrypt captured wireless traffic when the required credentials are available.
86. `airbase-ng` - Create virtual wireless access points for authorized testing.
87. `airolib-ng` - Manage databases used by the Aircrack-ng suite.
88. `wash` - Identify WPS-enabled wireless access points.
89. `reaver` - Audit WPS security on authorized wireless networks.
90. `bully` - Perform WPS security auditing on supported wireless networks.
### Traffic Analysis, File Analysis & Utilities
91. `tcpdump` - Capture and inspect network packets from the command line.
92. `tshark` - Capture and analyze network traffic from the command line.
93. `wireshark` - Capture and analyze network traffic using a graphical interface.
94. `ettercap` - Perform network traffic analysis and authorized interception testing.
95. `bettercap` - Perform network reconnaissance and security testing.
96. `macchanger` - Display or change a network interface's MAC address.
97. `openssl` - Inspect certificates and perform cryptographic operations.
98. `strings` - Extract readable strings from binary and other files.
99. `xxd` - Create hexadecimal dumps or convert hexadecimal data.
100. `sha256sum` - Calculate or verify SHA-256 file checksums.

***These commands should only be used on systems you own or have explicit permission to test. Always use Kali Linux and its tools responsibly and ethically, and follow all applicable laws and security guidelines.***
