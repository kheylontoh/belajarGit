Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
user@LAPTOP-NSB71ORR MINGW64 ~
$ cd "D:\FILE\Sem 4\tugas PW"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW
$ git clone https://github.com/kheylontoh/belajarGit.git
Cloning into 'belajarGit'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW
$ cd belajarGIT

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@LAPTOP-NSB71ORR.(none)')

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ git config --global user.email "kherenlontoh@gmail.com"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git e0c5ba9] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-git
Updating 34af0ad..e0c5ba9
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGit.git
   34af0ad..e0c5ba9  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html c0c7398] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-html
Updating e0c5ba9..c0c7398
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 294 bytes | 294.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGit.git
   e0c5ba9..c0c7398  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css b6a15b5] Menambahkan Tugas-Css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-css
Updating c0c7398..b6a15b5
Fast-forward
 Tugas-Css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGit.git
   c0c7398..b6a15b5  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js 92d8d72] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
M       Tugas-Css.txt
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git commit -m "Menambahkan Tugas-Js.txt"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Css.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git add Tugas-Js.txt
fatal: pathspec 'Tugas-Js.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-Js
Updating b6a15b5..92d8d72
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 284 bytes | 284.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGit.git
   b6a15b5..92d8d72  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-midproject
Switched to a new branch 'Tugas-midproject'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-midproject)
$ touch Tugas-MidProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-midproject)
$ git add Tugas-MidProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-midproject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midproject 1d08baa] Menambahkan Tugas-MidProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-MidProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-midproject)
$ git checkout main
Switched to branch 'main'
M       Tugas-Css.txt
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-Js
Already up to date.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Everything up-to-date

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ ^C

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-MidProject
Updating 92d8d72..1d08baa
Fast-forward
 Tugas-MidProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-MidProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 296 bytes | 296.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGit.git
   92d8d72..1d08baa  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php ed04082] Menambahkan Tugas-Php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-Php.txt
Please commit your changes or stash them before you switch branches.
Aborting

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git checkout main^C

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git commit -m "Mengcommit perubahan pada Tugas-Php.txt sebelum beralih branch"
On branch Tugas-php
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Css.txt
        modified:   Tugas-Php.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git stash
Saved working directory and index state WIP on Tugas-php: ed04082 Menambahkan Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-Php
Updating 1d08baa..ed04082
Fast-forward
 Tugas-Php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 247 bytes | 247.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGit.git
   1d08baa..ed04082  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-finalProject Daftar perintah GiT
fatal: Cannot update paths and switch to branch 'Tugas-finalProject' at the same time.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject 0d30eef] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git merge Tugas-FinalProject
Updating ed04082..0d30eef
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 265 bytes | 132.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/belajarGit.git
   ed04082..0d30eef  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin -all
error: did you mean `--all` (with two dashes)?

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/belajarGit.git
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midproject -> Tugas-midproject
 * [new branch]      Tugas-php -> Tugas-php

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 4/tugas PW/belajarGIT (main)
$

