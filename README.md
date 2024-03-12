# belajarGIT
  Daftar tugas / branch
1.  Tugas-git
2.  Tugas-html
3.  Tugas-css
4.  Tugas-js
5.  Tugas-midProject
6.  Tugas-php
7.  Tugas-finalProject

Daftar perintah GIT
ACER@injil MINGW64 /
$ git clone https://github.com/jstisya/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ACER@injil MINGW64 /
$ cd belajarGIT

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ touch Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ nano Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git add .
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt dan berisi informasi"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ACER@injil.(none)')

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git config --global user.email "justisyainjilia@gmail.com"
g
ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git config --global user.name "jstisya"

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt dan berisi informasi"
[Tugas-git a0b5eda] Menambahkan file Tugas-git.txt dan berisi informasi
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git commit
On branch Tugas-git
nothing to commit, working tree clean

ACER@injil MINGW64 /belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-git
Updating 5a7e052..a0b5eda
Fast-forward
 Tugas-git.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
To https://github.com/jstisya/belajarGIT.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/jstisya/belajarGIT.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

ACER@injil MINGW64 /belajarGIT (main)
$ git pull origin main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 936 bytes | 46.00 KiB/s, done.
From https://github.com/jstisya/belajarGIT
 * branch            main       -> FETCH_HEAD
   5a7e052..9916e8d  main       -> origin/main
Auto-merging Tugas-git.txt
CONFLICT (add/add): Merge conflict in Tugas-git.txt
Automatic merge failed; fix conflicts and then commit the result.

ACER@injil MINGW64 /belajarGIT (main|MERGING)
$ git add Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (main|MERGING)
$ git commit -m "Menyelesaikan konflik pada pada file Tugas-git.txt"
[main 3717b17] Menyelesaikan konflik pada pada file Tugas-git.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 693 bytes | 693.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jstisya/belajarGIT.git
   9916e8d..3717b17  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ACER@injil MINGW64 /belajarGIT (Tugas-html)
$ touch Tugas-html.txt

ACER@injil MINGW64 /belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ACER@injil MINGW64 /belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html bbaff87] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ACER@injil MINGW64 /belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-html
Updating 3717b17..bbaff87
Fast-forward
 Tugas-html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 328 bytes | 328.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jstisya/belajarGIT.git
   3717b17..bbaff87  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ACER@injil MINGW64 /belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ACER@injil MINGW64 /belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ACER@injil MINGW64 /belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 8b4a2b2] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

ACER@injil MINGW64 /belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-css
Updating bbaff87..8b4a2b2
Fast-forward
 Tugas-css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 248 bytes | 248.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jstisya/belajarGIT.git
   bbaff87..8b4a2b2  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ACER@injil MINGW64 /belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ACER@injil MINGW64 /belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ACER@injil MINGW64 /belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 288323a] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

ACER@injil MINGW64 /belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-js
Updating 8b4a2b2..288323a
Fast-forward
 Tugas-js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 272 bytes | 272.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jstisya/belajarGIT.git
   8b4a2b2..288323a  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ACER@injil MINGW64 /belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 5397fc8] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-midProject
Updating 288323a..5397fc8
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 265 bytes | 265.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jstisya/belajarGIT.git
   288323a..5397fc8  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ACER@injil MINGW64 /belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ACER@injil MINGW64 /belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ACER@injil MINGW64 /belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php e4c52ab] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

ACER@injil MINGW64 /belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-php
Updating 5397fc8..e4c52ab
Fast-forward
 Tugas-php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 251 bytes | 251.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jstisya/belajarGIT.git
   5397fc8..e4c52ab  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ACER@injil MINGW64 /belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 163f7ee] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ACER@injil MINGW64 /belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@injil MINGW64 /belajarGIT (main)
$ git merge Tugas-finalProject
Updating e4c52ab..163f7ee
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt
ACER@injil MINGW64 /belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 265 bytes | 265.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jstisya/belajarGIT.git
   e4c52ab..163f7ee  main -> main

ACER@injil MINGW64 /belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

