cu betty script will switch the current user to betty user if the use is already created
whoami command print the effective username of the surrent user
groups command will print all the groups that the current user is part of
chown [user] [filename] is a command to change the owner of a file
touch file_name is used to creat an empty file_name file
By using the command chmod with three digit values and file name, we can change the permisson
Chmod with threedigit vale can change the giving file permission
we have to use u+r or w or x to add permission at excution time
u meand owner, g means group and o meand other user
Is there and difference between ugo+x and u+x,g+x,o+x?
For a file rwxr-x-wx means 753
chmod --reference=[file_1] [file_2]  this will copy the permission mode from file_1 to file_2
option -m is required while creating directory with access permission number like 751
It is possible to change the groups of a file1 this command chgrp [newgroup] fgile1
The command chown is used to change the file owner. It also used to change the file group inline with user owner. here is the syntax chmown -R <owner>:<groupname> .*
