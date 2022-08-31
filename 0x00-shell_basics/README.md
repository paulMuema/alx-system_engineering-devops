pwd - prints the absolute path name of the current working directory
ls - shows content list of current directory
cd - changes working directory to user's home directory
ls -l  - displays current directory contents in a long format
ls -al  - displays current directory contents, including hidden files
ls -an  - displays current directory with user and group IDs displayed numerically
mkdir tmp/my_first_directory - creates a directory named my_first_directory in /tmp/ directory
mv /tmp/betty /tmp/my_first_directory
rm /tmp/betty/my_first_directory
rm -r /tmp/my_first_directory
cd -  - changes working directory to previous one
ls -al . .. /boot - Lists all files in working directory, parent of working directory and /boot directory
file /tmp/iamafile - Prints tupe of file named iamafile
ln -s /bin/ls ls -  Creates a symbolic link to /bin/ls named __ls__
cp -rua *.html ../ - copies all HTML files from current working directory to parent of working directory
mv [[:upper:]]* /tmp/u - moves files beginning with uppercase letter to directory /tmp/u
rm *~ - deletes all files in current working directory that end with character ~
mkdir -p welcome/to/school - creates directories welcome/, welcome/to and welcome/to/school
ls -map | sort -d
