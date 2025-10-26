# HW3A Solution - Git and Version Control

## Part 1: Repository Cloning

I successfully cloned two repositories:
- **INSY6500**: Course materials and assignments
- **handson-ml3**: Reference materials for machine learning

### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections

### Repository Structure

[Paste your tree output from Part 1 here]

## Part 2: Portfolio Repository Creation

I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes

### Understanding Git Workflow

The three-stage workflow:
1. **Working Directory**: Where I edit files
2. **Staging Area**: Where I prepare commits with `git add`
3. **Repository**: Where commits are permanently stored with `git commit`

## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Repository URL: `https://github.com/<your-username>/py4eda-work`
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)

