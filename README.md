# 2020-04-28 Git Collaboration

- `git clone <URL>`: downloads the repository from the web to our computer
    - Make sure you don't nest this command in another repository
    - just like `git init` do this only once per repository

## Branches

- `git branch <branch_name>`: create a new branch
- `git switch <branch_name>`: move to a branch
    - `git checkout <branch_name`: old way of moving to branch

- `git switch -c <branch_name>`: create and move in one command
    - `git checkout -b <branch_name>`: old way

- `git stash`: temporarily store updates
    - `git stash list`: show list of stashes

## Pull requests (online merge)

- `git push origin <branch_name>`: pushes branch to remote
    - this is where you will create the pull request (online)
    - you merge the PR (and also the branch) by accepting and merging the PR
- don't forget to clean up your branches
- `git fetch --prune`: cleans up the references in your git log
- `git branch -d <branch_name>`: deletes the branch on your local machine
    - it will tell you to move to another branch first, if you're in that branch

## Rebasing or incorporating branch updates

- `git rebase <branch>`: if `branch` is `master`, replay the current branch off of master
    - will auto merge if possible
    - potentially deal with conflicts
