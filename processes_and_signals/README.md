# Processes and Signals in Holbertonschool-Shell
This directory houses shell scripts that dive into Linux process management and signal handling, helping me understand how to monitor, control, and manipulate processes effectively.

![Running 7-highlander Script](link-to-image.png)

## About Me
I'm [Your Name], a software engineer passionate about mastering low-level systems programming. I built these scripts to deepen my Linux expertise. Connect with me on [LinkedIn](your-linkedin-url), follow my coding journey on [X](your-x-url), or check out my [Portfolio](portfolio-repo-url).

## Overview
The `processes_and_signals` directory contains scripts that explore Linux process management and signal handling. From displaying process IDs (`0-what-is-my-pid`) to creating immortal processes (`7-highlander`), these scripts tackle real-world system administration challenges.

## My Development Journey
Working on `7-highlander` was a game-changer—I had to figure out how to make a process resist termination signals, which led me down a rabbit hole of `trap` commands. I also struggled with `6-stop_me_if_you_can`, where I learned the nuances of cross-process signaling.

## Features
**Implemented:**
- `0-what-is-my-pid`: Displays the current script’s process ID.
- `4-to_infinity_and_beyond`: Runs an infinite loop to simulate a persistent process.
- `7-highlander`: Creates a process that resists termination.
- `11-manage_my_process`: Manages a background process with start/stop functionality.

**Future Goals:**
- Add signal logging for caught signals.
- Enhance `manage_my_process` with status monitoring.

## Key Challenges
- **Signal Trapping**: Trapping SIGTERM in `7-highlander` was tricky until I mastered `trap` syntax.
- **Process Communication**: Sending signals in `6-stop_me_if_you_can` taught me how to use `kill` effectively.

## Getting Started
1. Navigate: `cd processes_and_signals`
2. Make executable: `chmod +x 7-highlander`
3. Run: `bash 7-highlander`
4. Test signals: `kill -SIGTERM <pid>`

> “Processes are the heartbeat of a system—signals keep them in rhythm.”

[PID 1234]
  ├── [PID 1235]
  └── [PID 1236]
