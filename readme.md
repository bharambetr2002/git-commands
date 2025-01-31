# Git Commands Cheat Sheet

## 1. Core Commands
- `git init`: Initialize a new Git repository.
- `git clone`: Clone a repository into a new directory.
- `git add`: Add files to the staging area.
- `git commit`: Record changes to the repository.
- `git status`: Show the working directory status.
- `git diff`: Show differences between commits, branches, or files.
- `git checkout`: Switch branches or restore files.
- `git reset`: Unstage changes or reset commits.
- `git log`: Show commit logs.
- `git show`: Show information about a commit.
- `git tag`: Create, list, or delete tags.
- `git push`: Push changes to a remote repository.
- `git pull`: Fetch and merge changes from a remote repository.

## 2. Branching Commands
- `git branch`: List, create, or delete branches.
- `git checkout -b`: Create and switch to a new branch.
- `git merge`: Merge branches.
- `git rebase`: Reapply commits on top of another base.
- `git branch --set-upstream-to`: Set upstream tracking branch.
- `git branch --unset-upstream`: Remove upstream tracking branch.
- `git cherry-pick`: Apply the changes from a specific commit.

## 3. Merging Commands
- `git merge`: Merge branches.
- `git rebase`: Reapply commits on top of another base.

## 4. Stashing Commands
- `git stash`: Save changes temporarily.
- `git stash pop`: Apply and remove the most recent stash.
- `git stash list`: List all stashes.
- `git stash apply`: Apply a specific stash.
- `git stash drop`: Remove a specific stash.

## 5. Remote Commands
- `git remote`: Manage remote repositories.
- `git remote add`: Add a new remote.
- `git remote remove`: Remove a remote.
- `git fetch`: Download changes from a remote repository.
- `git pull`: Fetch and merge changes from a remote.
- `git push`: Push changes to a remote.
- `git clone --mirror`: Create a mirror of a repository.

## 6. Configuration Commands
- `git config`: Get and set configuration variables.
- `git global config`: Configure Git globally.
- `git reset config`: Reset configuration values.

## 7. Plumbing Commands
- `git cat-file`: Provide content or type of an object.
- `git checkout-index`: Copy files from the index.
- `git commit-tree`: Create a new commit object.
- `git diff-tree`: Show changes between tree objects.
- `git for-each-ref`: Display references.
- `git hash-object`: Compute object ID and create a blob.
- `git ls-files`: Show tracked files.
- `git ls-remote`: List references in a remote repository.
- `git merge-tree`: Show three-way merge results.
- `git read-tree`: Read a tree object.
- `git rev-parse`: Parse revision identifiers.
- `git show-branch`: Show branches and their commits.
- `git show-ref`: List references.
- `git symbolic-ref`: Read and modify symbolic refs.
- `git tag --list`: List tags.
- `git update-ref`: Update a reference.

## 8. Porcelain Commands
- `git blame`: Show who changed what and when.
- `git bisect`: Find the commit that introduced a bug.
- `git checkout`: Switch branches or restore files.
- `git commit`: Record changes to the repository.
- `git diff`: Show differences between commits or files.
- `git fetch`: Download changes from a remote.
- `git grep`: Search for patterns in tracked files.
- `git log`: Show commit logs.
- `git merge`: Merge branches.
- `git push`: Push changes to a remote.
- `git rebase`: Reapply commits on top of another base.
- `git reset`: Unstage changes or reset commits.
- `git show`: Show information about a commit.
- `git tag`: Create, list, or delete tags.

## 9. Alias Commands
- `git config --global alias.<alias> <command>`: Create a custom Git alias.

## 10. Hook Commands
- `git config --local core.hooksPath <path>`: Set a custom path for Git hooks.

