# GitTutor
This repo is for 
> Git commands.

[Basic writing and formatting git docs](https://help.github.com/articles/basic-writing-and-formatting-syntax/). :+1:

## Git Basics
- Git is the industry-standard version control system for web developers.
- Use git commands to help keep track of changes made to a project:
  + git init: creates a new Git repository
  + git status: inspects the contents of the working directory and staging area
  + git add: adds files from the working directory to staging area
    git add filename1 filename2 ...: add multiple files to staging area
  + git diff: show the different between the working directory and the staging area
  + git show commit_SHA: show what changes in a specific commit
  + git commit: permanently stores file changes from the staging area in the repository
  + git log: shows a list of all previous commits
  
 ## Git Backtrack
 You can use these skills to undo changes made to your Git project
  + git checkout HEAD filename: Discards changes in the working directory
  + git reset HEAD filename: Unstages file changes in the staging area
  + git reset commit_SHA: Reset to a previous commit in your commit history

## Git Branching
Git branching allows users to experiment with different versions of a project by checking out separate branches to work on.
The following commands are useful in the Git branch workflow.
- git branch: Lists all Git project's branches
- git branch branch_name: Creates a new branch
- git checkout branch_name: Used to switch from one branch to another
- git merge branch_name: Used to merge changes from branch_name to current branch
- git branch -d  branch_name: Deletes the branch specified

## Git Teamwork
- A remote is a Git repository that lives outside your Git project folder. Remotes can live on the web, on a shared network or even in a seperate folder on you local computer.
- The Git Collaborative Workflow are steps that enables smooth project development when multiple collaborators are working on the same Git project.
- The following commands help to deal with remote:
  + git clone: Creates a local copy of a remote
  + git remote -v: Lists a Git project's remotes
  + git fetch: Fetches work from the remote into the local copy
  + git merge origin/master: Merges orgin/master into your local branch
  + git push origin <branch_name>: Pushes a local branch to the origin remote

## Git Colaborative workflow
1. Fetch and merge changes from the remote
2. Create a branch to work on a new project feature
3. Develop the feature on your branch and commit your work
4. Fetch and merge from the remote again (in case new commits were made while you were working)
5. Push your branch up to the remote for review
6. Merge your branch to master
7. Delete your feature branch
