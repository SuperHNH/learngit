#

$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit

$ git init
Initialized empty Git repository in /Users/michael/learngit/.git/

readme.txt
Git is a distributed version control system.
Git is free software.

$ git add readme.txt
$ git commit -m "wrote a readme file"

$ git status
$ git diff readme.txt

$ git add readme.txt
$ git status
$ git commit -m "add distributed"

$ git push origin master



$ git clone git@github.com:SuperHNH/StudyPython.git
Cloning into 'StudyPython'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.


$ git clone https://github.com/SuperHNH/learngit.git
$ git clone https://github.com/SuperHNH/StudyPython.git

LC@DESKTOP-2U1EEG5 MINGW64 /e/GitHub (master)
$ git clone https://github.com/SuperHNH/learngit.git
Cloning into 'learngit'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 12 (delta 1), reused 12 (delta 1), pack-reused 0
Unpacking objects: 100% (12/12), done.

LC@DESKTOP-2U1EEG5 MINGW64 /e/GitHub (master)
$ git clone https://github.com/SuperHNH/StudyPython.git
Cloning into 'StudyPython'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
