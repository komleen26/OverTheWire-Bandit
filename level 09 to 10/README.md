#Bandit level 9 to level 10:

#Commands used: ssh bandit9@bandit.labs.overthewire.org -p 2220
strings data.txt | grep ==

#Command breakdown:
- `ssh` – Establishes a secure connection to the remote Bandit server.
- `bandit9` – Username for the current Bandit level.
- `@` – Separates the username from the remote host.
- `bandit.labs.overthewire.org` – Hostname of the Bandit server.
- `-p 2220` – Specifies the custom SSH port used by the Bandit server.
- `strings` – Extracts printable (human-readable) strings from a binary file.
- `data.txt` – The file containing the hidden password.
- `|` – Pipes the output of one command as the input to another.
- `grep "=="` – Searches for lines containing the pattern `==`, which identifies the password.
