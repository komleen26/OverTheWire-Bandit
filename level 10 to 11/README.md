#Bandit level 10 to level 11:

#Commands used: ssh bandit10@bandit.labs.overthewire.org -p 2220 
strings data.txt | base64 -d

#Command breakdown:
- `strings` – Extracts printable (human-readable) strings from a file.
- `data.txt` – The file containing the Base64-encoded password.
- `|` – Pipes the output of one command as the input to another.
- `base64 -d` – Decodes Base64-encoded data into its original form.
