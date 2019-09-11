# Week 2 - Assignments

Install git scm software & configure for first time \(see reference: [https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) but my recommendations are: 

1. Install Git  \[My recommendation would be to use the gitforwindows project for windows - [https://gitforwindows.org/](https://gitforwindows.org/); using [https://git-scm.com/download/mac](https://git-scm.com/download/mac) for Mac with directions explained here - including security issues - [https://codeburst.io/installing-git-for-the-first-time-on-mac-osx-bf9c513af2b8](https://codeburst.io/installing-git-for-the-first-time-on-mac-osx-bf9c513af2b8)\]

1a. Configure your git user.name & user.email

```text
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

1b. Send me a copy or a screenshot of your .gitconfig file via email or  \(.gitconfig is a “hidden file” - in Windows, probably will be at C:\Users\yourusername\.gitconfig; in Mac, will likely be at /Users/yourname\)

1c. note any challenges you had with installation / .gitconfig finding \(e.g., in Gitter Week 2 room, or email directly to me\)

2. Essentially following these instructions: [https://guides.github.com/activities/forking/](https://guides.github.com/activities/forking/) - Github Fork

in github, fork the ccsute350 repo coursedocs \(if you didn’t already\)

\[if you are running into problems with "forking" - the concept and the how on Github - check out this short video [https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5](https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5) \(approx. 2 mins\)\]

In fact, this playlist of short youtube videos covers everything you will need to know in git \(though does so for data scientists, still the same toolset/functions\) - [http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD](http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)

2a. edit the syllabus.md  \(you can actually 

 2b. for basic points, simply add your name at the bottom of the page

 2c. for 2-5 extra points \(pending the1.6 Getting Started - First-Time Git Setup number and legitimacy of edits\), also find a typo, misspelling, need for updated url, or other mistake, then fix it, and send a pull request to me\) Read: Getting Legit with Git and GitHub: Your First Pull Request [https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/](https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/)

**3.** _**\[Substituting for former \#3\]**_ 

Watch & practice along with: 

1. Introduction to Git: Core Concepts - [https://youtu.be/uR6G2v\_WsRA](https://youtu.be/uR6G2v_WsRA) 
2. Introduction to Git: Branching and Merging - [https://youtu.be/FyAAIHHClqI](https://youtu.be/FyAAIHHClqI) 
3. Introduction to Git: Remotes - [https://youtu.be/Gg4bLk8cGNo](https://youtu.be/Gg4bLk8cGNo) 

Practice the following types of things in your git and command line

a. Creating a repository, initializing a repository, modifying files in the repository, then adding them to staging, and finally committing them with a message describing the commit's inclusion

* **git init**
* **git status**
* **git add** _**filename**_ **** **git add .**
* **git status**
* **git commit -m** _**"message why I'm committing these files"**_

b. Along the way, you will need some common command line \(aka, CLI\) commands. See: [https://www.git-tower.com/blog/command-line-cheat-sheet/](https://www.git-tower.com/blog/command-line-cheat-sheet/) Some that we used today in class included:

* **pwd** \[print working directory - find out where you are\]
* **cd** \[change directory - to go up just 1 level, use **cd ..** , up 2 levels, use **cd ../..** otherwise, use **cd** _**directoryname**_ - using whatever the directory name is that you want to get into.. you make even choose to direct to a full path, such as **cd c:/Users/**_**yourusername/yourreponame**_\]
* **ls**
* **mkdir**
* **cat**
* **less**

 c. Some git commands we did not get to in class that I would like you to try out:

* **git log** \[view your history of git activities on your local pc\] 
* **git rm** _**filename**_ ****\[remove both the file named _filename_ and the git record of it\]

d. if you feel adventurous, I encourage you to clone down a repo from your own github \(e.g., one that you have forked from another\) as a way of creating a local git repo and try some of the following commands:

* **git clone**
* **git remote -v**
* **git push origin master** 
* **git fetch / git merge**
* **git pull**
* **git branch**  **git checkout -b** _**yournewbranchname**_ ****

_3_~~_. \[NOTE: See the \#3 above instead, we will work on these more complex options of forking, cloning down, adding remotes, pushing & placing pull requests in class or next week.\] Practice with git - add another repo to your GitHub, work with it in git, then commit locally & push to your remote GitHub repo_~~ 

* ~~_try forking, then cloning down a git repository -_~~ [~~_https://github.com/ccsu-te350/Week2-Class-1_~~](https://github.com/ccsu-te350/Week2-Class-1)~~\_\_~~
  * ~~_fork the repo on github to your own github account_~~
  * ~~_go into command line git, get to root directory you want your repo to be in -  e.g., C:/Users/yourusername_~~
  * ~~_then git clone your forked repo with the address provided by github - e.g., git clone https://github.com/myusername/Week2-Class-1.git_~~ 
  * ~~_git status_~~
  * ~~_then, into that local repo, add a file called readme.md \(put in it whatever you want, e.g., \# This is my readme.md file for the Week2-Class-1 repository\)_~~
  * ~~_go through the git add \[staging\] option_~~
  * ~~_git commit & then git push edits back up \[before git push, check the git remote -v, reset if needed, see below about cloning down another person’s repo\]_~~
  * ~~_try cloning down someone else’s repo, e.g., git clone_~~ [~~_https://github.com/epodigital/Git-and-GitHub-for-Poets.git_~~](https://github.com/epodigital/Git-and-GitHub-for-Poets.git)~~\_\_~~

   ~~_when you git remote -v_~~

   ~~_you should see that your remote is to the original person’s repo; you won’t be able to push to this, so the remote will need to be reset?_~~

   ~~_create your empty repo at github to be the remote for your cloned version of the repo_~~

    ~~_copy the empty repo’s address then:_~~ 

~~_git remote set-url origin_~~ [~~_https://github.com/youraccountname/yournewemptygitrepo.git_~~](https://github.com/youraccountname/yournewemptygitrepo.git)~~\_\_~~

   ~~_only then can you git push origin master_~~

~~_But what about getting updates from the repository from which you forked your own?   
\[origin is the remote / github for your fork, not the original repo\] - the "upstream"_~~

~~_See more on adding the upstream remote and then git fetch / merge or git pull to get updates from master repo \(from which you forked your own\) -_~~ [~~_https://www.gun.io/blog/how-to-github-fork-branch-and-pull-request_~~](https://www.gun.io/blog/how-to-github-fork-branch-and-pull-request)~~_\]_~~

**Read from** _**Pro Git**_ **\(free online, openly licensed at** [**https://git-scm.com/book/en/v2**](https://git-scm.com/book/en/v2)**\) - at least:** 

* In SUPPORT OF 1a - Read _Pro Git_'s 1.6 Getting Started - First-Time Git Setup: [https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) \[don’t worry about editor default, but do set up your user.name and user.email\] 
* 1.3 Getting Started: What is Git?
* Read _Pro Git_ Ch. 2.1-2.5 on “Git Basics” - [https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

### Getting Help:

Google your error messages as specifically as possible with key words - e.g., git fatal error not a repository; go to Stack Overflow-based answers. Contact me and/or your classmates!

### References:

* Series of YouTube videos on git:
  1. Introduction to Git: Core Concepts - [https://youtu.be/uR6G2v\_WsRA](https://youtu.be/uR6G2v_WsRA) 
  2. Introduction to Git: Branching and Merging - [https://youtu.be/FyAAIHHClqI](https://youtu.be/FyAAIHHClqI) 
  3. Introduction to Git: Remotes - [https://youtu.be/Gg4bLk8cGNo](https://youtu.be/Gg4bLk8cGNo) 
* Data School's series on git \(& github\) seemed good, videos in very short segments - view full playlist at  ****[http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD](http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* Data School has an excellent-looking Git Quick Reference for Beginners page at: [https://www.dataschool.io/git-quick-reference-for-beginners/](https://www.dataschool.io/git-quick-reference-for-beginners/)
* A little irreverent, but easy to read website/tutorial on git [https://rogerdudler.github.io/git-guide/](https://rogerdudler.github.io/git-guide/) called: "git - the simple guide: just a simple guide for getting started with git. no deep shit ;\)" by Roger Dudler
* A git cheatsheet for beginners that I think looks a little easier to grasp than the Github Education cheatsheet \(from the Roger Dudler website on simple git\) - [https://rogerdudler.github.io/git-guide/files/git\_cheat\_sheet.pdf](https://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)
* Github Education's cheatsheet of git commands: [https://education.github.com/git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf)
* The _**Pro Git**_ book \(openly licensed, free online\) at [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2)
* Git scm videos at [https://git-scm.com/videos](https://git-scm.com/videos)
* Github help at [https://help.github.com/en](https://help.github.com/en)
* Github guides at [https://guides.github.com/](https://guides.github.com/)
* Github Learning Lab at [https://lab.github.com/](https://lab.github.com/)
* "Undoing" changes in git - [https://www.atlassian.com/git/tutorials/undoing-changes](https://www.atlassian.com/git/tutorials/undoing-changes)
* Resolving git merge issues / troubleshooting git video - [https://youtu.be/h1e8oC7g0Ps](https://youtu.be/h1e8oC7g0Ps)
* Github fork, upstream remote, pull requests - [https://www.gun.io/blog/how-to-github-fork-branch-and-pull-request](https://www.gun.io/blog/how-to-github-fork-branch-and-pull-request)
* 2 forking-specific resources:
  * [https://guides.github.com/activities/forking/](https://guides.github.com/activities/forking/) \[the activity that you have to do in \#2 essentially\)
  * a good, short video on what a fork is and how to do it from the Data School series:  [https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5](https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5)

**In preparation for the next class about use of Pull Requests in Open Source Software:**

* Listen to \(approx. 26 m\) podcast _**Command Line Heroes Podcast, SEASON 2, EPISODE 3: “Ready to Commit” \[00:26:15\]**_

  [https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit?extIdCarryOver=true&sc\_cid=701f2000001OH7EAAW](https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit?extIdCarryOver=true&sc_cid=701f2000001OH7EAAW)  
  ****

* **Read:** _Getting Legit with Git and GitHub: Your First Pull Request_ [https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/](https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/)

\*\*\*\*



