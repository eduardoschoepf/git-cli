# Git Commands Cheat Sheet

## Initial Configuration

### Configure user name and email
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
## Basic Commands

### Verify configuration
```bash
git config --list
```

### Initialize a Git repository
```bash
git init
```

### Clone an existing repository
```bash
git clone <repository-url>
```

### Add files to the staging area
```bash
git add <file>
git add .
```

###  Commit changes
```bash
git commit -m "Commit message"
```

### Check the repository status
```bash
git status
```

### View commit history
```bash
git log
```

## Working with Branches

### Create a new branch
```bash
git branch <branch-name>
```

### Switch to another branch
```bash
git checkout <branch-name>
```

### Create and switch to a new branch
```bash
git checkout -b <branch-name>
```

### Merge a branch into the current branch
```bash
git merge <branch-name>
```

### Delete a branch
```bash
git branch -d <branch-name>
```

## Working with Remote Repositories

### Add a remote repository
```bash
git remote add origin <repository-url>
```

### View remote repositories
```bash
git remote -v
```

### Push commits to the remote repository
```bash
git push origin <branch-name>
```

### Pull updates from the remote repository
```bash
git pull origin <branch-name>
```

### Clone a remote repository
```bash
git clone <repository-url>
```

## Other Useful Commands
