#Bandit level 6 to level 7:

#Commands used: ssh bandit6@bandit.labs.overthewire.org -p 2220
- find / -user bandit7 -group bandit6 -size 33c
- cat /var/lib/dpkg/info/bandit7.password


#Command breakdown:
- `find /` – Starts searching from the root (`/`) directory.
- `-user bandit7` – Searches for files owned by the user `bandit7`.
- `-group bandit6` – Restricts the search to files belonging to the group `bandit6`.
- `-size 33c` – Finds files that are exactly **33 bytes** in size.
- `2>/dev/null` – Redirects permission error messages to `/dev/null`, hiding unnecessary output.
- `cat` – Displays the contents of the file.
