# Understanding Git and Version Control


# What is Git?

Git is a Version Control System (VCS) used to track changes in files and projects over time.

It helps developers to:

- Track code changes
- Save project history
- Collaborate with teams
- Restore previous versions
- Manage multiple branches of development

Git works locally on a developer's machine and can synchronize with platforms like GitHub and GitLab.

---

# Why Version Control is Important

Without version control:

- Code changes may be lost
- Tracking bugs becomes difficult
- Collaboration becomes confusing
- Files can get overwritten
- Reverting mistakes becomes risky

Git solves these problems by maintaining a complete history of project changes.

---

# Core Concepts of Git

## Repository (Repo)

A repository is a project folder tracked by Git.

It contains:

- Project files
- Commit history
- Branch information
- Project configuration

### Types of Repositories

| Type | Description |
|------|-------------|
| Local Repository | Exists on your machine |
| Remote Repository | Hosted online for collaboration |

---

## Working Directory

The working directory is where developers actively modify project files.

---

# Initializing a Git Repository

To initialize a Git repository:

```bash
git init
```

---

# Checking Repository Status

To check tracked, modified, and untracked files:

```bash
git status
```

---

# Staging Area

The staging area prepares files before creating a commit.

## Add All Files

```bash
git add .
```

## Add Specific File

```bash
git add <file-name>
```

---

# Commit

A commit is a saved snapshot of the project at a specific time.

## Create a Commit

```bash
git commit -m "message"
```

### Example

```bash
git commit -m "Added Git documentation"
```

---

# Best Practices for Commit Messages

- Keep messages short and clear
- Describe what was changed
- Use meaningful action words

### Example

```bash
git commit -m "Fixed login bug"
```

---

# Commit History

Git stores a history of all commits.

## View Full History

```bash
git log
```

## View Short History

```bash
git log --oneline
```

---

# Remote Repositories

A remote repository is hosted online and helps teams collaborate efficiently.

---

# Connecting to a Remote Repository

```bash
git remote add origin <repository-url>
```

---

# Push Changes

Uploads local commits to the remote repository.

```bash
git push origin main
```

---

# Pull Changes

Downloads and merges the latest changes from the remote repository.

```bash
git pull origin main
```

---

# Branching in Git

Branches allow developers to work independently without affecting the main codebase.

## Benefits of Branches

- Parallel development
- Safe experimentation
- Independent bug fixing
- Feature development

---

# Main Branch

Common names:

- `main`
- `master`

This branch usually contains stable production-ready code.

---

# Feature Branches

Feature branches are used for developing individual features.

### Naming Examples

```bash
feature/login-page
feature/payment-system
feature/user-profile
```

---

# Merge

Git merge combines changes from one branch into another.

## Example

### Step 1: Switch Branch

```bash
git checkout main
```

### Step 2: Merge Branch

```bash
git merge feature-login
```

---

# Merge Conflicts

A merge conflict occurs when two branches modify the same line differently.

Git requires manual conflict resolution in such cases.

---

# Benefits of Git in Collaborative Development

- Prevents code loss
- Enables teamwork
- Maintains complete project history
- Simplifies collaboration
- Supports safe experimentation

---

# Common Git Commands

| Command | Purpose |
|---------|---------|
| `git init` | Initialize repository |
| `git status` | Check repository status |
| `git add .` | Stage all files |
| `git add <file>` | Stage specific file |
| `git commit -m "msg"` | Create commit |
| `git log` | View commit history |
| `git push` | Upload commits |
| `git pull` | Download latest changes |
| `git branch` | View branches |
| `git checkout <branch>` | Switch branch |
| `git merge <branch>` | Merge branches |

---

# Conclusion

Git is an essential tool for modern software development. It helps developers manage code efficiently, collaborate safely, and maintain a complete history of project changes.

This documentation was created as part of my Week 1 Internship Task to understand Git and Version Control concepts.

---
