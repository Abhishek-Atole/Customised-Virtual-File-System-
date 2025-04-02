# Customized Virtual File System

## Platform Required
- Windows Platform Or Linux Distributions.

## Architectural Requirement
- INTEL 32 Bit Processor Or Higher.

## User Interface
- Command Line Interface.

## Technology Used
- System Programming Using C.

## About Customized Virtual File System

The Customized Virtual File System is a project that emulates all the data structures used by an operating system to manage file system-oriented tasks. It operates in a virtual environment by maintaining all records in primary storage (RAM).

### Implemented Data Structures
1. **FT (File Table):** Emulation of the file table.
2. **UAREA:** Emulation of the user area.
3. **UFDT (User File Descriptor Table):** Emulation of the user file descriptor table.
4. **SB (Super Block):** Emulation of the super block.
5. **DILB (Data Inode List Block):** Emulation of the data inode list block.
6. **DB (Data Block):** Emulation of the data block.

### Implemented System Calls and Commands
- Open
- Close
- Read
- Write
- Lseek
- Create
- RM (Remove)
- LS (List)
- Stat
- Fstat

### Project Overview
This project provides a comprehensive implementation of the necessary system calls and commands for file subsystem operations. The functionalities are built using custom data structures inspired by algorithms used in the UNIX operating system.

### How to Use
1. Clone the repository.
2. Compile the source code using a C compiler compatible with your platform.
3. Run the executable in the command line.

### Example Usage
```bash
$ ./virtual_file_system
