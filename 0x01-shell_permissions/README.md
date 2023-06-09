My name is Betty
0-iam_betty script that switches the current user to the user betty.

Who am I
1-who_am_i script that prints the effective username of the current user.

Groups
2-groups script that prints all the groups the current user is part of.

New owner
3-new_owner script that changes the owner of the file hello to the user betty.

Empty file
4-empty script that create an empty file.

Execute
5-execute scripts that adds execution permission to file 'hello'.

Multiple permissions
6-multiple_permissions script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

Everybody!
7-everybody script that adds execution permission to the owner, the group owner and the other users, to the file hello.

James Bond
8-James_Bond script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
John Doe
9-John_Doe that sets the mode of the file hello to this: ## -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

Look in the mirror
10-mirror_permissions script that sets the mode of the file hello the same as olleh’s mode.

Directories
11-directories_permissions script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

More directories
12-directory_permissions script that creates a directory called my_dir with permissions 751 in the working directory.

Change group
13-change_group script that changes the group owner to school for the file hello.

Owner and group
100-change_owner_and_group script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Symbolic links
101-symbolic_link_permissions script that changes the owner and the group owner of _hello to vincent and staff respectively:

The file _hello is in the working directory
The file _hello is a symbolic link
If only
102-if_only script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

Star wars
103-Star_Wars script that will play the StarWars IV episode in the terminal.
