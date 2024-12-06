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
### GitHub Basic Commands

#### 1. **Setting Up Git**
- `git config --global user.name "Your Name"`  
  Sets the name to be used for commits.
- `git config --global user.email "youremail@example.com"`  
  Sets the email address to be used for commits.
- `git config --list`  
  Lists all Git configuration settings.

#### 2. **Initializing a Git Repository**
- `git init`  
  Initializes a new Git repository in the current directory.

#### 3. **Cloning a Repository**
- `git clone <repository_url>`  
  Clones a repository from GitHub to your local machine.

#### 4. **Checking the Status**
- `git status`  
  Displays the status of your working directory, showing tracked and untracked files.

#### 5. **Adding Files**
- `git add <file>`  
  Adds a specific file to the staging area.
- `git add .`  
  Adds all changes in the directory to the staging area.

#### 6. **Committing Changes**
- `git commit -m "Commit message"`  
  Commits the changes in the staging area with a message.

#### 7. **Viewing Commit History**
- `git log`  
  Displays the commit history of the repository.
- `git log --oneline`  
  Displays the commit history in a more concise format.

#### 8. **Pushing Changes**
- `git push`  
  Pushes your commits to the remote repository.
- `git push origin main`  
  Pushes your commits to the `main` branch on the remote repository.

#### 9. **Pulling Changes**
- `git pull`  
  Pulls the latest changes from the remote repository and merges them into your local branch.
- `git pull origin main`  
  Pulls the changes from the `main` branch on the remote repository.

#### 10. **Creating and Switching Branches**
- `git branch <branch_name>`  
  Creates a new branch.
- `git checkout <branch_name>`  
  Switches to an existing branch.
- `git checkout -b <branch_name>`  
  Creates and switches to a new branch.

#### 11. **Merging Branches**
- `git merge <branch_name>`  
  Merges changes from the specified branch into the current branch.

#### 12. **Deleting Branches**
- `git branch -d <branch_name>`  
  Deletes a local branch.
- `git push origin --delete <branch_name>`  
  Deletes a branch from the remote repository.

#### 13. **Undoing Changes**
- `git checkout -- <file>`  
  Discards changes in a file and reverts it to the last committed state.
- `git reset <file>`  
  Unstages a file that was previously added to the staging area.

#### 14. **Remote Repositories**
- `git remote -v`  
  Lists all remotes associated with the repository.
- `git remote add origin <repository_url>`  
  Adds a remote repository URL (typically for pushing to GitHub).
- `git remote remove origin`  
  Removes a remote repository.

#### 15. **Tagging**
- `git tag <tag_name>`  
  Creates a new tag.
- `git push origin <tag_name>`  
  Pushes a tag to the remote repository.
```

