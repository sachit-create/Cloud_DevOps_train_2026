## Today's Work

- So we have studied about linux
- and practised some basic linux commands.
- Also studied about text editors in linux.


## Commands

udo apt update

General Operations:

- clear = Clears the terminal

Directory Operatings:

- pwd = Show current directory. Example Output: /home/rgupta
- ls = List folders and files. Example Output: Desktop  Downloads  Pictures  Documents
- cd [dirname] = Change directory to [dir]
- mkdir [dirname] = Make directory [dirname]
- cd .. = Go up a directory

File Operations:

- touch [filename] = Create [filename]
- rm [filename] = Delete [filename]
- rm -r [dirname] = Delete a non-empty directory and all the files in it
- rm -d [dirname] or rmdir [dirname] = Delete an empty directory

Navigating in the File System:

- cd usr/local/bin = Navigate multiple dirs (relative path - relative to current dir). Move to bin directory
- cd ../.. = Move up 2 hierarchies, so go to 'usr' directory
- cd /usr = Alternative to go to 'usr' directly (absolute path)
- cd [absolute path] = Move to any location by providing the full path
- cd /home/rgupta = Go to my home directory (absolute path)
- cd ~ = Shortcut alternative to go to home directory
- ls /etc/network = List folders and files of 'network' directory

More File and Directory Operations

- mv [filename] [new_filename] = Rename the file to a new file name
- cp -r [dirname] [new_dirname] = Copy dirname to new_dirname recursively meaning including the files
- cp [filename] [new_filename] = Copy filename to new_filename

Some more useful commands

- ls -R [dirname] = Show dirs and files but also sub dirs and files
- history = Gives a list of all past commands typed in the current terminal session
- history 20 = Show list of last 20 commands
- CTRL + r = Search history
- CTRL + c = Stop current command
- CTRL + SHIFT + v = Paste copied text into terminal
- ls -a = See hidden files too
- cat [filename] = Display the file content
- cat .bash_history = Example 1: Display the file content
- cat Documents/java-app/Readme.md = Example 2: Display the file content

Display OS Information

- uname -a = Show system and kernel
- cat /etc/os-release =  Show OS information
- lscpu = Display hardware information, e.g. how many CPU you have etc.
- lsmem = Display memory information

Execute commands as superuser

- sudo [some command] = Allows regular users to run programs with the security privileges of the superuser or root
- su - admin = Switch from rgupta user to admin

</details>

**

APT Package Manager:

- sudo apt search [package_name] = Search for a given package
- sudo apt install [package_name] = Install a given package
- sudo apt install [package_name] [package_name2] = Install multiple packages with one command
- sudo apt remove [package_name] = Remove installed package
- sudo apt update = Updates the package index. Pulls the latest change sfrom the APT repositories

APT-GET Package Manager:

- sudo apt-get install [package_name] = Install package with apt-get package manager

SNAP Package Manager:

- sudo snap install [package_name] = Install a given package

</details>

**

Install Vim, if it's not available:

- sudo apt install vim = Search for a given package

There are 2 Modes:

- Command Mode: default mode, everything is interpreted as a command
- Insert Mode: Allows to enter text

Vim Commands:

- vim [filename] = Open file with Vim
- Press i key = Switch to Insert Mode
- Press esc key = Switch to Command Mode
- Type :wq = Write File to disk and quit Vim
- Type :q! = Quit Vim without saving the changes
- Type dd = Delete entire line
- Type d10 = Delete next 10 lines
- Type u = Undo
- Type A = Jump to end of line and switch to insert mode
- Type 0 = Jump to start of the line
- Type $ = Jump to end of the line
- Type 12G = Go to line 12
- Type 16G = Go to line 16
- Type /pattern = Search for pattern, e.g. /nginx
  - Type n = Jump to next match
  - Type N = Search in opposite direction
- Type :%s/old/new = Replace 'old' with 'new' throughout the file

