# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
Lenovo@SHMILY-LENOVO MINGW64 ~ (master)
$ git config --global user.email "shmilypantow026@student.unsrat.ac.id"

Lenovo@SHMILY-LENOVO MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/Lenovo/.git/

Lenovo@SHMILY-LENOVO MINGW64 ~ (master)
$ cd "C:\Users\Lenovo\Documents\Kuliah\Semester 4\Pemrograman Web (TIK2032H)"

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H) (master)
$ git clone https://github.com/shmilypantow/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H) (master)
$ cd BelajarGIT

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-git

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-git
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ touch Tugas-git.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ git add Tugas-git.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 92060a1] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ git add Tugas-git.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git 1c68b1d] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-git
Updating 5dcbb0d..1c68b1d
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 606 bytes | 46.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/shmilypantow/belajarGIT.git
   5dcbb0d..1c68b1d  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-html

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ touch Tugas-html.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 8419f03] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html ce04358] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-html
Updating 1c68b1d..ce04358
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 588 bytes | 117.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/shmilypantow/belajarGIT.git
   1c68b1d..ce04358  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-css

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ touch Tugas-css.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ git add Tugas-css.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 4087f07] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ git add Tugas-css.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css 928aaef] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-css
Updating ce04358..928aaef
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 616 bytes | 154.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/shmilypantow/belajarGIT.git
   ce04358..928aaef  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-js

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ touch Tugas-js.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ git add Tugas-js.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 9de8779] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ git add Tugas-js.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[Tugas-js eb43732] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-js
Updating 928aaef..eb43732
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 548 bytes | 137.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/shmilypantow/belajarGIT.git
   928aaef..eb43732  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-midProject

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject f1074d2] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[Tugas-midProject 3982c67] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-midProject
Updating eb43732..3982c67
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 578 bytes | 72.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/shmilypantow/belajarGIT.git
   eb43732..3982c67  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-php

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ touch Tugas-php.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ git add Tugas-php.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php bc8e897] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ git add Tugas-php.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php 9000192] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-php
Updating 3982c67..9000192
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 551 bytes | 137.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/shmilypantow/belajarGIT.git
   3982c67..9000192  main -> main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch Tugas-finalProject

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject c5145a8] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject 28c3dfe] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git merge Tugas-finalProject
Updating 9000192..28c3dfe
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Lenovo@SHMILY-LENOVO MINGW64 ~/Documents/Kuliah/Semester 4/Pemrograman Web (TIK2032H)/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 580 bytes | 145.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/shmilypantow/belajarGIT.git
   9000192..28c3dfe  main -> main
