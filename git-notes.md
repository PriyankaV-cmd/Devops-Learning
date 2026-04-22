Git – Version Control System
Git is a distributed version control system.
It helps developers:

• Track code changes 
• Collaborate with teams
• Maintain code history
• Roll back code

Example:
Imagine 5 developers working on the same project.
Without Git, Files will constantly overwrite each other.
Git solves this.

#Git Architecture

Git has three important areas:
1. Working Directory
   Where you edit files.
2. Staging Area
   Temporary area where changes are prepared before committing.
3. Repository
   Where Git stores committed versions.
   Flow:
   Working Directory -> git add -> Staging Area -> git commit  -> Repository

#Installing Git

Mac - brew install git

Ubuntu - sudo apt install git

Check installation: git --version

#Git Configuration

Set username:
git config --global user.name "Your Name"

Set email:
git config --global user.email "your@email.com"

Check config:
git config --list

#Creating Git Repository

Initialize repository:
git init

Check status:
git status

Add files:
git add file.txt

Add all files:
git add .

Commit:
git commit -m "Initial commit/your comments"

#Git Branching:
Branching allows multiple developers to work independently.

Default branch:
main / master

Create branch:
git branch feature-login

Switch branch:
git checkout feature-login

Create + switch:
git checkout -b feature-login

Merge branch:
git merge feature-login

#Git Merge vs Rebase
Merge:
Combines histories with a merge commit.
Safe and commonly used.

Rebase:
Rewrites history to create a linear commit history.
Cleaner but risky if used incorrectly.

#GitHub

GitHub is a cloud platform for hosting Git repositories.
It enables:

• Collaboration 

• Code sharing

• Pull requests

• CI/CD pipelines

• Issue tracking

#Connecting Git to GitHub:

Create repository on GitHub.

Then run:
git remote add origin https://github.com/user/repo.git

Push code:
git push origin main

**GitHub Workflow**

Typical workflow:

Developer creates branch
↓
Writes code
↓
Push to GitHub
↓
Create Pull Request
↓
Code review
↓
Merge into main

**Pull Requests**

Pull request allows:

• Code review
• Discussion
• Approval before merging

Steps:
1 Create branch 

2 Push code 

3 Create PR 

4 Review 

5 Merge

**Forking**

Fork means copying someone else's repository to your account.
Used in open source contributions.

Flow:

Fork repo
↓
Clone repo
↓
Make changes
↓
Create PR (done)


