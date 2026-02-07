sudo apt update

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