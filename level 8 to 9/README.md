#Bandit level 8 to level 9:

#Commands used: ssh bandit8@bandit.labs.overthewire.org -p 2220
- sort data.txt | uniq -u

#Command breakdown:
- `sort data.txt` – Sorts all lines in the file alphabetically. This is necessary because the `uniq` command only detects duplicate lines that are adjacent.
- `|` – Pipes the output of one command as the input to another.
- `uniq -u` – Displays only the lines that appear exactly once.
