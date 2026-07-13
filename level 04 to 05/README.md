#Bandit level 4 to level 5:

#Commands used: ssh bandit4@bandit.labs.overthewire.org -p 2220

#Command breakdown:
- `ls` – Lists the files and directories in the current directory.
- `cd inhere` – Changes the current working directory to `inhere`.
- `file ./*` – Determines the type of every file in the current directory.
- `cat -- "-file07"` – Displays the contents of `-file07`.
- `--` – Marks the end of command options so that `-file07` is treated as a filename instead of an option.
