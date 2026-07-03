# 🐧 Linux Cheat Sheet

A practical Linux command reference for students, developers, and cybersecurity enthusiasts.

---

## 📖 Table of Contents

- File & Directory Management
- File Permissions
- User Management
- Process Management
- Networking
- Searching & Filtering
- Compression & Archives
- Disk Usage
- Package Management
- SSH
- Useful One-Liners
- Cybersecurity Commands

---

## 📁 File & Directory Management

| Command | Description |
|----------|-------------|
| `pwd` | Show current directory |
| `ls` | List files and directories |
| `ls -la` | List all files including hidden ones |
| `cd directory` | Change directory |
| `mkdir folder` | Create a directory |
| `rmdir folder` | Remove an empty directory |
| `rm file` | Delete a file |
| `rm -rf folder` | Delete a directory recursively |
| `cp source destination` | Copy files |
| `mv source destination` | Move or rename files |
| `touch filename` | Create an empty file |

---
## 🔒 File Permissions

| Command | Description |
|----------|-------------|
| `chmod 755 file` | Set file permissions |
| `chmod +x script.sh` | Make a script executable |
| `chown user file` | Change file owner |
| `chgrp group file` | Change file group |

### Permission Numbers

| Number | Meaning |
|---------|---------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
| 0 | --- |

---

## 👤 User Management

| Command | Description |
|----------|-------------|
| `whoami` | Display current user |
| `id` | Show user and group IDs |
| `passwd` | Change password |
| `sudo command` | Run command as administrator |

---

## ⚙️ Process Management

| Command | Description |
|----------|-------------|
| `ps` | Show running processes |
| `top` | Real-time process viewer |
| `kill PID` | Terminate a process |
| `killall process` | Kill all processes with the given name |

---

## 🌐 Networking

| Command | Description |
|----------|-------------|
| `ip a` | Show IP addresses |
| `ping host` | Test connectivity |
| `curl URL` | Fetch data from a URL |
| `wget URL` | Download a file |
| `ssh user@host` | Connect to a remote system |
| `netstat -tuln` | Show listening ports |
| `ss -tuln` | Modern replacement for netstat |

---

## 🔍 Searching & Filtering

| Command | Description |
|----------|-------------|
| `grep` | Search text |
| `find` | Find files |
| `locate` | Quickly locate files |
| `cat` | Display file contents |
| `less` | View large files |
| `head` | Show first lines |
| `tail` | Show last lines |

---

## 🛡️ Cybersecurity Commands

| Command | Purpose |
|----------|---------|
| `nmap` | Network scanning |
| `tcpdump` | Packet capture |
| `journalctl` | View system logs |
| `history` | Command history |
| `sha256sum` | Generate SHA-256 hash |
| `md5sum` | Generate MD5 hash |

---

## 📜 License

This project is licensed under the MIT License.