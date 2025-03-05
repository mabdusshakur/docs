# Git and GitHub Guide

## Table of Contents

1. [Setting Up Git](#setting-up-git)
2. [Basic Git Commands](#basic-git-commands)
3. [Branching](#branching)
4. [Pushing to GitHub](#pushing-to-github)
5. [Merging Branches](#merging-branches)

## Setting Up Git

1. **Install Git**: Download and install Git from [git-scm.com](https://git-scm.com/).
2. **Configure Git**:
   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

## Basic Git Commands

1. **Initialize a Repository**:
   ```sh
   git init
   ```
2. **Clone a Repository**:
   ```sh
   git clone https://github.com/username/repository.git
   ```
3. **Check Status**:
   ```sh
   git status
   ```
4. **Add Changes**:
   ```sh
   git add .
   ```
5. **Commit Changes**:
   ```sh
   git commit -m "Commit message"
   ```

## Branching

1. **Create a New Branch**:
   ```sh
   git branch new-branch
   ```
2. **Switch to a Branch**:
   ```sh
   git checkout new-branch
   ```
3. **Create and Switch to a New Branch**:
   ```sh
   git checkout -b new-branch
   ```
4. **List Branches**:
   ```sh
   git branch
   ```

## Pushing to GitHub

1. **Add Remote**:
   ```sh
   git remote add origin https://github.com/username/repository.git
   ```
2. **Push to Remote Repository**:
   ```sh
   git push -u origin main
   ```
   > **Note**: If your branch name is `master`, rename it to `main` before pushing:
   ```sh
   git branch -M main
   ```

3. **Push a Branch**:
   ```sh
   git push origin branch-name
   ```

## Merging Branches

1. **Merge a Branch into Current Branch**:
   ```sh
   git merge branch-name
   ```
2. **Resolve Merge Conflicts**: Edit the conflicted files and then:
   ```sh
   git add .
   git commit -m "Resolved merge conflicts"
   ```

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
