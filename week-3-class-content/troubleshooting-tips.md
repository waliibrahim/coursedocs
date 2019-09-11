# Troubleshooting tips

When you've typed the command: **git log** you may end up with a screen with a colon **:** or **\(END\)** rather than being back at the command prompt. To get out of this, as with many command-line things, try **q** \(for quit\) and you should get out. 

If you get stuck in a very bad place in command line and can't seem to get out of the loop, try pressing the following 2 keyboard buttons simultaneously: **Ctrl C**   


If, on the other hand, you have entered the dreaded **vi editor** \(which will show a screen with a bunch of ~ down the side\), you should hit the **Esc** button then the **:**  \[colon\] and then type **q!** \(see ref: [http://itproguru.com/expert/2016/11/how-to-exit-quit-vi-editor-without-saving-changes-step-by-step/](http://itproguru.com/expert/2016/11/how-to-exit-quit-vi-editor-without-saving-changes-step-by-step/)\)

If you mistakenly created a nested git repo - e.g., by cloning into your testrepo2, you made the class2repo, you may just want to delete it, then go up to your "root" level and then clone down to that \(e.g., c:\Documents\) location fresh. When you clone down a project, it creates a directory with the name of the github repo. If you need to ever un-initialize a git repo and you have no need of those commit histories, etc., you can remove the directory **.git** and everything underneath it. Remember that this could be a dangerous thing if you were relying on your git history. \(the dangerous linux / CLI command for removing a whole directory is **rm -R** _**nameofdirectory**_\)

### References:

Command line cheatsheet - [https://www.git-tower.com/blog/command-line-cheat-sheet/](https://www.git-tower.com/blog/command-line-cheat-sheet/)

Command line basics article - [https://www.techspot.com/guides/835-linux-command-line-basics/](https://www.techspot.com/guides/835-linux-command-line-basics/)



