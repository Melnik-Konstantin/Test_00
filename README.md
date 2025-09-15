Day 1 Mandatory Practice Project
Project Overview

This is the Day 1 practice project for learning Git. The main goal is to get familiar with basic Git operations: initializing a repository, creating commits, managing files, and exploring Git history.

Project Structure

README.md — project description.

app.py — main Python file. Initially contains:

print("Hello Git")


notes.txt — personal notes.

.gitignore — ignores files with the pattern *.log.

dummy.log — example log file to test .gitignore.

Git Practice Steps

Created the folder day1_project and initialized Git:

git init


Created files: README.md, app.py, notes.txt.

Made at least 5 commits:

Added all initial files.

Modified app.py (e.g., added a new function).

Deleted notes.txt.

Added .gitignore with *.log.

Added a dummy log file and verified Git ignores it.

Used git log --graph --oneline to visualize the commit history.

Practiced undoing changes with:

git checkout -- <file>

Learning Outcomes

Basic Git workflow: add, commit, status.

Understanding staging area and commit history.

Ignoring files with .gitignore.

Viewing Git history as a graph.

Undoing changes in files using git checkout.
