# belajarGIT
Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GIT

veyzz@Vey MINGW64 ~
$ cd documents

veyzz@Vey MINGW64 ~/documents
$ cd unsrat

veyzz@Vey MINGW64 ~/documents/unsrat
$ cd "semester 4"

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4
$ cd "pemrograman web"

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web
$ git clone https://github.com/Vey08/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 12 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), 4.43 KiB | 4.43 MiB/s, done.
Resolving deltas: 100% (1/1), done.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web
$ cd belajarGIT

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-git

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ checkout Tugas-git
bash: checkout: command not found

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git commit "Menambah file tugas-git"
error: pathspec 'Menambah file tugas-git' did not match any file(s) known to git

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git commit -m "Menambah file tugas-git"
[Tugas-git cf5db32] Menambah file tugas-git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ checkout belajargit
bash: checkout: command not found

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git checkout belajargit
error: pathspec 'belajargit' did not match any file(s) known to git

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git checkout belajarGIT
error: pathspec 'belajarGIT' did not match any file(s) known to git

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-git
Updating f51f757..cf5db32
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 288 bytes | 288.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Vey08/belajarGIT.git
   f51f757..cf5db32  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-htmml

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-htmml
Switched to branch 'Tugas-htmml'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-htmml)
$ notepad Tugas-html.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-htmml)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-htmml)
$ git commit -m "Menambah file Tugas-html.txt"
[Tugas-htmml d32709a] Menambah file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-htmml)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-html.txt
merge: Tugas-html.txt - not something we can merge

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-html
merge: Tugas-html - not something we can merge

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch -d Tugas-htmml
error: The branch 'Tugas-htmml' is not fully merged.
If you are sure you want to delete it, run 'git branch -D Tugas-htmml'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch -D Tugas-htmml
Deleted branch Tugas-htmml (was d32709a).

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-html

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-html)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"

[Tugas-html d353a66] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-html
Updating cf5db32..d353a66
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Vey08/belajarGIT.git
   cf5db32..d353a66  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-css

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-css)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 525d9c3] Menambahkan file Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-css
Updating d353a66..525d9c3
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Vey08/belajarGIT.git
   d353a66..525d9c3  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-js

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-js)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 7a3f381] Menambahkan file Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-js
Updating 525d9c3..7a3f381
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Vey08/belajarGIT.git
   525d9c3..7a3f381  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-midProject

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-midProject)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 1b88ee5] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-midProject
Updating 7a3f381..1b88ee5
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Vey08/belajarGIT.git
   7a3f381..1b88ee5  main -> main
veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-php

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-php)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 7b58bea] Menambahkan file Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-php
Updating 1b88ee5..7b58bea
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 287 bytes | 287.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Vey08/belajarGIT.git
   1b88ee5..7b58bea  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git branch Tugas-finalProject

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-finalProject)
$ git add .

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 8f7404a] Menambahkan file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 7b58bea..8f7404a
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Vey08/belajarGIT.git
   7b58bea..8f7404a  main -> main

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push origin -all
error: did you mean `--all` (with two dashes)?

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Vey08/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

veyzz@Vey MINGW64 ~/documents/unsrat/semester 4/pemrograman web/belajarGIT (main)
$ 
