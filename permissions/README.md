# Permissions in Holbertonschool-Shell
This directory contains shell scripts designed to master Linux file and directory permissions, helping me automate user access control and understand ownership intricacies.

![Running 9-John_Doe Script](link-to-image.png)

## About Me
I'm [Your Name], a software engineer passionate about systems programming and automation. These scripts reflect my journey in mastering Linux permissions. Connect with me on [LinkedIn](your-linkedin-url), follow my tech journey on [X](your-x-url), or explore my [Portfolio](portfolio-repo-url).

## Overview
The `permissions` directory features scripts that automate Linux permission management, from changing file ownership (`3-new_owner`) to setting symbolic link permissions (`15-symbolic_link_permissions`). These scripts helped me grasp `chmod`, `chown`, and `chgrp` commands.

## My Development Journey
Writing `10-mirror_permissions` was eye-opening—I had to mirror permissions between files, which deepened my understanding of `stat` and `chmod`. The trickiest part was `16-if_only`, where I learned to apply conditional permission changes based on the owner.

## Features
**Implemented:**
- `0-iam_betty`: Switches the current user to `betty`.
- `9-John_Doe`: Sets specific permissions (rwxr-x-wx) for a file.
- `11-directories_permissions`: Adds execute permissions to all subdirectories.
- `15-symbolic_link_permissions`: Changes permissions for symbolic links.

**Future Goals:**
- Add a script to audit permissions across a directory tree.
- Implement permission rollback functionality for testing.

## Key Challenges
- **Symbolic Links**: In `15-symbolic_link_permissions`, I struggled with how symbolic links inherit permissions, but `chmod -h` cleared things up.
- **Conditional Logic**: Writing `16-if_only` required precise `if` conditions to check ownership before changing permissions.

## Getting Started
1. Navigate: `cd permissions`
2. Make executable: `chmod +x 9-John_Doe`
3. Run: `bash 9-John_Doe`
4. Verify: `ls -l` to see the changes.

> “Permissions are the gatekeepers of a system—set them wisely.”

-rwxr-xr-x  [file]
drwxr-xr-x  [dir]
