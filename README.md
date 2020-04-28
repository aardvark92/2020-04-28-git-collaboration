# 2020-04-28 Git Collaboration webinar

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

- `git log --oneline --graph --decorate --all`: see a list of commits
