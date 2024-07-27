# Introduction To Linux
## Linux: Definition, Origin
- Linux is an operating system that sits underneath all of the other software on a computer, receiving requests from those programs and relaying these requests to the computer’s hardware.
- It is the best-known and most-used open source operating system.
- In 1991, Linus Torvalds, a Finnish computer science student, started developing the Linux kernel as a personal project.

## Linux File System Hierarchy: An Overview
Linux File System contains many directories. Some of them are:
1.  **/ (Root Directory)**  - Only root user has the permission to read and write this directory.
2.  **/bin**  - Commands used by all the users of the system are located here.
3.  **/dev**  - These include terminal devices, usb, or any device attached to the system.
4.  **/etc**  - Contains configuration files required by all programs.
5.  **/home**  - Home directories for all users to store their personal files.
6.  **/tmp**  - Directory that contains temporary files created by system and users.
7.  **/usr**  - Contains binaries, libraries, documentation, and source-code for second level programs.
8.  **/var**  - Contains variable data for the system

## File Permissions
1. **Read(r) :**  User can view the contents of a file or directory.
2. **Write(w) :**  User can delete or modify a file or directory.
3. **Execute(x) :** User can run a file as a program or access a directory’s contents.

## Basic Commands
- **ls :**  List directory contents.
- **mkdir :**  Make a directory.
- **cd :**  Change directory.
- **pwd :**  Print working directory.
- **rmdir :**  Remove an empty directory.
- **rm :**  Remove files or directories.
- **cat :**  Concatenate and display the content of files.

## Networking Commands
- **ifconfig :**  Configure network interfaces.
- **ping :**  Send ICMP ECHO_REQUEST packets to network hosts to check connectivity
- **netstat :**  Print network connections, routing tables, interface statistics.
- **nmap :**  Network exploration and security auditing tool
- **traceroute :**  Trace the route packets take to a network host.

## Services And Logs
- **systemctl :**  Control the systemd system and service manage.
- **journalctl :**  View all logs managed by systemd
- **service :**  Initiate or query services.

## System Administration Commands
- **apt-get :**  Manage packages.
- **sudo :**  Execute a command as another user, typically the superuser.
- **chmod :**  Change file permissions.
- **chown :**  Change file owner and groups.
- **uname :**  Print system information.
- **ps :**  Display information about running processes.
