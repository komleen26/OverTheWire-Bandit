#Bandit level 5 to level 6:

#Commands used: ssh bandit5@bandit.labs.overthewire.org -p 2220

#Command breakdown:
- `ls` – Lists the files and directories in the current directory.
- `file ./*` – Displays the type of each item in the current directory.
- `ls maybehere00` – Lists the contents of the `maybehere00` directory to inspect its files.
- `find . -type f -size 1033c` – Searches recursively for regular files that are exactly **1033 bytes** in size.
- `cd maybehere07` – Changes into the directory containing the matching file.
- `cat -- "-file2"` – Displays the contents of the file named `-file2`.
- `--` – Marks the end of command options, ensuring `-file2` is treated as a filename rather than an option.
