# First-Repo
This is my first repository, I am naking this  with reference to the apna college youtube 1hr video on gtihub.
This repo includes: - 
Introduction
1. Git Introduction
     A version control system that helps to track changes in code, It is free and open source.
2. GitHub Introduction
     Website that allows developers to store and manage their code using Git.
4. Configuring Git & Git Hub
     git --version : to check the latest version of git (run this in Git Bash)
     git config --global user.name "MruneshB" : to declare user name throughout the project (use **global** is you use only 1 git/github account or you can also use **local**
     git config user.email "mruneshbabar7@gmail.com" : to declare user email
     git config list - to check above changes that have been made to git.
5. Working with VS Code
     Use VS Code, to write your code and then deploy it to the GitHub via VS Code terminal.
     Create a folder and on the terminal check for git --version
6. Clone and Status
     Clone: We can copy any project from git using the git clone (copy any https link from the green code button).
            cd (change directory) - after cloning change your directory to project dir
            ls (list files) - gives the names of all files present.
            ls -a (to show hidden files).
7. Types of Status
     Untracked: new files that git does not track yet
     Modified: files that have changed
     Staged: file is ready to commit (done by using add ' ')
     Unmodified: files which are unchanged ( which are commited)
8. Add & Commit commands
     adds new or unchanged files in your working directory to the git staging area.
          git add First-Repo.html
     commit is the record of change
          git commit -m "some message"
          git commit . (to commit all the files)
9. Push command
     push - uploads local repo (system/pc) content to remote repo (GitHub)
          git push origin main (here origin is the name declared for the respective Github repo, we can have any name for it. Also main is for the main branch we are pushing our repo to)
10. Create a new repo in VS Code 
        Use cd.. to get out of the first repo and initialize a new repo using 'git init'
        make a new directory named second repo using mkdir Second-Repo 
        create new files in it
11. Init Command
        used to create a new repo in system/pc using git init
        git remote add origin <link>
        git remote -v
        git branch
        git branch -m main (to rename branch)
12. Workflow 
        1.Create a Github Repo.
        2. Clone your repo to local system.
        3. Input the data, do the required changes.
        4. Add to staging area.
        5. Commit the changes.
        6. Push the repo to origin main (GitHub)
