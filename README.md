# Git and GitHub Workshop

Welcome to the Git and GitHub workshop! This guide will walk you through the basic commands you'll need to start using Git and GitHub effectively.

![Git and GitHub Work Process](https://raw.githubusercontent.com/Ahmadjajja/SMIT-Web-and-Mobile-Batch7/main/Git%20%26%20Github%20Class%203-4/git%20%26%20github%20work%20process.webp)


## Step-by-Step Guide

### 1. Install Git

- Download Git from [here](https://git-scm.com/downloads) and install it.

### 2. Verify Git Installation

- Open the command prompt (cmd) and type the following command to check if Git is installed:
  ```sh
  git
  ```
### 3. Configure Git

- Open the command prompt as an administrator.
- Set your username:
  ```sh
  git config --global user.name "your name"
  ```
- Set your email:
  ```sh
  git config --global user.email "your email"
  ```
### 4. Clone a Repository

- Download code from GitHub using:
  ```sh
  git clone URL_OF_REPOSITORY
  ```
### 5. Connect Local Repository to Remote Repository

- If you have an existing local repository and want to connect it to a new GitHub repository:
  ```sh
  git remote add origin URL_OF_REPOSITORY
  ```
- Verify the new remote URL:
  ```sh
  git remote -v
  ```
### 6. Pull Changes from GitHub

- Bring changes to your local repository from GitHub using:
  ```sh
  git pull
  ```
### 7.Check Git Status

- Check the status of your repository:
  ```sh
  git status
  ```
### 8. Add Files to Staging Area

- Add all files to the staging area::
  ```sh
  git add .
  ```
### 9. Commit Changes

- Commit your changes with a message:
  ```sh
  git commit -m "commit message"
  ```
### 10. Push Changes to GitHub

- Push your code to the remote repository:
  ```sh
  git push origin main
  ```

## Concepts
### Untracked Area
- __Untracked Area:__ When you create or modify files in your local repository, they are initially untracked by Git. This means Git is not monitoring these files for changes.
### Staging Area (Tracking Area)
- __Staging Area (Tracking Area):__ Also known as the index, this is where you place files that you want to be included in your next commit. When you run git add, the files move from the untracked area to the staging area. This is like preparing your files for a snapshot.
### Commit Area
- __Commit Area:__ When you commit your changes, the files in the staging area are moved to the commit area. A commit is a snapshot of your repository at a specific point in time. It includes all the changes that were in the staging area.

## Additional Commands for Beginners
### Create a New Branch
- Create and switch to a new branch:
  ```sh
  git checkout -b new-branch-name
  ```
### Switch Branches
- Switch to an existing branch:
  ```sh
  git checkout branch-name
  ```
### Merge Branches
- Merge changes from another branch into your current branch:
  ```sh
  git merge branch-name
  ```
### View Commit History
- View the commit history of the repository:
  ```sh
  git log
  ```
### Remove a File from Staging Area

- Unstage a file (remove it from the staging area):
  ```sh
  git reset HEAD file-name
  ```
### Delete a Branch

- Delete a branch:
  ```sh
  git branch -d branch-name
  ```
