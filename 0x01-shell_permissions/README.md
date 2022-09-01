su betty - changes user from current user to user Betty.
whoami - Prints effective username of current user.
groups - prints all groups current user is part of.
sudo chown betty hello - changes owner of file hello to user Betty.
touch hello - creates an empty file hello.
chmod 744 hello - adds execute permissions to owner of file hello.
chmod 754 hello - adds execute permissions to owner and group and group owner and read permission to other users.
chmod 751 hello - adds execute permissions to owner, group owner and other users.
chmod ugo+x hello - adds execution permission to owner, group owner and others to the file hello.
chmod 007 hello - gives no permissions to owner and group owner but gives all permissions to the other users.
chmod 753 hello - gives all permissions to owner, read and execute permissions to group owner and write and execute permissions to other users.
chmod --reference=olleh Hello - sets mode of file hello to be the same as olleh's mode
chmod a+X * - creates a script that adds execute permission to all sub directories of current directory for owner, group owner and all other users. Regular files are not changed.
mkdir -m 751 my_dir - creates a directory my_dir with permissions 751.
chgrp school hello - changes group owner to school for file hello.
telnet towel.blinkenlights.nl - Plays StarWars IV episode in terminal.
chown --from=guillaume betty hello - changes owner of file hello to betty only if owner is user guillaume.

