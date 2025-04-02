# Customised Virtual File System

## Overview
This project provides all functionality similar to the Linux File System, implementing necessary system calls and commands via a **customised shell**. It enables system-level operations across different OS platforms. The system implements core Linux file operations, allowing users to perform file management efficiently. By incorporating file system structures such as Incore Inode Table and File Descriptor Table, it ensures seamless storage handling. 

The project provides an **interactive shell** where users can execute commands similar to Linux, making it ideal for educational and experimental purposes in system programming. 

## Features
- Implements essential file system structures: **Incore Inode Table, File Table, UAREA, User File Descriptor Table**.
- Customised shell for interacting with the file system.
- Supports core **Linux-like** operations for file management.
- Allows file operations such as **creation, deletion, reading, writing, and permissions management**.
- Enables a Linux-like environment on non-Linux operating systems.

## Technologies Used
- **Programming Language:** C
- **Operating System:** Linux

## Installation & Usage
```bash
# Clone this repository
git clone https://github.com/yourusername/custom-vfs.git
cd custom-vfs
# Compile the program
gcc vfs.c -o vfs
# Run the shell
./vfs
