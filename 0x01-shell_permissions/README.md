# Basic Shell Script re permissions.
 
0. changes your user ID to betty

1. prints the effective userid of the current user

2. prints all the groups the current user is part of

3. changes the owner of the file hello to the user betty

4. creates an empty file called hello

5. adds execute permission to the owner of the file hello

6. adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7. adds execution permission to the owner, the group owner and the other users, to the file hello

8. Owner: no permission at all; Group: no permission at all; Other users: all the permissions

9. Write a script that sets the mode of the file to -rwxr-x-wx

10. A script that sets the mode of the file hello the same as olleh’s mode

11. A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12.  A script that creates a directory called my_dir with permissions 751 in the working directory.
13. Changes the group owner to school for the file hello. 
     * The file hello will be in the working directory.
15. Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15. changes the owner and the group owner of _hello to vincent and staff respectively.

    * The file _hello is in the working directory
    * The file _hello is a symbolic link

16.  changes the owner of the file hello to betty only if it is owned by the user guillaume.
    * The file hello will be in the working directory

17. plays the StarWars IV episode in the terminal
