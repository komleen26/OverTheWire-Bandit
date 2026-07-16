#Bandit level 12 to level 13:

#Commands used: ssh bandit12@bandit.labs.overthewire.org -p 2220

- mkdir /tmp/kim
- cp data.txt /tmp/kim
- cd /tmp/kim
- xxd -r data.txt > data
- file data
- mv data data.gz
- gzip -d data.gz
- mv file file.tar
- tar xf file.tar
- mv data6.bin data.bz2
- bzip2 -d data.bz2

#Command breakdown:
- `mkdir /tmp/kim` – Creates a temporary working directory.
- `cp data.txt /tmp/kim` – Copies the challenge file to the working directory.
- `cd /tmp/kim` – Moves into the working directory.
- `xxd -r` – Reverses the hexadecimal dump back into its original binary form.
- `file` – Identifies the current file type.
- `mv` – Renames the file with the correct extension before decompression.
- `gzip -d` – Decompresses Gzip-compressed files.
- `tar xf` – Extracts files from a TAR archive.
- `bzip2 -d` – Decompresses Bzip2-compressed files.
- `cat` – Displays the contents of the final text file.
