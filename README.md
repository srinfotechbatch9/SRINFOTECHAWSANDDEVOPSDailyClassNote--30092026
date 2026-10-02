# SRINFOTECHAWSANDDEVOPSDailyClassNote--30092026

AWS And DevOps Demo::
======================

30/09/2026::
============

<img width="1903" height="739" alt="image" src="https://github.com/user-attachments/assets/2fb6424c-0203-4040-9063-ae9b807eefe9" />





02/10/2026::
=============

Lab Practicals::
===============

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9
$ git clone git@github.com:srinfotechbatch9/srinfotechdemo.git
Cloning into 'srinfotechdemo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is: SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9
$ cd srinfotechdemo

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'HelloWorld.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git commit -m "just added helloworld java file"
[main 8a4ee1a] just added helloworld java file
 3 files changed, 47 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 768 bytes | 256.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch9/srinfotechdemo.git
   8eca81c..8a4ee1a  main -> main

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git add --all
warning: in the working copy of 'HelloWorld.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   HelloWorld.java


HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git commit -m "updatdd the code in helloworld"
[main 9a255ef] updatdd the code in helloworld
 1 file changed, 6 deletions(-)

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 355 bytes | 355.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:srinfotechbatch9/srinfotechdemo.git
   8a4ee1a..9a255ef  main -> main

HP@DESKTOP-3GU6R56 UCRT64 ~/Documents/srinfotech batch9/srinfotechdemo (main)
$
