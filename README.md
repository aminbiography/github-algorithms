# GitHub README.md Markdown Nesting
 
![Example Image](https://i.pinimg.com/736x/06/2a/e4/062ae4ca969aa0ec84af0823d3f99ed1.jpg)
![Example Image](https://i.pinimg.com/736x/35/52/f4/3552f431827a8d12a6f5034285d25320.jpg)
[Learn More](https://github.com/)

# abcdefghijklmnopqrstuvwxyz

## abcdefghijklmnopqrstuvwxyz
- abcdefghijklmnopqrstuvwxyz **abcdefghijklmnopqrstuvwxyz** abcdefghijklmnopqrstuvwxyz.
- abcdefghijklmnopqrstuvwxyz:
  - abcdefghijklmnopqrstuvwxyz
  - abcdefghijklmnopqrstuvwxyz
  - abcdefghijklmnopqrstuvwxyz
- abcdefghijklmnopqrstuvwxyz:
  - abcdefghijklmnopqrstuvwxyz **abcdefghijklmnopqrstuvwxyz** (e.g.,abcdefghijklmnopqrstuvwxyz)
     - abcdefghijklmnopqrstuvwxyz
  - Improving security monitoring

**abcdefghijklmnopqrstuvwxyz**

```
               abcdefghijklmnopqrstuvwxyz 
```
****abcdefghijklmnopqrstuvwxyz****
---
#### abcdefghijklmnopqrstuvwxyz
---

![Example Image](https://via.placeholder.com/150)
[Learn More](https://example.com)

# GitHub README.md Markdown Nesting Inputs 

```
# abcdefghijklmnopqrstuvwxyz

## abcdefghijklmnopqrstuvwxyz
- abcdefghijklmnopqrstuvwxyz **abcdefghijklmnopqrstuvwxyz** abcdefghijklmnopqrstuvwxyz.
- abcdefghijklmnopqrstuvwxyz:
  - abcdefghijklmnopqrstuvwxyz
  - abcdefghijklmnopqrstuvwxyz
  - abcdefghijklmnopqrstuvwxyz
- abcdefghijklmnopqrstuvwxyz:
  - abcdefghijklmnopqrstuvwxyz **abcdefghijklmnopqrstuvwxyz** (e.g.,abcdefghijklmnopqrstuvwxyz)
     - abcdefghijklmnopqrstuvwxyz
  - Improving security monitoring

**abcdefghijklmnopqrstuvwxyz**

****abcdefghijklmnopqrstuvwxyz****
---
#### abcdefghijklmnopqrstuvwxyz
---

![Example Image](https://via.placeholder.com/150)
[Learn More](https://example.com)
```


# github-algorithms in youtube

https://www.youtube.com/GitHub

<h1>Create a new repository using the command lines</h1>

```
cd /path/to/your/folder
```
```
echo "# html5-css3-fundamentals" >> index.html             \\\ Optional 
```
```
git init
```
```
git add .
```
```
git commit -m "first commit"
```
```
git branch -M main
```
```
git remote add origin https://github.com/username/repository-name.git
```
```
git push -u origin main
```
<h1>Push an existing repository using the command lines</h1>

```
git init
```
```
git add .
```
```
git commit -m "Add existing project files to Git"
```
```
git remote add origin https://github.com/username/repository-name.git
```
```
git push -u
```
or
```
git pull
```
or
```
git push -v
```
or
```
-f origin master
```

<h1>Essential GitHub Commands</h1>

```
git init                                # Initializes a new Git repository in the current directory.
git clone <repository_url>              # Clones an existing remote repository to your local machine.
git add <file>                          # Stages the specified file(s) for the next commit.
git commit -m "message"                 # Commits the staged changes with a descriptive message.
git status                              # Shows the status of the working directory and staging area.
git branch                              # Lists all branches, and the current active branch.
git branch <branch_name>                # Creates a new branch.
git checkout <branch_name>              # Switches to the specified branch.
git merge <branch_name>                 # Merges changes from the specified branch into the current branch.
git pull <remote> <branch_name>         # Fetches and merges changes from a remote repository into the current branch.
git push <remote> <branch_name>         # Pushes local commits to the remote repository.
git remote add origin <url>             # Adds a new remote repository URL (usually origin).
git remote -v                           # Lists all configured remotes for the repository.
git fetch <remote>                      # Fetches updates from the remote repository without merging.
git log                                 # Displays the commit history for the current branch.
git log --oneline                       # Shows the commit history in a compact, single-line format.
git reset <file>                        # Unstages the specified file(s).
git reset --hard                        # Resets the working directory and staging area to the last commit.
git revert <commit_id>                  # Creates a new commit that undoes changes from the specified commit.
git rm <file>                           # Removes the file from both the working directory and staging area.
git mv <old_name> <new_name>            # Renames a file in the repository.
git tag <tag_name>                      # Tags a commit with a specific label.
git diff                                # Shows the changes between the working directory and the staging area.
git diff --cached                       # Shows the changes between the staging area and the last commit.
git stash                               # Temporarily saves changes that are not yet ready for committing.
git stash pop                           # Restores the most recent stashed changes.
git bisect <command>                    # Helps find the commit that introduced a bug using binary search.
git cherry-pick <commit_id>             # Applies the changes from a specific commit to the current branch.
git blame <file>                        # Shows who modified each line of a file and when.
git reflog                              # Shows the history of the references and their changes.
git submodule update --init             # Initializes and updates submodules in a repository.
git push --force                        # Forcefully pushes changes to a remote repository, overwriting the remote history (use with caution).
git pull --rebase                       # Pulls changes from the remote and applies your local commits on top.
git fetch --all                         # Fetches changes from all remotes.
git merge --no-ff <branch_name>         # Merges a branch with a merge commit, even if the merge is a fast-forward.
git push origin --delete <branch_name>  # Deletes a remote branch from the origin.
git branch -d <branch_name>             # Deletes a local branch (safe to use only if it has been fully merged).
git branch -D <branch_name>             # Forces deletion of a local branch, even if it hasn’t been merged.
git remote prune <remote_name>          # Removes remote-tracking branches that no longer exist on the remote.
git diff --staged                       # Shows the differences between staged changes and the last commit.
git tag -a <tag_name> -m "message"      # Creates an annotated tag with a message.
git tag -d <tag_name>                   # Deletes a local tag.
git push origin <tag_name>              # Pushes a tag to the remote repository.
git push origin --tags                  # Pushes all tags to the remote repository.
git pull --no-commit                    # Pulls changes from the remote but doesn’t automatically commit them.
git clean -fd                           # Removes untracked files and directories from the working directory.
git cherry-pick --abort                 # Aborts a cherry-pick operation if conflicts arise.
git worktree add <path> <branch>        # Adds a new working directory for a specific branch.
git submodule update --recursive        # Updates submodules recursively, including nested submodules.
git ls-files                            # Lists all tracked files in the repository.
git commit --amend                      # Edits the last commit without changing the commit message.
git fsck                                # Runs a file system check on the repository to identify issues.
git gc                                  # Runs garbage collection to optimize the repository.
git svn clone <svn_repo_url>            # Clones a repository from Subversion (SVN) to Git.
git svn fetch                           # Fetches changes from a Subversion repository.
git svn rebase                          # Rebases changes with a Subversion repository.
git log --graph                         # Visualizes the commit history in a graphical format.
git log --oneline --graph               # Shows a simplified graph of commits in a one-line format.
git log --author="Author Name"          # Filters commits by a specific author.
git shortlog                            # Displays a summary of commit history, grouped by author.
git rev-parse <commit_hash>             # Retrieves the full commit hash for a given commit reference.
git show <commit_hash>                  # Displays detailed information about a specific commit.
git reset --soft <commit_hash>          # Resets the current branch to a previous commit but keeps changes staged.
git reset --mixed <commit_hash>         # Resets the current branch to a previous commit and unstages the changes.
git reset --hard <commit_hash>          # Resets the current branch to a previous commit, discarding all changes.
git diff <commit_hash> <file>           # Shows the difference between a commit and the current version of a file.
git ls-remote <repository_url>          # Lists references in a remote repository.
git remote set-url origin <new_url>     # Changes the URL of the remote repository.
git merge --abort                       # Aborts a merge operation if there are conflicts.
git commit --no-edit                    # Commits changes without modifying the commit message.
git pull --rebase=interactive           # Rebases interactively when pulling changes.
git stash list                          # Lists all stashed changes.
```
more
```
git config --global user.name "Your Name"               # Sets the global Git username.
git config --global user.email "you@example.com"        # Sets the global Git email address.
git config --list                                       # Displays all Git configuration settings.
git archive --format=tar <branch_name> > archive.tar    # Creates a tarball of a specific branch.
git reflog expire --expire=now --all=now                # Cleans up the reflog (use with caution).
git config --global core.editor "editor_name"           # Sets the default text editor for Git commit messages.
git diff <commit_hash1> <commit_hash2>                  # Shows the difference between two commits.
git update-index --assume-unchanged <file>              # Marks a file as unchanged, useful for ignoring local changes temporarily.
git update-index --no-assume-unchanged <file>           # Stops assuming a file is unchanged.
git submodule add <repository_url> <path>               # Adds a new submodule to the repository.
```

