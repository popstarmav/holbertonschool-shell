# Shell, I/O Redirections and Filters

This repository contains a collection of shell scripts that demonstrate various I/O redirections and filtering techniques in Bash. These scripts showcase fundamental command-line operations for text processing, file manipulation, and data filtering.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Examples](#examples)

## Description

This project explores the power of shell scripting with a focus on:
- Standard input/output redirection
- Command pipelines
- Text processing utilities (grep, sed, awk, etc.)
- File operations and manipulation
- Pattern matching and filtering

Each script demonstrates a specific concept or technique, providing practical examples of shell commands for everyday tasks.

The repository includes scripts for:
- Displaying text and file contents
- Manipulating file content
- Filtering and searching text
- Counting and sorting data
- Working with directories and files
- Pattern matching and replacement

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
cd holbertonschool-shell/io_redirections_and_filters
```

3. Make the scripts executable (if they aren't already):
```bash
chmod +x *.sh
```

4. Run any script:
```bash
./script_name
```

## Examples

Display "Hello, World":
```bash
./0-hello_world
```

Count the number of directories in the current path:
```bash
./11-directories
```

Find all lines containing "root" in /etc/passwd:
```bash
./14-findthatword
```
