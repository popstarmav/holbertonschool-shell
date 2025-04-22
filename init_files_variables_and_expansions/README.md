# Shell Init Files, Variables, and Expansions

This repository contains shell scripts that demonstrate the use of initialization files, variables, and expansions in Bash. These scripts showcase fundamental concepts for shell environment configuration and variable manipulation.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Key Concepts](#key-concepts)
- [Examples](#examples)

## Description

This project focuses on understanding and working with shell environment components, covering:
- Shell initialization files (.bashrc, .bash_profile, etc.)
- Variable creation and manipulation (local and global)
- Shell expansions and substitutions
- Command substitution and arithmetic operations
- Alias creation and management

Each script demonstrates specific aspects of shell environment management, from creating aliases to performing arithmetic operations and variable manipulations.

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
cd holbertonschool-shell/init_files_variables_and_expansions
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

- **Aliases**: Creating command shortcuts
- **Shell Variables**: Storing and manipulating data
- **Shell Initialization**: Understanding startup files
- **Local vs. Global Variables**: Scope differences
- **Reserved Variables**: Special variables like PATH, HOME
- **Expansions**: Parameter, command, and arithmetic expansions
- **Shell Arithmetic**: Performing calculations in scripts
- **Number Base Conversion**: Converting between decimal, binary, and hexadecimal

## Examples

Create an alias:
```bash
./0-alias
```

Display environment variables:
```bash
./4-global_variables
```

Perform arithmetic operations:
```bash
./9-divide_and_rule
```

Convert from binary to decimal:
```bash
./11-binary_to_decimal
```
