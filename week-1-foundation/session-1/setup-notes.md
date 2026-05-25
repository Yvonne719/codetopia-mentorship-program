#Notes on Git Installation Verification, Configuration Commands and Commands Learned during Week 1

#Git Installation Verification
To ensure that git was installed and accessible through the terminal interface, the following command
was executed; 

**Command:** git --version
**Result:** This returns the version of GitHub that is currently installed on the Operating System.

#Configuration Commands
On GitHub, it is very important for one to configure his or her identity, most of the time for
security reasons. The following commands are used to configure a name and an email and verify the;
configuration.

** Commands - name:** git config --global user.name "Princess Yvonne Eshun"
** Commands - email:** git config --global user.email "princessyveshun@gmail.com"
** Command for verification:** git config --list

#Git Commands Learned during Week 1
* cd [directory-path] - Change directory to navigate through the file system.

* ls - List files and subfolders within the current active directory.

* ls -a - Reveal all contents, including hidden system files (like .git).

* mkdir - create a project

* mkdir -p [path] - Create parent and nested subdirectories simultaneously.

* git init - creates a hidden .git folder which will hold all your commits 

* git status - check status

* git add - stage a file

* git add . - stage more than one file

* git  commit -m - commit a file with a message

* echo - create a file

* cat - view the contents of a textfile in the terminal

* nano - opening a textfile and editing it

* git log - full history

* git log --oneline - shows only one line per commit

* git log --oneline --graph - visualize branches

* git log --oneline --all --graph - include all branches


