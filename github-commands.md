# GitHub Commands Cheat Sheet

A handy reference for Git and GitHub commands, organized by skill level.

---

## Beginner Commands

Basic commands every Git/GitHub user should know.

| Command                                            | Description                         |
| -------------------------------------------------- | ----------------------------------- |
| `git --version`                                    | Check Git version                   |
| `git config --global user.name "Your Name"`        | Set Git username                    |
| `git config --global user.email "you@example.com"` | Set Git email                       |
| `git init`                                         | Initialize a new Git repository     |
| `git clone <repo-url>`                             | Clone a remote repository           |
| `git status`                                       | Check status of changes             |
| `git add <file>`                                   | Stage a file for commit             |
| `git add .`                                        | Stage all changes                   |
| `git commit -m "message"`                          | Commit staged changes               |
| `git log`                                          | Show commit history                 |
| `git diff`                                         | Show unstaged changes               |
| `git branch`                                       | List branches                       |
| `git checkout <branch>`                            | Switch to a branch                  |
| `git checkout -b <branch>`                         | Create and switch to a new branch   |
| `git push`                                         | Push changes to remote repository   |
| `git pull`                                         | Fetch and merge changes from remote |

---

## Intermediate Commands

Commands for better repository management and collaboration.

| Command                           | Description                                    |
| --------------------------------- | ---------------------------------------------- |
| `git remote -v`                   | List remote repositories                       |
| `git fetch`                       | Fetch updates from remote without merging      |
| `git merge <branch>`              | Merge another branch into current branch       |
| `git rebase <branch>`             | Reapply commits on top of another base branch  |
| `git stash`                       | Temporarily save changes                       |
| `git stash pop`                   | Restore stashed changes                        |
| `git reset --hard <commit>`       | Reset current branch to a specific commit      |
| `git rm <file>`                   | Remove a file from repo and stage the deletion |
| `git mv <old> <new>`              | Rename or move a file                          |
| `git log --oneline --graph --all` | Visualize commit history                       |
| `git tag <tag-name>`              | Create a tag for a commit                      |
| `git push origin <branch>`        | Push specific branch to remote                 |
| `git push origin --tags`          | Push tags to remote repository                 |

---

## Advanced Commands

Commands for advanced workflows, troubleshooting, and collaboration.

| Command                                       | Description                                        |
| --------------------------------------------- | -------------------------------------------------- |
| `git cherry-pick <commit>`                    | Apply a commit from another branch                 |
| `git revert <commit>`                         | Undo a commit by creating a new one                |
| `git reflog`                                  | Show history of branch changes (even after resets) |
| `git bisect start`                            | Start a binary search to find a bug commit         |
| `git bisect good <commit>`                    | Mark commit as good                                |
| `git bisect bad <commit>`                     | Mark commit as bad                                 |
| `git blame <file>`                            | Show who changed each line in a file               |
| `git log -p <file>`                           | Show commit history with diffs for a file          |
| `git remote add <name> <url>`                 | Add a new remote repository                        |
| `git push origin <branch> --force`            | Force push changes (use carefully)                 |
| `git checkout <commit>`                       | Checkout a specific commit (detached HEAD)         |
| `git submodule add <repo> <path>`             | Add a submodule to your repo                       |
| `git config --global alias.<alias> <command>` | Create Git command alias                           |

---


