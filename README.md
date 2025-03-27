# Stepwise Git Installation Guide  

Git is a distributed version control system that helps developers manage code efficiently.  
This guide provides step-by-step instructions for installing Git and setting up a local repository.  

## Installation Steps  

### 1. Download Git  
- Visit [Git Official Website](https://git-scm.com/)  
- Click on "Download" and select the appropriate version for your OS.  

### 2. Run the Installer  
- Locate the downloaded `.exe` file and double-click to run it.  

### 3. Setup Configuration  
- Choose the installation directory (default is recommended).  

### 4. Select Code Editor  
- Select your default code editor (e.g., Visual Studio Code) to integrate with Git.  

### 5. Continue Installation  
- Keep the default settings and click "Next" until the "Install" button appears.  

### 6. Complete Installation  
- Click "Install" and wait for the setup to finish.  
- Once done, launch **Git Bash** to start using Git.  

### 7. Verify Installation  
- Open **Command Prompt / Terminal** and run:  
  ```sh
  git --version

# Setting Up a Local and Remote Repository in Git  

## Local Repository in Git  

A **local repository** refers to the version of your project that resides on your own computer.  
When you initialize a Git repository in a directory (using `git init`), it sets up a local repository where Git:  
- Tracks changes  
- Manages versions of files  
- Stores commit history  

The following steps outline the process of creating a local repository in Git:  

### 1. Initialize Git Repository  
```sh
git init
```
### 2. This stages the file README.md for the next commit 
```sh
git add README.md 
```
### 3.  This saves the staged changes into Git’s history
```sh
git commit -m "first commit"
```
### 4.  Renames the current branch to “main”
```sh
git branch -M main
```
### 5. This links your local repository to a remote repository(like github) 
```sh
git remote add origin "link of repository"
```
### 6. This uploads (pushes) the commits from your local repository to the remote 
```sh
git push -u origin main
```
