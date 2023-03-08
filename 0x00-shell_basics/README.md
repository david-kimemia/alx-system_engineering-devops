# Shell, Basics
### Task 0: Where am I? 
- File: `0-current_working_directory`  
A script that prints the absolute path name of the current working directory. 

### Task 1: What’s in there? 
- File: `1-listit`
Displays the contents list of your current directory.

### Task 2: There is no place like home 
- File: `2-bring_me_home`
A script that changes the working directory to the user’s home directory.

### Task 3: The long format 
- File: `3-listfiles`
Displays current directory contents in a long format

### Task 4: Hidden files 
- File: `4-listmorefiles`
Displays current directory contents, including hidden files (starting with `.`). Use the long format.

### Task 5: I love numbers 
- File: `5-listfilesdigitonly`
Displays current directory contents.
    > Long format
    > with user and group IDs displayed numerically
    > And hidden files (starting with .)

### Task 6: Welcome
- File: `6-firstdirectory`
Creates a script that creates a directory named `my_first_directory` in the `/tmp/`directory.

### Task 7: Betty in my first directory 
- File: `7-movethatfile`
Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

### Task 8: Bye bye Betty
- File: `8-firstdelete`
Deletes the file `betty` from `/tmp/my_first_directory `.

### Task 9: Bye bye My first directory
- File: `9-firstdirdeletion`
Deletes the directory `my_first_directory` that is in the `/tmp` directory.

### Task 10: Back to the future 
- File: `10-back`
A script that changes the working directory to the previous one.

### Task 11: Lists 
- File: `11-lists`
A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

### Task 12: File type
- File: `12-file_type`
A script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script

### Task 13: We are symbols, and inhabit symbols
- File: `13-symbolic_link`
Creates a symbolic link to `/bin/ls`, named `__ls__`. Where the symbolic link should be created in the current working directory. 

### Task 14: Copy HTML files 
- File: `14-copy_html`
A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. 
    >Considering that all HTML files have the extension `.html`
