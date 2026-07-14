#Bandit level 11 to level 12:

#Commands used: ssh bandit11@bandit.labs.overthewire.org -p 2220
- cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

#Command breakdown:
- `cat data.txt` – Displays the contents of `data.txt`.
- `|` – Pipes the output of one command as the input to another.
- `tr` – Translates or replaces characters from one set to another.
- `'A-Za-z'` – Specifies all uppercase and lowercase alphabetic characters.
- `'N-ZA-Mn-za-m'` – Maps each letter using the ROT13 substitution.
