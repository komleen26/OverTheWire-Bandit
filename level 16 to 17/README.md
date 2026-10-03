#Bandit level 16 to level 17:

#Commands used: ssh bandit16@bandit.labs.overthewire.org -p 2220
nmap -sV localhost -p 31000-32000
openssl s_client -connect localhost:31790

#Commands breakdown:
- nmap – Network scanning tool.
- -sV – Attempts to determine the service and version running on each open port.
- localhost – Scans the local machine.
- -p 31000-32000 – Scans ports from 31000 through 32000.

- openssl – Cryptographic toolkit.
- s_client – OpenSSL client used to establish SSL/TLS connections.
- -connect – Specifies the destination.
- localhost:31790 – Connects to the identified SSL/TLS service on port 31790.
