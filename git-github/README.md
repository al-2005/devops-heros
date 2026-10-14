# Git and GitHub

## Objective
To practise essential Git commands and understand how Git manages version control and collaboration.

## Tasks Completed

### 1. Repository Initialization
- Initialized a local Git repository using `git init`.
- Checked the repository status using `git status`.

### 2. File Tracking and Commits
- Created `notes.txt`.
- Staged the file using `git add`.
- Committed changes using `git commit`.
- Viewed commit history using `git log --oneline`.

### 3. Branching
- Created a branch named `feature-branch`.
- Made and committed a change on the feature branch.
- Listed branches using `git branch`.

### 4. Merging
- Switched back to the `master` branch.
- Merged `feature-branch` into `master`.
- Inspected the commit graph using `git log --oneline --graph --all`.

## Commands Practised

```bash
git init
git status
git add notes.txt
git commit -m "Add Git practice notes"
git log --oneline
git switch -c feature-branch
git branch
git switch master
git merge feature-branch
git log --oneline --graph --all
git show --stat --oneline HEAD
```

## Conclusion

This practical exercise helped me understand repository initialization, file staging, commits, branch creation, merging, and viewing Git history. These commands form the foundation of version control using Git.

The exercises were performed in a local practice repository.


