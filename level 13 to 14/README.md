#Bandit level 13 to level 14:

#Commands used: ssh bandit13@bandit.labs.overthewire.org -p 2220
- scp -P 2220 bandit13@bandit.labs.overthewire.org:/home/bandit13/sshkey.private .
- ssh -p 2220 -i sshkey.private bandit14@bandit.labs.overthewire.org

#Commands breakdown:
1. Copy the private SSH key
- scp -P 2220 bandit13@bandit.labs.overthewire.org:/home/bandit13/sshkey.private .
- scp – Securely copies files between systems over SSH.
- -P 2220 – Specifies the SSH port used by the Bandit server.
- bandit13@bandit.labs.overthewire.org – Specifies the remote username and server.
- /home/bandit13/sshkey.private – Path of the private SSH key on the remote server.
-  Copies the file into the current local directory.

2. Log in using the private key
- ssh -p 2220 -i sshkey.private bandit14@bandit.labs.overthewire.org
- ssh – Establishes a secure remote connection.
- -p 2220 – Specifies the custom SSH port.
- -i sshkey.private – Specifies the private SSH key to use for authentication.
- bandit14@bandit.labs.overthewire.org – Connects to the server as user bandit14.

3. Read the password
- Once successfully logged in as bandit14, I used:
- cat /etc/bandit_pass/bandit14


