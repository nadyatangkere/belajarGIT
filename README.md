Daftar tugas/branch
1.Tugas-git
2.Tugas-html
3.Tugas-css
4.Tugas-js
5.Tugas-midProject
6.Tugas-php
7.Tugas-finalProject

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git
$ git clone https://github.com/nadyatangkere/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git
$ git init
Initialized empty Git repository in C:/nadya/Git/.git/

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git (master)
$ cd belajarGIT

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-git

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt.txt
        Tugas-FinalProject.txt.txt
        Tugas-Git.txt.txt
        Tugas-Html.txt.txt
        Tugas-Js.txt.txt
        Tugas-MidProject.txt.txt
        Tugas-Php.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt
fatal: pathspec 'Tugas-Git.txt' did not match any files

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git config -global user.email "nadyatangkere@gmail.com"
error: did you mean `--global` (with two dashes)?

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 070a0b8] tugasgit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-git
Updating 1d4d871..070a0b8
Fast-forward
 Tugas-Git.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 276 bytes | 276.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/nadyatangkere/belajarGIT.git
   1d4d871..070a0b8  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-html

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt
fatal: pathspec 'Tugas-Html.txt' did not match any files

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git commit -m "htmltugas"
[Tugas-html 7328316] htmltugas
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-html
Updating 070a0b8..7328316
Fast-forward
 Tugas-Html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 276 bytes | 276.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/nadyatangkere/belajarGIT.git
   070a0b8..7328316  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-css

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git commit -m "csstugas"
[Tugas-css acf1d7b] csstugas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-css
Updating 7328316..acf1d7b
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 261 bytes | 130.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nadyatangkere/belajarGIT.git
   7328316..acf1d7b  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-js

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git commit -m "javascripttugas"
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Js.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Js.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-js.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js c293230] tugasjs
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-js
Updating acf1d7b..c293230
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 288 bytes | 288.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nadyatangkere/belajarGIT.git
   acf1d7b..c293230  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-midProject

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-MidProject
Switched to branch 'Tugas-MidProject'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git add Tugas-midProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git commit -m "midproject"
[Tugas-MidProject b077613] midproject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git status
On branch Tugas-MidProject
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-MidProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-midProject
Updating c293230..b077613
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 245 bytes | 245.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nadyatangkere/belajarGIT.git
   c293230..b077613  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-php

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git commit -m "phptugas"
[Tugas-php afc8730] phptugas
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-php
Updating b077613..afc8730
Fast-forward
 Tugas-Php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 232 bytes | 232.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nadyatangkere/belajarGIT.git
   b077613..afc8730  main -> main

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git branch Tugas-finalProject

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git checkout Tugas-finalproject
Switched to branch 'Tugas-finalproject'

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git add Tugas-FinalProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git config --global user.email "nadyatangkere@gmail.com"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git config --global user.name "nadyatangkere"

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git commit -m 'tugasfinalproject"
> ;
> ''
> "
> ""
> '
[Tugas-finalproject 68bc15d] tugasfinalproject" ;
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git status
On branch Tugas-finalproject
nothing to commit, working tree clean

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (Tugas-finalproject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git merge Tugas-finalProject
Updating afc8730..68bc15d
Fast-forward
 Tugas-FinalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

Asus@LAPTOP-NJS0VREB MINGW64 /c/nadya/Git/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 252 bytes | 252.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nadyatangkere/belajarGIT.git
   afc8730..68bc15d  main -> main
