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
- 
