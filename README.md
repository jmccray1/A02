# A02 - GitHub and WebStorm Tutorial

## Introduction
This tutorial will guide you through using Git and GitHub with WebStorm. It covers setting up a repository, pushing code, and understanding basic Git operations.

## Prerequisites
- A GitHub account
- Git installed on your local machine: [Download Git](https://git-scm.com/downloads)
- WebStorm IDE: [Download WebStorm](https://www.jetbrains.com/webstorm/download/)

## Step-by-Step Guide

### 1. Setting up Git
1. Download and install Git from the [Git Downloads page](https://git-scm.com/downloads).
2. Configure Git with your username and email:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
## Basic Git Commands
git clone <repository-url>: Clone a repository.
git status: Check the status of your local repository.
git add <file>: Stage changes.
git commit -m "message": Commit changes.
git push origin main: Push changes to the main branch.

### Glossary
### Branch: 
A separate line of development in a Repository that allows you to work on different features or versions independently.
#### Clone: 
Creating a local copy of a remote Repository on your machine, typically using the git clone command.
### Commit: 
A snapshot of changes made to files in a Repository. Each Commit has a unique ID and serves as a save point.
### Fetch: 
A command that retrieves updates from a Remote Repository without merging them into your current branch. This allows you to see changes before you apply them.
### GIT: 
A version control system used for tracking changes in files and coordinating work among multiple developers.
### GitHub: 
A cloud-based platform for hosting GIT Repositories and enabling collaboration among developers.
#### Merge: 
Combining changes from one Branch into another Branch to update the content.
#### Merge Conflict: 
An issue that occurs when changes in two Branches cannot be automatically merged by GIT due to conflicting edits in the same part of a file.
#### Push:
Sending local Commits to a Remote Repository, thereby updating it with your changes.
#### Pull:
A command that downloads changes from a Remote Repository and merges them into your current Branch.
#### Remote: 
A version of a Repository hosted on a server, such as on GitHub, which can be accessed from different locations.
#### Repository: 
A storage location for a project, containing files, directories, and the history of changes tracked by GIT.
