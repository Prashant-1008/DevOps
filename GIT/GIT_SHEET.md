# Git Cheat Sheet

## Getting Started
- **Initialize a repository**: `git init`
- **Clone a repository**: `git clone <repository_url>`

## Basic Commands
- **Check status**: `git status`
- **Add files to staging area**: `git add <file>`
- **Commit changes**: `git commit -m "commit message"`
- **View commit history**: `git log`

## Branching
- **List branches**: `git branch`
- **Create a new branch**: `git branch <branch_name>`
- **Switch to a branch**: `git checkout <branch_name>`
- **Create and switch to a new branch**: `git checkout -b <branch_name>`
- **Merge a branch**: `git merge <branch_name>`

## Remote Repositories
- **Add a remote repository**: `git remote add <name> <url>`
- **Fetch changes from remote**: `git fetch <remote>`
- **Push changes to remote**: `git push <remote> <branch>`
- **Pull changes from remote**: `git pull <remote> <branch>`

## Undoing Changes
- **Unstage a file**: `git reset <file>`
- **Revert a commit**: `git revert <commit_hash>`
- **Reset to a previous commit**: `git reset --hard <commit_hash>`

## Stashing
- **Stash changes**: `git stash`
- **Apply stashed changes**: `git stash apply`
- **List stashes**: `git stash list`

## Viewing Differences
- **Show changes**: `git diff`
- **Show changes between commits**: `git diff <commit1> <commit2>`

## Tags
- **Create a tag**: `git tag <tag_name>`
- **List tags**: `git tag`
- **Push tags to remote**: `git push <remote> --tags`

## Configuration
- **Set username**: `git config --global user.name "Your Name"`
- **Set email**: `git config --global user.email "your.email@example.com"`

## Helpful Tips
- **View help for a command**: `git help <command>`
- **Alias a command**: `git config --global alias.<alias_name> '<command>'`
