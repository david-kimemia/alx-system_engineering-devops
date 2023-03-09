# 0x01. Shell, permissions
### Task 0: My name is Betty  
- File: `0-iam_betty`  
A script that switches the current user to the user `betty` 

### Task 1: Who am I  
- File: `1-who_am_i`
a script that prints the effective username of the current user.

### Task 2: Groups 
- File: `2-groups`
A script that prints all the groups the current user is part of.

### Task 3: New owner  
- File: `3-new_owner`
A script that changes the owner of the file `hello` to the user `betty`

### Task 4: Empty! 
- File: `4-empty`
A script that creates an empty file called `hello`.

### Task 5: Execute 
- File: `5-execute`
A script that adds execute permission to the owner of the file `hello`.

### Task 6: Multiple permissions 
- File: `6-multiple_permissions`
A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

### Task 7: Everybody!  
- File: `7-everybody`
a script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.

### Task 8: James Bond 
- File: `8-James_Bond`
A script that sets the permission to the file `hello` as follows:

    >Owner: no permission at all
    >Group: no permission at all
    >Other users: all the permissions

### Task 9: John Doe 
- File: `9-John_Doe`
A script that sets the mode of the file hello to this:
```
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```

### Task 10: Look in the mirror 
- File: `10-mirror_permissions`
A script that sets the mode of the file `hello` the same as `olleh’s` mode.

### Task 11: Directories  
- File: `11-directories_permissions`
A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

### Task 12: More directories 
- File: `12-directory_permissions`
A script that creates a directory called `my_dir` with permissions 751 in the working directory.

### Task 13: Change group 
- File: `13-change_group`
A script that changes the group owner to `school` for the file `hello`.

### Task 14: Owner and group  
- File: `100-change_owner_and_group`
A script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.
