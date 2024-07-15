# Linux File System Hierarchy
The Linux file system organizes files and directories into a structured hierarchy. Understanding this hierarchy is essential for navigating and managing files effectively in Linux.

## Overview
### Root Directory (/)
The root directory is the top-level directory in the Linux file system hierarchy. All other directories and files are subdirectories or files within the root directory.

### Common Directories

**/bin**

Contains essential binary executable files (commands) required for system boot and maintenance (e.g., ls, cp, mv).

**/boot**

Contains boot loader files and the Linux kernel.

**/dev**

Contains device files, representing physical and virtual devices (e.g., hard drives, terminals).

**/etc**

Contains system-wide configuration files and scripts (e.g., /etc/passwd for user information, /etc/apt for package management on Debian-based systems).

**/home**

Contains user home directories, where users store personal files and configurations.

**/lib and /lib64**

/lib contains essential shared library files required by executable programs.

/lib64 on 64-bit systems contains 64-bit libraries.

**/media**

Mount point for removable media devices (e.g., USB drives, CDs).

**/mnt**

Mount point for temporarily mounted filesystems.

**/opt**

Optional application software packages can be installed here (e.g., /opt/google/chrome).

**/proc**

Virtual filesystem providing information about processes and system status.

Contains dynamic system information and kernel data structures as files.

**/root**

Home directory for the root user (superuser).

**/sbin**

Contains system binaries (commands) essential for system administration, typically used by the superuser.

**/srv**

Contains data directories for specific services provided by the system.

**/tmp**

Directory for temporary files created by system and users. Files here may be deleted automatically by the system.

**/usr**

Contains user-accessible programs and files that are not required for system booting.

Subdirectories include /usr/bin, /usr/sbin, /usr/lib, /usr/local, etc.

**/var**

Contains variable data files (e.g., logs, databases, mail spool directories) that may change in size and content while the system is running.

### Understanding Paths
Paths in Linux start from the root directory (/) and specify the location of files and directories. Absolute paths begin with /, while relative paths specify locations relative to the current directory.

Examples:

Absolute path: /etc/passwd

Relative path: ../documents/myfile.txt (relative to the current directory)

## Summary
The Linux file system hierarchy is a structured organization of directories and files, starting with the root directory (/). Each directory serves a specific purpose, facilitating system administration, user management, application installation, and data storage.
