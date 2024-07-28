# Introduction To Windows
Windows is an operating system developed by Microsoft, designed to provide a graphical user interface (GUI), virtual memory management, multitasking, and support for many peripheral devices. 

## Windows File System 
Windows supports several file systems. The most common ones are:
- FAT (File Allocation Table) : FAT12, FAT16, FAT32
- exFAT (Extended File Allocation Table)
- NTFS (New Technology File System)
- ReFS (Resilient File System)
- HPFS (High Performance File System)

NTFS is the default file system for Windows operating systems from Windows XP onwards. Before NTFS, FAT and HPFS was used.

## Folders
- **C:\Windows** is the folder which contains the OS.
- **System32** folder inside the Windows folder holds the important files that are critical for OS.

## Access Control Types, Permissions, and User Access Control (UAC)
### Access Control Types 
- **Discretionary Access Control (DAC) :**  It is the primary access control model.  It allows resource owners to define who can access their resources and what operations they can perform.
- **Mandatory Access Control (MAC) :**  It is more stringent and is typically used in environments requiring high-security levels.
- **Role-Based Access Control (RBAC) :** It simplifies access management by assigning permissions to roles rather than individual users.
- **Attribute-Based Access Control (ABAC) :**  It is a more dynamic and flexible model that evaluates access based on attributes.
### Permissions
Windows permissions are categorized into two main types:
1. **NTFS Permissions :**  Read, write, read & execute, modify, full control, etc.
2. **Share Permissions :**  Read, change and full control
### User Access Control (UAC)
- It is introduced by Microsoft to protect the local users with elevated privileges.
- It prompts users for permission or an administrator password before allowing applications to make changes that could affect the system or other users.
- It does not apply for built-in local admin account.

## Windows Firewall and Windows Defender
### Windows Firewall
- It is a built-in network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules.
- Its primary goal is to protect the computer from unauthorized access and network-based threats.
### Windows Defender
- It is a built-in antivirus and anti-malware program that provides real-time protection against various types of threats, including viruses, spyware, and ransomware.

## Windows Remote Management and Remote Desktop Prototcol
### Windows Remote Management (WinRM)
It is a command-line tool that enables administrators to remotely execute commands, manage configurations, and access system information on Windows machines.
### Remote Desktop Protocol (RDP)
It is a proprietary protocol developed by Microsoft that allows users to connect to and control a remote Windows computer through a graphical user interface (GUI).

## Basic Commands
- **dir :**  Lists the contents of a directory.
- **cd :**  Change directory.
- **mkdir :**  Create a new directory.
- **rmdir :**  Remove a directory.
- **move :**  Move a file from one location to another.
- **copy :**  Copy a file from one location to another.
- **ipconfig :**  Displays network configuration details.
- **systeminfo :**  Provides detailed information about the system.
- **net :**  Used to manage network resources.
- **attrib :**  Changes file attributes
- **ping :**  Tests network connectivity to a specific IP address or hostname.
- **tracert :**  Traces the route taken by packets to reach a network host.
- **netstat :**  Displays active network connections and listening ports.

## Batch Scripting
-  It allows you to automate tasks by writing scripts that execute a sequence of commands.
-  These are plain text files with a **.bat** or **.cmd** extension.
-  To create a batch file, write commands in a text file and save it with a .bat extension.
