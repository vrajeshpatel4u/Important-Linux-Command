# Important-Linux-Command
Important Linux Command

pwd : The pwd command is a command line utility for printing the current working directory. It will print the full system path of the current working directory to standard output.

rm command is used to delete the files and directories in Linux. rm stands for remove.

Syntax : rm [options] [-r directories] filenames

Options :

-i : is used to prompting before every removal.

Ex : rm -ri PHP – It will remove php folder after input ‘Y’. (‘N’ for No).

-d : is used to delete an empty directory.

Ex : rm -d PHP or rm -rd PHP

-r, -R, — recursive: option deletes all the files and subdirectories in the parent directory recursively.

Ex : rm -r PHP

-f, — force: option ignores nonexistent files and it will never prompt.

Ex : rm -rf PHP or rm -rf PHP

Wget : Wget is the non-interactive network downloader which is used to download files from the server even when the user has not logged on to the system and it can work in the background without hindering the current process.

Syntax : wget [option] [URL]

Example : wget http://example.com/sample.php

mv : mv stands for move. mv is used to move one or more files or directories from one place to another in file system.

Syntax : mv [Option] source destination

Ex : mv /home/v/Desktop/VP/Move.php /home/v/Desktop/VK/Move.php

If the destination file exist, then it will be overwrite and the source file will be deleted. By default, mv doesn’t prompt for overwriting the existing file, So be careful !!

who : The basic who command with no command-line arguments shows the names of users that are currently logged in, and depending on which Unix/Linux system you are using, may also show the terminal they’re logged in on, and the time they logged in.

Ex : who

uname : To know only system name, you can use uname command.

Ex : uname

cat /etc/os-release : To know the System Info.

Ex : cat /etc/os-release

sudo -i : Users can gain root by “sudo” and not by switching to the root user.

Ex : sudo -i

du -sh ‘foldername’ : To know size of folder in MB.

Syntax : du -sh 'foldername'

Ex : du -sh pub/media

grep -r -H “Searh” * : Find in Files via SSH.

Syntax : grep -r -H "SearhWords" *

Ex : grep -r -H "Add to Cart" *

ssh -V : To check the SSH info.

Ex : ssh -V

composer -v : To check the Composer info.

Ex : composer -v
