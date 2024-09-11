# Git-Work-

## 1. Creating a New Git Repository and Pushing It to GitHub

```sh
# Initialize a new Git repository locally
git init

# Add all files in the current directory to the Git repository
git add .

# Commit the files with a message
git commit -m "Initial commit"

# Add your GitHub repository as the remote origin
git remote add origin https://github.com/your-username/your-repo-name.git

# Push the commit to the master branch (or main branch) on GitHub
git push -u origin master

```

## Pushing Changes After Each Update

```sh
# Add changes to the staging area
git add .

# Commit the changes with a message
git commit -m "Your commit message describing the change"

# Push the changes to the GitHub repository
git push

```
