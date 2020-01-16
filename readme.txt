basic operation till "time traveling"
$ mkdir learngit
$ cd learngit
$ pwd %%to see the catalog at present
$ git add
$ git commit
$ git status
$ git diff
$ cat readme.txt %%to see the context  
$ git log %% history
$ git reset hard HEAD^  %% ^, ^^ means iterations of retreat back. if for 100 times Head~100
$ git reset hard #####
$ git reflog %% retreat back to history to see the commit id
**It's important to understand the concept of : working directory,  temporary stage, respiratory.
$ git diff HEAD -- readme.txt  %% to see the difference between the file in workspace and master
$ git checkout -- filename %%discard changes in working directory（ if temporary stage have last stage's files)
$ git reset HEAD<file> %% unstage，扰乱了工作文件的内容，还添加到了stage时，先reset, 再checkout
 
Git is a distributed version control system.
Git is free software distributed under GPL.
Git has a mutable index called stage.
Git tracks changes for files.