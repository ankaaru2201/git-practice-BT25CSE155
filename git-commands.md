# Git Commands Practice Record

## 1. Git Configuration

git config --global user.name "Ankit Kumar"
Sets the Git username.

git config --global user.email "email"
Sets the Git email address.

## 2. Repository Management

git init
Initializes a new Git repository.

git clone URL
Clones an existing remote repository.

git status
Displays the current repository status.

## 3. File Management

git add filename
Adds a specific file to the staging area.

git add .
Stages all modified and new files.

git commit -m "message"
Saves staged changes with a commit message.

## 4. Branching

git branch
Lists all local branches.

git branch branch-name
Creates a new branch.

git switch branch-name
Switches to another branch.

git switch -c branch-name
Creates and switches to a new branch.

## 5. Merging

git merge branch-name
Merges another branch into the current branch.

## 6. Remote Repository

git remote -v
Displays remote repository URLs.

git push origin main
Uploads local commits to GitHub.

git pull origin main
Fetches and integrates remote changes.

git fetch
Downloads remote changes without merging.

## 7. History

git log
Displays commit history.

git log --oneline
Displays compact commit history.

git diff
Shows changes between working files and the index.

git show
Displays details of a commit.

