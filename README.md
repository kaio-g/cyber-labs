# Cyber Labs

Hands-on cybersecurity labs and notes focused on fundamentals.

## Topics
- Linux fundamentals
- Networking basics
- Security concepts
- Practical labs

## Platforms
- TryHackMe
- Hack The Box (future)

## Structure
```text
tryhackme/
  ├── linux-fundamentals/
  │   └── notes.md
  ├── networking/
  │   └── notes.md
'''
## Linux Essential Commands
```bash

### File & Directory Management
- `ls` (list files and directories)
- `cd` (change directory)
- `pwd` (show current directory path)
- `mkdir` (create directories)
- `rmdir` (remove empty directories)
- `cp` (copy files or directories)
- `mv` (move or rename files/directories)
- `rm` (remove files or directories)
- `find` (search for files and directories)
- `locate` (quick file search using index)

### File Viewing & Editing
- `cat` (display file content)
- `less` (view file content page by page)
- `head` (show first lines of a file)
- `tail` (show last lines of a file)
- `nano` (terminal text editor)
- `vim` (advanced text editor)

### Permissions & Ownership
- `chmod` (change file permissions)
- `chown` (change file owner)
- `chgrp` (change group ownership)
- `ls -l` (view permissions and ownership)

### User & Group Management
- `whoami` (show current user)
- `id` (display user and group IDs)
- `adduser` (create a new user)
- `passwd` (change user password)
- `groups` (show user groups)

### Networking
- `ip a` (show network interfaces)
- `ifconfig` (network configuration – legacy)
- `ping` (test network connectivity)
- `netstat` (network connections and ports)
- `ss` (socket statistics)
- `curl` (transfer data from URLs)
- `wget` (download files from the web)

### Process Management
- `ps` (show running processes)
- `top` (real-time process monitoring)
- `htop` (enhanced process viewer)
- `kill` (terminate a process)
- `killall` (terminate processes by name)

### Disk & System Information
- `df` (disk space usage)
- `du` (directory space usage)
- `free` (memory usage)
- `uname -a` (system information)
- `uptime` (system running time)
- `lsblk` (list block devices)

### Package Management (Debian/Ubuntu)
- `apt update` (update package list)
- `apt upgrade` (upgrade installed packages)
- `apt install` (install packages)
- `apt remove` (remove packages)

### Logs & Monitoring
- `journalctl` (view system logs)
- `dmesg` (kernel messages)
- `watch` (run command repeatedly)

### Compression & Archives
- `tar` (archive files)
- `zip` (compress files)
- `unzip` (extract zip files)
- `gzip` (compress files)
- `gunzip` (decompress files)

### Redirection & Pipes
- `>` (redirect output)
- `>>` (append output)
- `<` (input redirection)
- `|` (pipe output between commands)

### Permissions Cheat Sheet
- `r` = read
- `w` = write
- `x` = execute
- `777` = full permissions
- `755` = common executable permissions
- `644` = common file permissions
