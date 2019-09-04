---
description: Week 2 - In class activities
---

# Week 2 in class

* Slides: [https://docs.google.com/presentation/d/1Fc90t3sZUe5S7ry7VU3iTLym-GagFJof51LVt9wAKg0/edit?usp=sharing](https://docs.google.com/presentation/d/1Fc90t3sZUe5S7ry7VU3iTLym-GagFJof51LVt9wAKg0/edit?usp=sharing) 
* In class activity - "Hello world" in Github [https://docs.google.com/document/d/1NVsXeluktOahdaahEbKWGRV1QIRSDcEge9ELrXXG1Tw/edit?usp=sharing](https://docs.google.com/document/d/1NVsXeluktOahdaahEbKWGRV1QIRSDcEge9ELrXXG1Tw/edit?usp=sharing)
* In class - use Git-scm - GIT BASH

**In class activity \#2:**

**open up git bash / scm**

**check config - git config -- list**

**add your git config user.name / user.email**  


**In class activity \#3:**

* **Getting a git repository -** [**https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository**](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
  * **try creating a git repository yourself, locally, create the local directly then initialize it with git**
    * **mkdir for a new directory / folder locally**
    * **then cd into new directory**

**\[if you already had a directory that you wanted to add git to, you would go into that directory and then follow along with the git init and other commands below…\]**

* * * **then git init**
    * **then git status**
    * **then create a file - e.g., touch readme.md**
    * **then git status**
      * **\[shows untracked file readme.md\]**
    * **then git add readme.md**
    * **then git status** 
      * **\[shows tracked/staged, but uncommitted\]**
    * **then git commit -m “first commit, added readme”**
    * **then git status** 
      * **\[nothing different since commit\]**
    * **then modify the file \(e.g., add a line to the readme.md file\)**
    * **then git status** 
      * **\[git notices the file is modified, but not staged, would need to git add to stage\]**
    * **then git add**
    * **then git status** 
      * **\[file staged, not committed\]**
    * **then git commit -m “first line added to file”**
    * **then git status**
      * **\[nothing different since commit\]**
    * **then git log** 
      * **\[to view history of commits\]**

**when you are ready to add it to a repo on github, add the github repo as your remote and push to it \(see:** [**https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line**](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)**\)**

* * * * **if you did not already do so, create an empty github repo \[Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.\]**
      * **At the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.**
      * **In the Command prompt, add the URL for the remote repository where your local repository will be pushed.**
        * **$ git remote add origin remote-repository-URL**

**\# Sets the new remote**

* * * * * **$ git remote -v**

**\# Verifies the new remote URL**

* * * * **Push the changes in your local repository to GitHub.**
        * **$ git push origin master**

**\# Pushes the changes in your local repository up to the remote repository you specified**  


