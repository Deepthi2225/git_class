#  Git Cheatsheet – Basic Commands

This cheat sheet covers essential Git commands used for everyday version control tasks.

---

## Initialization

```bash
git init               # Create a new Git repository
git clone <url>        # Copy a remote repo to your computer
```

## Staging & Committing
```bash
git status             # Show status of files
git add <file>         # Stage a specific file
git add .              # Stage all files
git commit -m "msg"    # Commit staged changes with a message
```

## Branching
```bash
git branch             # List branches
git branch <name>      # Create new branch
git checkout <name>    # Switch to a branch
git checkout -b <name> # Create + switch to branch
git merge <branch>     # Merge a branch into current
```
## Pushing & Pulling
```bash
git remote -v             # Show remote URL(s)
git push origin <branch>  # Push changes to GitHub
git pull origin <branch>  # Pull changes from GitHub
```

## Logs & History
```bash
git log                # Show commit history
git show               # Show details of latest commit
git diff               # Show unstaged file changes
```

## Undoing Things
```bash
git restore <file>         # Discard changes in file (safe)
git reset <file>           # Unstage file from commit
git reset --hard HEAD      # Discard all local changes (dangerous)
git revert <commit_hash>   # Undo a commit by creating a new one 
```
