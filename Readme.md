# Git Practice Repository

## Overview

This repository serves as a comprehensive learning resource for understanding Git version control fundamentals and advanced workflows. It is designed to help developers practice essential Git commands and gain hands-on experience with real-world scenarios, particularly in handling merge conflicts.

## Project Purpose

The primary objective of this project is to provide a practical environment for:
- Mastering Git command-line operations
- Understanding branching and merging workflows
- Learning conflict resolution strategies
- Practicing collaborative development patterns
- Building proficiency with version control best practices

## Project Structure

```
git-practice/
├── index.html      # Main HTML file for the web interface
├── main.js         # JavaScript functionality and interactivity
├── style.css       # CSS styling and layout
├── dummy.txt       # Sample text file for practice
└── Readme.md       # Project documentation
```

## Key Learning Areas

### 1. Git Fundamentals
- Repository initialization
- Staging and committing changes
- Viewing commit history
- Understanding the working directory, staging area, and repository

### 2. Branching & Merging
- Creating and switching branches
- Fast-forward merges
- Three-way merges
- Branch management and cleanup

### 3. Merge Conflict Resolution
- Understanding when conflicts occur
- Identifying conflict markers
- Manual conflict resolution techniques
- Using Git tools for conflict resolution
- Best practices for preventing conflicts

### 4. Remote Repository Management
- Adding remote repositories
- Fetching and pulling changes
- Pushing commits to remote branches
- Managing multiple remotes

## Getting Started

### Prerequisites
- Git installed on your system
- Basic understanding of command-line interface
- A text editor or IDE

### Initial Setup
```bash
# Clone the repository
git clone https://github.com/rubeshscoby/git-practice.git

# Navigate to the project
cd git-practice

# View project files
ls -la
```

### Running the Project
1. Open `index.html` in your web browser to view the interface
2. Inspect `main.js` and `style.css` to understand the structure
3. Begin practicing Git commands on this repository

## Common Git Commands to Practice

```bash
# Status and logging
git status
git log
git log --oneline --graph --all

# Branching
git branch
git branch <branch-name>
git checkout -b <branch-name>
git switch <branch-name>

# Committing changes
git add <file>
git add .
git commit -m "descriptive message"

# Merging
git merge <branch-name>
git merge --no-ff <branch-name>

# Handling conflicts
git diff
git mergetool
```

## Merge Conflict Practice

This repository is ideal for practicing merge conflict resolution. Follow these steps:

1. Create a feature branch: `git checkout -b feature/new-feature`
2. Make changes to the same files from different branches
3. Attempt to merge branches to trigger conflicts
4. Resolve conflicts using your preferred method
5. Complete the merge and commit changes

## Recommended Workflow

1. **Create a new branch** for each feature or practice scenario
2. **Make isolated changes** on your branch
3. **Commit regularly** with meaningful messages
4. **Push to remote** to backup your work
5. **Create pull requests** to practice code review workflows
6. **Resolve conflicts** when merging different branches

## Best Practices

- Use descriptive branch names: `feature/`, `bugfix/`, `hotfix/`, `docs/`
- Write meaningful commit messages
- Commit frequently with logical, atomic changes
- Keep branches focused on single features or fixes
- Delete merged branches to keep the repository clean
- Always pull before pushing to stay updated

## Resources for Further Learning

- [Git Official Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- [Interactive Git Visualization](https://learngitbranching.js.org)

## Contributing & Practice

This is a personal practice repository. Feel free to:
- Experiment with different Git workflows
- Create and delete branches freely
- Force push to explore dangerous operations (safely)
- Rebase and squash commits
- Use all Git features without concerns

## Notes

- This repository is intended for learning and experimentation
- It's safe to make mistakes here and learn from them
- Consider this your sandbox for Git mastery

---

**Last Updated:** February 12, 2026  
**Repository:** [rubeshscoby/git-practice](https://github.com/rubeshscoby/git-practice)
