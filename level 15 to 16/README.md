#Bandit level 15 to level 16:

#Commands used: ssh bandit15@bandit.labs.overthewire.org -p 2220
- openssl s_client -connect localhost:30001

#Commands breakdown:
- openssl – A toolkit for cryptographic operations and secure communication.
- s_client – OpenSSL's command-line client for establishing an SSL/TLS connection to a server.
- -connect – Specifies the destination host and port.
- localhost – Refers to the current machine.
- 30001 – The port on which the secure service is listening.
