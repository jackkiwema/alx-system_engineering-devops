---
Shell permissions
---
#### My name is Betty
* Create a script that switches the current user to the user betty

#### Who am I 
* A script that prints the effective username of the current user

#### Groups
* Script that prints all the groups the current user is part of

#### New owner
* Script that changes the owner of the file hello to betty

#### Empty
* Script that creates an empty file

#### Execute
* Script that execute permission to the owner of the file

#### Multiple permissions
* Script that adds execute permission to the owner and the group owner, and read permission to the other users to the file `hello`

#### Everybody!
* Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`

#### James Bond
* Script that sets the permission to the file `hello`:
	```
	Owner: no permission at all
	Group: no permission at all
	Other users: all the permissions
	```
#### John Doe
* Script that sets the mode of the file `hello` to 
	` -rwxr-x-wx 1 julien 23 Sep 20 14:25 hello`

#### Look in the mirror
* Script that sets the mode of the file hello the same as olleh's mode

#### Directories
* Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

#### More directories
* Script that creates a directory called `my_dir` with permissions 751 in the working directory

#### Change group
* Script that changes the group owner to `school` for the file `hello`
