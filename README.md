# ☕ Git & GitHub Practice

Welcome to my Git and GitHub learning repository! 🚀

I created this repository while learning Git and GitHub from **Chai aur Code**. The goal is to understand version control, practice Git commands, and learn how to manage projects using GitHub.

## 📚 What I Learned

### 1. Introduction to Git
- What is Git?
- Why do we need version control?
- Difference between Git and GitHub
- Installing and configuring Git
- Checking Git version

### 2. Git Configuration
```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git config --list
```

### 3. Repository Management
- Initializing a repository
- Checking repository status
- Staging and committing changes
- Viewing commit history

```bash
git init
git status
git add .
git commit -m "Initial commit"
git log
```

### 4. Branching and Merging
Branches allow developers to work on different features without directly modifying the main branch.

```bash
git branch
git branch feature-branch
git switch feature-branch
git switch -c new-feature
git merge feature-branch
```

**Branch management commands:**

```bash
git branch -m old-name new-name
git branch -d branch-name
git branch -D branch-name
```

### 5. Working with GitHub
- Creating a GitHub account and repository
- Connecting a local repository to GitHub
- Adding a remote repository
- Pushing local changes to GitHub
- Cloning remote repositories
- Pulling changes from GitHub

```bash
git remote -v
git remote add origin <repository-url>
git push -u origin main
git pull origin main
git clone <repository-url>
```

### 6. Undoing Changes
- Understanding the difference between working directory, staging area, and repository
- Unstaging files
- Discarding local changes
- Understanding merge conflicts and aborting a merge

```bash
git restore <file-name>
git restore --staged <file-name>
git merge --abort
```

> **Note:** Commands such as `git restore` can discard changes. Always check your working tree before running commands that may remove work.

### 7. Working with Remote Branches
- Listing remote repositories
- Fetching changes
- Pushing branches to GitHub
- Setting upstream branches

```bash
git fetch origin
git push -u origin <branch-name>
git branch -a
```

## 🛠️ Tools Used

- **Git:** Distributed version control system
- **GitHub:** Platform for hosting Git repositories
- **Visual Studio Code:** Code editor
- **PowerShell:** Command-line terminal
- **Windows:** Development environment

## 🎯 Learning Goals

- Build a strong foundation in Git and GitHub.
- Understand the complete Git workflow.
- Practice branching, merging, and remote repositories.
- Learn to collaborate on software projects.
- Apply version control in Java and Spring Boot projects.

## 📈 My Learning Journey

This repository represents my hands-on practice as I continue learning software development. I will keep updating it with examples, commands, and concepts as I progress.

## 🙏 Learning Resource

**Chai aur Code**

YouTube: https://www.youtube.com/@chaiaurcode

## 👨‍💻 About Me

I am a Computer Science Engineering graduate focused on becoming a Java Backend Developer. I am currently strengthening my skills in Java, SQL, Git, GitHub, and Spring Boot.

🔗 GitHub: https://github.com/Samadhan-Sargar-1210

---

⭐ If you find this repository useful, feel free to explore it and learn along with me.

**Keep Learning. Keep Building. Keep Growing.** 🚀
