# Git

## Basic git commands

- git - lists all commands
- git init - initialises git
- git status - shows the current status
- git diff - shows the differences, that are not yet staged
- git reset --force - reviokes all changes that are staged
- git clone <repo-address> - clone a repo locally
- git push - pushes staged commits
- git remote add origin <repo-address> - adds remote server to a local repo
- git push --set-upstream origin <repo-address>  - adds upstream origin to our current branch
- git push -u origin <repo-address> - adds upstream origin to our current branch

- git branch - lists all local branches
- git branch -a - lists all  local + all remote branches
- git branch -vv - lists all branches and if they are connected to remote branch
- git branch <branch-name> - creates a new branch
- git checkout -b <branch-name> - switches to a branch with branch name <branch-name>

- git branch -d  <branch-name> - deletes branch localy
- git push origin -d <branch-name> - deletes branch remotely

- git fetch - brings the latest changes without merging into current barnch
- git pull --rebase - merges the latest state of repo into the current branch

- git log --oneline - lists all commits in lines
- git cherry-pick <commit-id> - selects only a particular commit from another branch
