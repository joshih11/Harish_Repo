# Git Distributed Version Control System

## Learning Git/GitHub/GitLab
---

Git/GitHub/GitLab
- Basic Git Explanation
- List of script for the commands
- Git API Interface with the Python Script

Git Commands
- git status


- git init

- git ls -la
>

- git add .
> track your files and changes in Git

- git commit -m "First Commit of Day 12.12.2024"
> save your files in Git

- git log .\file.txt


- git show .\file.txt


- git clone 
> bring repository that is hosted in GitHub/GitLab into a folder in your local machine

- git push
> upload Git commits to a remote repo like, Github/Gitlab from a machine

- git pull
> download Git commit to local machine from a remote repo. It is a opposite of Git

- git merge requests/conflict

- git user (git config --global user.email && git config --global user.name && git config --global --list)



Terminology 
* Directory --> Folder
* Terminal or Command Line --> Interface for Text Commands
* CLI --> Command Line Interface
* cd --> Change Directory
* Code Editor --> Word Processor for writing code
* Repository --> Project or older/place where you project is placed
* Git --> Tracks the changes in your code overtime
* Github --> Website to host your repositories online

---
## Workflow 1
- [] Clone Repository
- [] Create files/Write code/Make changes
- [] Check the status
- [] Commit change
- [] Add change
- [] Push the change


---
## Workflow 2
- [x] 1. Create local directories
- [x] 2. Create files/Write code/Make changes
- [x] 3. Create GitHub repository
- [x] 4. Change directory to local
- [x] 5. Init repository
- [x] 6. Check the status
- [x] 7. Commit change
- [x] 8. Add change
- [x] 9. Push the changes
- [x] 10. Remote add origin

---
## Git Branching
### Master Branch
> *Where all the developers changes are committed and merged, in default/master repository*
- commit #1. --> commit #2. --> commit #3. --> commit #4. --> merge

### Feature Branch
> *Codes will be similar to master and feature branch. But not finalized changes can be only seen in a feature branch*
- commit #3. --> fb_commit #1. --> fb_commit #2. --> merge

### Hot Fix Branch
> *When feature branch merge with master branch has caused problems then a Hot Fix Branch is created*
It is a merge of Feature Branch to Master branch containing limited commits
- commit #4. --> fb_commit #1. --> pre_merge --> final_merge