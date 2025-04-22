# Processes and Signals

This repository contains shell scripts that explore Linux process management and signal handling concepts. These scripts demonstrate fundamental techniques for monitoring, controlling, and manipulating processes in a Unix/Linux environment.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Key Concepts](#key-concepts)
- [Examples](#examples)

## Description

This project focuses on understanding and working with processes and signals in Linux, covering:
- Process identification and listing
- Process monitoring and management
- Signal handling and trapping
- Background processes and daemons
- Process control techniques

Each script demonstrates specific aspects of process management, from basic operations like displaying PIDs to more complex scenarios like creating resilient processes that handle signals.

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
cd holbertonschool-shell/processes_and_signals
```

3. Make the scripts executable:
```bash
chmod +x *.sh
```

4. Run any script:
```bash
./script_name
```

## Key Concepts

- **Process ID (PID)**: Unique identifier for running processes
- **Signals**: Software interrupts sent to processes
- **Trapping**: Capturing and handling signals in scripts
- **Background Processes**: Processes that run without being connected to the terminal
- **Process Management**: Starting, stopping, and monitoring processes

## Examples

Display your script's PID:
```bash
./0-what-is-my-pid
```

Create an "immortal" process that resists termination:
```bash
./7-highlander
```

Manage a background process:
```bash
./11-manage_my_process start
./11-manage_my_process stop
./11-manage_my_process restart
```
