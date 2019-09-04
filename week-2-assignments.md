# Week 2 - Assignments

Install git scm software & configure for first time \(see reference: [https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) but my recommendations are: 

1. Install Git  \[My recommendation would be to use the gitforwindows project for windows - [https://gitforwindows.org/](https://gitforwindows.org/); using [https://git-scm.com/download/mac](https://git-scm.com/download/mac) for Mac with directions explained here - including security issues - [https://codeburst.io/installing-git-for-the-first-time-on-mac-osx-bf9c513af2b8](https://codeburst.io/installing-git-for-the-first-time-on-mac-osx-bf9c513af2b8)\]

1a. Configure your git user.name & user.email

```text
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

1b. Send me a copy or a screenshot of your .gitconfig file via email or  \(.gitconfig is a “hidden file” - in Windows, probably will be at C:\Users\yourusername\.gitconfig; in Mac, will likely be at /Users/yourname

1c. note any challenges you had with installation / .gitconfig finding \(e.g., in Gitter Week 2 room, or email directly to me\)

2. Essentially following these instructions: [https://guides.github.com/activities/forking/](https://guides.github.com/activities/forking/)

fork the ccsute350 repo coursedocs \(if you didn’t already\)

\[if you are running into problems with "forking" - the concept and the how on Github - check out this short video [https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5](https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5) \(approx. 2 mins\)\]

In fact, this playlist of short youtube videos covers everything you will need to know in git \(though does so for data scientists, still the same toolset/functions\) - [http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD](http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)

2a. clone the coursedocs repo to your local repository, work from your clone of the forked repo

2b. edit the syllabus.md 

 2c. for basic points, simply add your name at the bottom of the page

 2d. for 2-5 extra points \(pending the1.6 Getting Started - First-Time Git Setup number and legitimacy of edits\), also find a typo, misspelling, need for updated url, or other mistake, then fix it, and send a pull request to me\) Read: Getting Legit with Git and GitHub: Your First Pull Request [https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/](https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/)

3. Practice with git - add another repo to your GitHub, work with it in git, then commit locally & push to your remote GitHub repo 

* try forking, then cloning down a git repository - [https://github.com/ccsu-te350/Week2-Class-1](https://github.com/ccsu-te350/Week2-Class-1)
  * fork the repo on github to your own github account
  * go into command line git, get to root directory you want your repo to be in -  e.g., C:/Users/yourusername
  * then git clone your forked repo with the address provided by github - e.g., git clone https://github.com/myusername/Week2-Class-1.git 
  * git status
  * then, into that local repo, add a file called readme.md \(put in it whatever you want, e.g., \# This is my readme.md file for the Week2-Class-1 repository\)
  * go through the git add \[staging\] option
  * git commit & then git push edits back up \[before git push, check the git remote -v, reset if needed, see below about cloning down another person’s repo\]
  * try cloning down someone else’s repo, e.g., git clone [https://github.com/epodigital/Git-and-GitHub-for-Poets.git](https://github.com/epodigital/Git-and-GitHub-for-Poets.git)

   when you git remote -v

   you should see that your remote is to the original person’s repo; you won’t be able to push to this, so the remote will need to be reset?

   create your empty repo at github to be the remote for your cloned version of the repo

    copy the empty repo’s address then: 

git remote set-url origin [https://github.com/youraccountname/yournewemptygitrepo.git](https://github.com/youraccountname/yournewemptygitrepo.git)

   only then can you git push origin master  


**Read from** _**Pro Git**_ **\(free online, openly licensed at** [**https://git-scm.com/book/en/v2**](https://git-scm.com/book/en/v2)**\) - at least:** 

* 1.3 Getting Started: What is Git?
* In SUPPORT OF 1a - Read _Pro Git_'s 1.6 Getting Started - First-Time Git Setup: [https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) \[don’t worry about editor default, but do set up your user.name and user.email\] 

**In preparation for the next class about use of Pull Requests in Open Source Software:**

* Listen to \(approx. 26 m\) podcast _**Command Line Heroes Podcast, SEASON 2, EPISODE 3: “Ready to Commit” \[00:26:15\]**_

  [https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit?extIdCarryOver=true&sc\_cid=701f2000001OH7EAAW](https://www.redhat.com/en/command-line-heroes/season-2/ready-to-commit?extIdCarryOver=true&sc_cid=701f2000001OH7EAAW)  
  ****

* **Read:** _Getting Legit with Git and GitHub: Your First Pull Request_ [https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/](https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/)

### References:

* Data School's series on git \(& github\) seemed excellent, videos in short segments - view full playlist at  ****[http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD](http://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* Data School has an excellent-looking Git Quick Reference for Beginners page at: [https://www.dataschool.io/git-quick-reference-for-beginners/](https://www.dataschool.io/git-quick-reference-for-beginners/)
* A little irreverent, but easy to read website/tutorial on git [https://rogerdudler.github.io/git-guide/](https://rogerdudler.github.io/git-guide/) called: "git - the simple guide: just a simple guide for getting started with git. no deep shit ;\)" by Roger Dudler
* A git cheatsheet for beginners that I think looks a little easier to grasp than the Github Education cheatsheet \(from the Roger Dudler website on simple git\) - [https://rogerdudler.github.io/git-guide/files/git\_cheat\_sheet.pdf](https://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)
* Github Education's cheatsheet of git commands: [https://education.github.com/git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf)
* The _**Pro Git**_ book \(openly licensed, free online\) at [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2)
* Git scm videos at [https://git-scm.com/videos](https://git-scm.com/videos)
* Github help at [https://help.github.com/en](https://help.github.com/en)
* Github guides at [https://guides.github.com/](https://guides.github.com/)
* Github Learning Lab at [https://lab.github.com/](https://lab.github.com/)
* 2 forking-specific resources:
  * [https://guides.github.com/activities/forking/](https://guides.github.com/activities/forking/) \[the activity that you have to do in \#2 essentially\)
  * a good, short video on what a fork is and how to do it from the Data School series:  [https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5](https://www.youtube.com/watch?v=f5grYMXbAV0&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD&index=5)



\*\*\*\*



