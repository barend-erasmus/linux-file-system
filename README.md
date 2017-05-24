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

### / – The Root Directory

Everything on your Linux system is located under the / directory, known as the root directory.

### /bin – Essential User Binaries

The /bin directory contains the essential user binaries (programs) that must be present when the system is mounted in single-user mode. Programs which a user install will be under /usr/bin but system programs will be located in /bin.

### /boot – Static Boot Files

The files in the /boot directory is needed to boot the system.

### /dev – Device Files

Remember everything is a file, including devices. Examples would be CPU, Keyboard and Memory.

### /etc – Configuration Files

### /home – Home Folders

### /lib – Essential Shared Libraries

### /media – Removable Media

### /mnt – Temporary Mount Points

### /opt – Optional Packages

### /proc – Kernel & Process Files

### /root – Root Home Directory

### /run – Application State Files

### /sbin – System Administration Binaries

### /srv – Service Data

### /tmp – Temporary Files

### /usr – User Binaries & Read-Only Data

### /var – Variable Data Files