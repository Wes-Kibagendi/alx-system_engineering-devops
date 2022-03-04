Shell Scripting, Permissions - file and directory permission
chmod - modify file permission gives access to owner, group or others to either read, write and execute the file to each of them, example chmod 600  file
To directories: 
	r- allows listing of files therein if x is allowed
	w - creation, deletion or renaming of files if x is allowed
	x - allow the directory to be entered
chown - change ownership of file/dir; sudo chown you file
chgrp - change group ownership; chgrp new group file
su - switch users
sudo - gives acces to superuser advantages.

Scripts;

su betty- switch to user betty
whoami - prints username of current user
