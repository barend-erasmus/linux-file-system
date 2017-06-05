# Linux: File System

In this document we'll cover:

1. Why the Linux File System is important?
2. File System Explained

## Why the Linux File System is important?

Understanding the Linux File System will clear out a lot of questions.

* What is a socket file?
* 'myfile' vs. 'myFile' ( Case Sensitivity )
* No C: or D: drive?
* Deleting an open file?

**In Linux everything is a file**

* External Drives
* Network Traffic
* CPU Performance
* SWAP configuration
* ...

**NO CONTROL PANEL**

**NO USER MANAGEMENT**

**NO REGISTRY**


There is tools that could help with the above but all these still is edits a file.

## File System Explained

Here is a list of the most commonly used directories in the Linux File System. There are a few which we'll not cover as it is optional or distribution specific.

![](https://github.com/barend-erasmus/linux-file-system/raw/master/screenshots/linux-filesystem.png)

### / – The Root Directory

Everything on your Linux system is located under the / directory, known as the root directory.

### /bin – Essential User Binaries

The /bin directory contains the essential user binaries (programs) that must be present when the system is mounted in single-user mode. Programs which a user install will be under /usr/bin but system programs will be located in /bin.

### /boot – Static Boot Files

The files in the /boot directory is needed to boot the system.

### /dev – Device Files

Remember everything is a file, including devices. Examples would be CPU, Keyboard and Memory.

### /etc – Configuration Files

The /etc directory contains configuration files, which can generally be edited by hand in a text editor.

### /home – Home Folders

The /home directory contains a home folder for each user.

### /lib – Essential Shared Libraries

The /lib directory contains libraries needed by the essential binaries in the /bin and /sbin folder.

### /media – Removable Media

The /media directory contains subdirectories where removable media devices inserted into the computer are mounted.

### /opt – Optional Packages

The /opt directory contains subdirectories for optional software packages.

### /proc – Kernel & Process Files

The /proc directory similar to the /dev directory because it doesn’t contain standard files. 

### /root – Root Home Directory

The /root directory is the home directory of the root user.

### /run – Application State Files

The /run directory is fairly new, and gives applications a standard place to store transient files they require like sockets and process IDs.

### /sbin – System Administration Binaries

The /sbin directory is similar to the /bin directory. It contains essential binaries that are generally intended to be run by the root user for system administration.

### /srv – Service Data

The /srv directory contains “data for services provided by the system.”

### /tmp – Temporary Files

Applications store temporary files in the /tmp directory. These files are generally deleted whenever your system is restarted.

### /usr – User Binaries & Read-Only Data

The /usr directory contains applications and files used by users, as opposed to applications and files used by the system.

### /var – Variable Data Files

The /var directory is the writable counterpart to the /usr directory, which must be read-only in normal operation.
