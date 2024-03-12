Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
…
ACER@user MINGW64 ~ (master)
$ cd documents

ACER@user MINGW64 ~/documents (master)
$ git clone https://github.com/athnael/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.

ACER@user MINGW64 ~/documents (master)
$ cd belajarGIT

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-git

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-html

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-html.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-html.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-html.txt"
[main 127adb1] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-html.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[main fa22870] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-html
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 587 bytes | 293.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/athnael/belajarGIT.git
   88f7cbd..fa22870  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-git.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-git.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-git.txt"
[main e272c90] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-git.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[main 8684dde] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-git
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 630 bytes | 315.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/athnael/belajarGIT.git
   fa22870..8684dde  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-css

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-js

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-midProject

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-php

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git branch Tugas-finalProject

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-css.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-css.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-css.txt"
[main 68e4368] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-css.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[main 5fced62] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-css
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 462 bytes | 462.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/athnael/belajarGIT.git
   8684dde..5fced62  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-js.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-js.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-js.txt"
[main 2113b21] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-js.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[main 928216d] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-js
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 483 bytes | 483.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/athnael/belajarGIT.git
   5fced62..928216d  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-midProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-midProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[main eb5b37b] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-midProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[main 9ce9a3c] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-midProject
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 483 bytes | 483.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/athnael/belajarGIT.git
   928216d..9ce9a3c  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-php.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-php.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-php.txt"
[main 8f01e0a] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-php.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[main a32c941] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-php
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 464 bytes | 464.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/athnael/belajarGIT.git
   9ce9a3c..a32c941  main -> main

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ touch Tugas-finalProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-finalProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[main 3f0f7b6] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git add Tugas-finalProject.txt

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[main bfa999f] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git merge Tugas-finalProject
Already up to date.

ACER@user MINGW64 ~/documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 491 bytes | 491.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/athnael/belajarGIT.git
   a32c941..bfa999f  main -> main
