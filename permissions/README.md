# Shell Permissions

This repository contains shell scripts that demonstrate and automate Linux file and directory permission management. These scripts cover fundamental operations for controlling access to files and directories in a Unix/Linux environment.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Key Concepts](#key-concepts)
- [Examples](#examples)

## Description

This project focuses on understanding and working with Linux permissions, covering:
- User and group ownership management
- Permission settings for files and directories
- Special permissions and modes
- Symbolic links permissions
- Conditional permission changes

Each script demonstrates specific aspects of permission management, from basic operations like changing owners to more complex scenarios like mirroring permissions between files.

## Requirements

- All scripts are designed to be run on Ubuntu 20.04 LTS
- All scripts are executable (`chmod +x script_name`)
- All scripts pass shellcheck without any errors
- The first line of all scripts is `#!/bin/bash`

## Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/holbertonschool-shell.git
```

2. Navigate to the directory:
```bash
cd holbertonschool-shell/permissions
```

3. Make the scripts executable (if they aren't already):
```bash
chmod +x *
```

4. Run any script:
```bash
./script_name
```

## Key Concepts

- **File Ownership**: Managing which users and groups own files
- **Permission Modes**: Setting read, write, and execute permissions
- **Symbolic Notation**: Using letters (rwx) to represent permissions
- **Numeric Notation**: Using octal numbers (e.g., 755) to set permissions
- **Special Permissions**: Understanding setuid, setgid, and sticky bit
- **Directory Permissions**: How permissions affect directory access

## Examples

Switch to another user:
```bash
./0-iam_betty
```

Set specific permissions for a file:
```bash
./9-John_Doe
```

Add execute permission to all subdirectories:
```bash
./11-directories_permissions
```

Change permissions for symbolic links:
```bash
./15-symbolic_link_permissions
```
