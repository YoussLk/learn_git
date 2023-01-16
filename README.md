# -----------------------Instructions-----------------------

1.Create a folder called learn_git. 
2.Cd (change directory) into the learn_git folder. 
3.Create a file called third.txt. 
4.Initialize an empty git repository. 
5.Add third.txt to the staging area. 
6.Commit with the message "adding third.txt". 
7.Check out your commit with git log. 
8.Create another file called fourth.txt. 
9.Add fourth.txt to the staging area. 
10.Commit with the message "adding fourth.txt" 
11.Remove the third.txt file. 
12.Add this change to the staging area. (Using the command "git add . " 13.Commit with the message "removing third.txt". 
14.Check out your commits using git log. 
15.Change your global settings to core.pager=cat - you can read more about that here. 
16.Write the appropriate command to list all the global configurations for git on your machine. 
17.You can type git config --global to find out how to do this.

-----------------All-Commands-Needed---------------------

!Repository named "learn_git" must be already created in your repositories on github.com

1# mkdir learn_git 
2# cd /learn_git 
3# notepad third.txt 
4# git init 5# git add . 
6# git commit -m "third.txt" 
7# git log 
8# notepad fourth.txt 
9# git add . 
10# git commit -m "adding fourth.txt" 
11# git rm third.txt 
12# git add . 
13# git commit -m "removing third.txt" 
14# git log 
15# git config --global core.pager "cat" 
16# git config --list 
17# git config --global

