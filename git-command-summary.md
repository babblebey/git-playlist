## Git Command summary from NetNinja's Youtube tutorial

#### Single Git Commands
Initialize a git repo in the current directory

    git init add --username
    git init add --email

Add all untracked changed files to staging, ready to be committed

    git add -A

Commit with a message

    git commit -m "commit-message-here"

Review your commit history or checkpoints in time log, (gives you the commit address for reference):

    git log --oneline

Switch to a previous commit to review code from that checkpoint

    git checkout <your-commit-id-here>

Sync a remote repository to local repository with automatic alias assigned called "origin"

    git remote add <alias-name> <your remote repository link comes here>

Push from local branch "master" (newly created Github repo/Git version 2.29+, use - "main") up to remote branch "origin" (where 'origin' is set as an alias to the remote repository)

    git push origin master

Pull from remote branch "origin" down to local branch "master" (newly created Github repo/Git version 2.29+, use - "main")

    git pull origin master

Create a new branch to manage a side hustle in project

    git branch <your-new-branch-name>

View all branches in your repository, also marks the branch you are working on with *

    git branch -a

Switch to a branch to work in it

    git checkout <your-branch-name-here>

Create a new branch and switch to it same time (Shortcut)

    git checkout -b <your-new-branch-name>

Delete a branch

    git checkout master
    // Deleting local branch
    git branch -D <branch name to be deleted>
