# Advanced Linux Commands

## Objectives
- Understand file permissions in Linux
- Learn about user and group management
- Explore disk management commands

## Concepts

### File Permissions
File permissions in Linux define who can read, write, and execute files and directories. They are represented by three sets of permissions for the owner, group, and others.

Symbolic Representation:
- r: Read permission
- w: Write permission
- x: Execute permission

#### Command Usage:

- chmod: Changes file permissions.

  Example: chmod u+x script.sh (adds execute permission for the owner)

- chown: Changes file ownership.

  Example: chown user1:group1 file.txt (changes ownership to user1 and group1)

- chgrp: Changes group ownership of a file.

  Example: chgrp group2 file.txt (changes group ownership to group2)

### User and Group Management
Linux uses users and groups to manage access control and resource allocation.

#### Commands:
- useradd: Adds a new user account.

  Example: sudo useradd -m newuser (creates a new user 'newuser' with a home directory)

- usermod: Modifies a user account.

  Example: sudo usermod -aG group1 newuser (adds 'newuser' to 'group1')

- userdel: Deletes a user account.

  Example: sudo userdel -r olduser (deletes user 'olduser' and removes their home directory)

- groupadd: Adds a new group.

  Example: sudo groupadd group2 (creates a new group 'group2')

- groupmod: Modifies a group.

  Example: sudo groupmod -n newgroup group2 (renames 'group2' to 'newgroup')

- groupdel: Deletes a group.

  Example: sudo groupdel group2 (deletes 'group2')

### Disk Management
Linux provides commands to manage disk partitions, filesystems, and disk space usage.

#### Commands:
- df: Displays disk space usage.

  Example: df -h (displays usage in human-readable format)

- du: Shows disk usage of files and directories.

  Example: du -sh /var/log (displays size of /var/log directory)

- fdisk: Manipulates disk partition tables.

  Example: sudo fdisk -l (lists all partitions)

- mkfs: Creates a filesystem on a disk partition.

  Example: sudo mkfs.ext4 /dev/sdb1 (creates an ext4 filesystem on /dev/sdb1)

- mount: Mounts a filesystem.

  Example: sudo mount /dev/sdb1 /mnt/data (mounts /dev/sdb1 on /mnt/data)

- umount: Unmounts a mounted filesystem.

  Example: sudo umount /mnt/data (unmounts /mnt/data)

## Summary
In this lesson, you explored advanced Linux commands related to file permissions, user and group management, and disk management. Mastering these commands is essential for effective system administration and resource management in Linux.
