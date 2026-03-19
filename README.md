# \# version-control-task



**## 1. What is Version Control?**

Version control is a system that records changes to files or sets of files over time so you can recall specific versions later. It allows multiple people to collaborate on a project, track who made what changes, and revert to previous states if something goes wrong.



**## 2. Difference between Git and GitHub**



**-- \*\*Git\*\*** is a distributed version control system that runs on your local machine. It tracks changes in your files and helps you manage different versions of a project.



**-- \*\*GitHub\*\*** is a web-based platform that host Git repositories online. It adds collaboration features like pull requests, issues, project management tools, and it allows you to share your code with others.



**## 3. Three GitHub Alternatives**

1. **\*\*GitLab\*\* -** A web-based DevOps lifecycle tool that provides Git repository manager with CI/CD pipelines, issue tracking and more.
2. **\*\*Bitbucket\*\* -** A Git repository hosting service owned by Atlassian, integrated with Jira and Trello.
3. **\*\*SourceForge\*\* -** An older platform that hosts open-source projects, providing version control via Git, Mercurial, and Subversion.



**## 4. Difference between "Git Fetch" and "Git Pull"**



**--\*\* Git Fetch \*\*** downloads new data from the remote repository (like new branches or commits) but does **\*\*not\*\*** integrate them into your working files. It just updates your local copy of the remote branches.



**--\*\* Git Pull \*\*** does two things: it fetches the latest changes and then immediately merges them into your current branch (like running 'git fetch' followed by 'git merge' ). It updates both your  remote tracking branches and your working directory.



**## 5. Explain git base in simple terms and the command**

Rebasing is a way to move or combine a sequence of commits to a new base commit. think of it as replaying your changes ontop of anither branch. It creates a cleaner, linear history.



**\*\*Command:\*\*** 

```bash

git rebase <branch-name>



**## 6. Explain git cherry-pick in simple terms and the command**

cherry-picking allows you to choose a specific commit from one branch and apply it onto another branch. it's like a single commit and it elsewhere, without moving the whole branch.



**\*\*command\*\***

git cherry-pick <commit-hash>





