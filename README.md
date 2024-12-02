# Distributed-Source-Control-System-DSCS---Inspired-by-Git
This project is a lightweight, file-based distributed source control system designed in the style of Git. It provides core version control functionalities to track file changes, manage branches, and collaborate on projects—all within a custom repository structure.

# Features
Initialize a Repository: Create a .dotgit directory with all necessary subdirectories and configuration files.
Staging Area (git add): Stage files for commits by tracking changes and preparing snapshots.
Committing Changes: Save a snapshot of staged files with metadata like author, timestamp, and message.
View Commit History: Traverse the commit graph to display detailed commit logs.
Branching: Create and switch between branches for parallel development.
Merging: Combine changes from different branches with basic conflict detection.
Diffing: Compare changes between commits or branches.
Cloning: Copy an existing repository to a new location on disk.
Ignore Files: Use a .dotgitignore file to exclude specific files or patterns from tracking.

# How It Works
The system mimics Git's architecture:
All repository data is stored in a .dotgit directory.
Files are hashed and stored as objects.
Branches are managed through reference files under .dotgit/refs/heads.
The HEAD file tracks the current branch.
