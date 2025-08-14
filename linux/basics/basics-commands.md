# Essential Linux Commands for Beginners

Below is a list of basic Linux commands that are fundamental for anyone starting with Linux:

## File and Directory Management
- `ls` – List directory contents
- `pwd` – Print working directory
- `cd` – Change directory
- `mkdir` – Make directories
- `rmdir` – Remove empty directories
- `rm` – Remove files or directories
- `cp` – Copy files and directories
- `mv` – Move/rename files and directories
- `touch` – Create empty files
- `cat` – Concatenate and display file content
- `less` / `more` – View file content page by page
- `find` – Search for files in a directory hierarchy
- `locate` – Find files by name

## File Permissions
- `chmod` – Change file modes or Access Control Lists
- `chown` – Change file owner and group
- `chgrp` – Change group ownership

## Viewing and Editing Files
- `nano` – Simple text editor
- `vim` – Advanced text editor
- `head` – Output the first part of files
- `tail` – Output the last part of files
- `grep` – Search text using patterns

## System Information
- `uname` – Print system information
- `df` – Report file system disk space usage
- `du` – Estimate file space usage
- `free` – Display memory usage
- `top` – Display Linux processes
- `htop` – Interactive process viewer (if installed)
- `whoami` – Print effective username
- `date` – Display or set the system date and time

## Networking
- `ping` – Check network connectivity
- `ifconfig` / `ip` – Configure network interfaces
- `netstat` – Network statistics
- `curl` – Transfer data from or to a server
- `wget` – Download files from the web

## Package Management (Debian/Ubuntu)
- `apt update` – Update package lists
- `apt upgrade` – Upgrade all packages
- `apt install <package>` – Install a package
- `apt remove <package>` – Remove a package


## User and Group Management
- `sudo` – Execute a command as another user (usually root)
- `useradd` – Create a new user
- `passwd` – Change user password
- `userdel` – Delete a user account
- `groupadd` – Create a new group
- `gpasswd -a` – Add a user to a group
- `gpasswd -m` – Set group members
- `groupdel` – Delete a group

## Other Useful Commands
// ...existing code...

---

---

## File Permission Table (User/Group/Other)

| Number | Read (R) | Write (W) | Execute (X) |
|--------|----------|-----------|-------------|
|   0    |    -     |     -     |     -       |
|   1    |    -     |     -     |     X       |
|   2    |    -     |     W     |     -       |
|   3    |    -     |     W     |     X       |
|   4    |    R     |     -     |     -       |
|   5    |    R     |     -     |     X       |
|   6    |    R     |     W     |     -       |
|   7    |    R     |     W     |     X       |

> Use this table to quickly determine the numeric value for chmod permissions.
