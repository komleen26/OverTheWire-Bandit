# Bandit Level 7 → Level 8

## Commands Used

ssh bandit7@bandit.labs.overthewire.org -p 2220
grep "millionth" data.txt

## Command Breakdown

- `ssh` – Establishes a secure connection to a remote Linux server.
- `bandit7` – Username for the current Bandit level.
- `@` – Separates the username from the remote host.
- `bandit.labs.overthewire.org` – The hostname of the Bandit server.
- `-p 2220` – Specifies the custom SSH port used by the Bandit server.
- `grep` – Searches a file for lines that match a specified pattern.
- `"millionth"` – The keyword used to locate the required line.
- `data.txt` – The file being searched.
