# Shell Basics

This repository contains shell scripts that demonstrate fundamental command-line operations in Linux. These scripts cover essential file system navigation, manipulation, and management tasks.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Key Concepts](#key-concepts)
- [Examples](#examples)

## Description

This project focuses on mastering basic shell commands and operations, covering:
- File system navigation and directory management
- File creation, deletion, and manipulation
- Listing files with various options and formats
- Working with symbolic links
- File copying and moving operations
- Pattern matching for file operations

Each script demonstrates specific shell commands and operations, providing practical examples of everyday command-line tasks.

## Requirements

- All scripts are designed to be run on Ubuntu 20.04 LTS
- All scripts are executable (`chmod +x script_name`)
- All scripts pass shellcheck without any errors
- The first line of all scripts is `#!/bin/bash`
- A comment explains what each script does

## Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/holbertonschool-shell.git
```

2. Navigate to the directory:
```bash
cd holbertonschool-shell/basics
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

- **File System Navigation**: Moving between directories (cd, pwd)
- **File Listing**: Viewing directory contents (ls with various options)
- **File Operations**: Creating, copying, moving, and deleting files
- **Directory Management**: Creating and removing directories
- **Symbolic Links**: Creating and working with symbolic links
- **File Patterns**: Using wildcards and pattern matching

## Examples

Display current working directory:
```bash
./0-current_working_directory
```

List files in multiple directories:
```bash
./11-lists
```

Create a symbolic link:
```bash
./13-symbolic_link
```

Copy HTML files:
```bash
./14-copy_html
```
