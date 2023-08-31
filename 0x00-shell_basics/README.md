Task 0
pwd : Termnal command to that prints the absolute path name of the current working directory.
Task 1
ls : Display the contents list of your current directory.
Task 2
cd ~ : changes the working directory to the user’s home directory
Task 3
ls -l : Display current directory contents in a long format
Task 4
ls -l -a : Display current directory contents, including hidden files
Tsak 5
ls -lna : Display current directory contents Long format, with user and group IDs displayed numerically And hidden files (starting with .)
Task 6
mkdir /tmp/my_first_directory : Create a script that creates a directory named my_first_directory in the /tmp/ directory.
Task 7
mc betty /my_first_directory : Move the file betty from /tmp/ to /tmp/my_first_directory.
Task 8
rm /tmp/my_first_directory/betty : Delete the file betty.
Task 9
rmdir /tmp/my_first_directory : Delete the directory my_first_directory that is in the /tmp directory.
Task 10
cd .. : changes the working directory to the previous one.
Task 11
ls -al / /alx-system_engineering-devops /boot : Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
Task12
file tmp/iamafile: File type
Task 13
ln -s /bin/ls __ls__
Task 14
cp -u *.html .. : Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
Task 15
mv [[:upper:]] /tmp/u : Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
Task 16
rm *~ : deletes all files in the current working directory that end with the character ~.
Task 17
mkdir -p welcome/to/school : Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
Task 18
ls -xamp : Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line.
Task 19
0 string SCHOOL school data !:mime school : Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.