pwd: pwd prints the absolute path name of the current working directory.

ls: Display the contents list of your current directory.

cd ~: this changes the working directory to the user’s home directory.

ls: Display current directory contents in a long format

ls -la: this displays the current directory contents, including hidden files

ls -lna: Display current directory contents in long format, with user and group IDs displayed numerically and hidden file starting with dot 

mkdir /tmp/my_first_directory : Create a script that creates a directory named my_first_directory in the /tmp/ directory

mv /tmp/betty /tmp/my_first_file: moves the file betty from tmp to tmp/my_first_directory

rm /tmp/my_first_directory/betty: delete the file betty

rmdir /tmp/my_first_directory: delete my_first_directory (rmdir is used to delete empty directory)

cd -: this  changes the working directory to the previous one.

ls -la . .. /boot: this lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile : the file command determines the type of file named iamafile

ln -s /bin/ls __ls__ : Create a symbolic link to /bin/ls, named __ls__   

cp -u *.html ../ : this script copies all the HTML files from the current working directory to the parent of the workingdirectory, but only copy files that did not exist in the parent of the working directory or were newer than the versionsin the parent of the working directory.

mv [[:upper:]]* /tmp/u : this script moves all files beginning with an uppercase letter to the directory /tmp/u.   

rm *~ : this script deletes all files in the current working directory that end with the character ~.

mkdir welcome/ welcome/to/ welcome/to/school script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. 
