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
  + git commit: permanently stores file changes from the staging area in the repository
  + git log: shows a list of all previous commits
  
 ## Git Backtrack
 You can use these skills to undo changes made to your Git project
  + git checkout HEAD filename: Discards changes in the working directory
  + git reset HEAD filename: Unstages file changes in the staging area
  + git reset commit_SHA: Reset to a previous commit in your commit history
