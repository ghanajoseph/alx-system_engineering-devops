**README FOR 0x01-shell_permissions PROJECT**

This Project consist of several tasks:

Task 0 - My Name is Betty [0-iam_betty]
       	 Create a script that switches the current user to the user betty.
	 *	You should use exactly 8 characters for your command (+1 character for the new line)
	 *	You can assume that the user betty will exist when we will run your script

Task 1 - who am I [1-who_am_i]
       	 Write a script that prints the effective username of the current user.

Task 2 - Groups [2-groups]
       	 Write a script that prints all the groups the current user is part of.

Task 3 - New owner [3-new_owner]
       	 Write a script that changes the owner of the file hello to the user betty.

Task 4 - Empty! [4-empty]
       	 Write a script that creates an empty file called hello.

Task 5 - Execute [5-execute]
       	 Write a script that adds execute permission to the owner of the file hello.
	 *     The file hello will be in the working directory

Task 6 - Multiple permissions [6-multiple_permissions]
       	 Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
	 *     The file hello will be in the working directory

Task 7 - Everybody! [7-everybody]
       	 Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
	 *     The file hello will be in the working directory
	 *     You are not allowed to use commas for this script

Task 8 - James Bond [8-James_Bond]
       	 Write a script that sets the permission to the file hello as follows:
	 *     Owner: no permission at all
	 *     Group: no permission at all
	 *     Other users: all the permissions
      	 The file hello will be in the working directory You are not allowed to use commas for this script

Task 9 - John Doe [9-John_Doe]
       	 Write a script that sets the mode of the file hello to this:
	       -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
	 *     The file hello will be in the working directory
	 *     You are not allowed to use commas for this script

Task 10 - Look in the mirror [10-mirror_permissions]
     	  Write a script that sets the mode of the file hello the same as olleh’s mode.
	  *	The file hello will be in the working directory
	  *	The file olleh will be in the working directory

Task 11 - Directories [11-directories_permissions]
     	  Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
	  Regular files should not be changed.

Task 12 - More directories [12-directory_permissions]
     	  Create a script that creates a directory called my_dir with permissions 751 in the working directory.

Task 13 - change Group [13-change_group]
     	  Write a script that changes the group owner to school for the file hello
	  *	The file hello will be in the working directory

**ADVANCED TASKS**
**-----------------------------**

Task 14 - Owner and group [100-change_owner_and_group]
     	  Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Task 15 - Symbolic links [101-symbolic_link_permissions]
     	  Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
	  *	The file _hello is in the working directory
	  *	The file _hello is a symbolic link

Task 16 - If only [102-if_only]
     	  Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
	  *	The file hello will be in the working directory

Task 17 - Star Wars [103-Star_Wars]
     	  Write a script that will play the StarWars IV episode in the terminal.