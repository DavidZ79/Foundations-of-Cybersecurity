<h2>Navigate the Linux file system</h2>

pwd: prints working directory

ls and cd

cat, head

Standard FHS directories
Directly below the root directory, you’ll find standard FHS directories. In the diagram, home, bin, and etc are standard FHS directories. Here are a few examples of what standard directories contain:

/home: Each user in the system gets their own home directory.

/bin: This directory stands for “binary” and contains binary files and other executables. Executables are files that contain a series of commands a computer needs to follow to run programs and perform other functions.

/etc: This directory stores the system’s configuration files.

/tmp: This directory stores many temporary files. The /tmp directory is commonly used by attackers because anyone in the system can modify data in these files.

/mnt: This directory stands for “mount” and stores media, such as USB drives and hard drives.

Pro Tip: You can use the man hier command to learn more about the FHS and its standard directories.

Lab

<h2>Manage file content in Bash</h2>

grep: returns all files that contains a substring

piping: sends output of one command as the input to another command

find, name, iname, mtime

mkdir, rmdir

touch: create new file, rm removes file

mv, cp

nano

Lab (i love labs)

<h2>Authenticate and authorize users</h2>

Permissions, Authorization

Read, Write, Execute

Types of users: users, group, other

drwxrwxrwx is a permission string, d is directory

ls -l displays permissions

ls -a displays hidden files

ls -la

chmod

root/super user

root user account should have logins disabled

sudo grants temp elevated privileges

useradd, userdel

Note: When you create a new user in Linux, a group with the same name as the user is automatically created and the user is the only member of that group. After removing users, it is good practice to clean up any such empty groups that may remain behind.

<h2>Get help in Linux</h2>

LOOK THINGS UP LOLOL

man pages, whatis, apropos

<h2>Glossary</h2>

Terms and definitions from Course 4, Module 3
Absolute file path: The full file path, which starts from the root

Argument (Linux): Specific information needed by a command

Authentication: The process of verifying who someone is

Authorization: The concept of granting access to specific resources in a system

Bash: The default shell in most Linux distributions

Command: An instruction telling the computer to do something

File path: The location of a file or directory

Filesystem Hierarchy Standard (FHS): The component of the Linux OS that organizes data

Filtering: Selecting data that match a certain condition

nano: A command-line file editor that is available by default in many Linux distributions

Options: Input that modifies the behavior of a command

Permissions: The type of access granted for a file or directory

Principle of least privilege: The concept of granting only the minimal access and authorization required to complete a task or function

Relative file path: A file path that starts from the user's current directory

Root directory: The highest-level directory in Linux

Root user (or superuser): A user with elevated privileges to modify the system

Standard input: Information received by the OS via the command line

Standard output: Information returned by the OS through the shell
