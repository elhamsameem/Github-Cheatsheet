# Github-Cheatsheet
##### Github Cheatsheet contains all the commands you are looking for
<br/>



``` git clone your-repo-ssh-or-http-link ``` (To clone a repo)

``` git checkout -b branch_name ``` ( Create a new repo on local computer)

 ``` git branch  ``` (shows the list of branches you have on your local computer)
 
 ``` git checkout branch_name  ``` (changes branch)
 
 ``` git checkout -b branch_name  ``` (creates a new branch and changes the active branch to the new one)
 
 ``` git add file_name  ``` (adds the untracked/edited file to the tree for commit)
 
 ``` git add .  ``` ( adds all untracked files to the tree)
 
 ``` git commit -m "your_message"  ``` (used for commits)
 
 ``` git push -u origin branch_name  ``` (push changes/tracked files to the github online)
 
 ``` git pull  ``` (pull updates from github online)
 
 ``` git branch -d branch_name  ``` (deletes a branch)

 <br/>
 If you have conflict merging two main branches:
(The “fatal: refusing to merge unrelated histories” Git error)
 
 
 ``` git pull origin main --allow-unrelated-histories```
