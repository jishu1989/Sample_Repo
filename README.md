# Cheat Sheet

***Basic Tutorial***

```
Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects
$ ls
CityBikeTravel_ETL/  KPI_DataIntegration/  Sample_Repo/

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects
$ ls -la
total 16
drwxr-xr-x 1 Soumya Das 197121 0 Oct 12 07:07 ./
drwxr-xr-x 1 Soumya Das 197121 0 Oct 12 06:45 ../
drwxr-xr-x 1 Soumya Das 197121 0 Oct 12 06:48 CityBikeTravel_ETL/
drwxr-xr-x 1 Soumya Das 197121 0 Oct 12 06:48 KPI_DataIntegration/
drwxr-xr-x 1 Soumya Das 197121 0 Oct 12 07:14 Sample_Repo/

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects
$ cd Sample_Repo/

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects/Sample_Repo (main)
$ git add .

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects/Sample_Repo (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Introduction.txt


Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects/Sample_Repo (main)
$ git commit
[main (root-commit) 924a8d6] self introduction
 1 file changed, 5 insertions(+)
 create mode 100644 Introduction.txt

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects/Sample_Repo (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 365 bytes | 365.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/jishu1989/Sample_Repo.git
 * [new branch]      main -> main

Soumya Das@DESKTOP-BJOAIJ7 MINGW64 ~/Documents/projects/git projects/Sample_Repo (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 967 bytes | 64.00 KiB/s, done.
From https://github.com/jishu1989/Sample_Repo
   924a8d6..874adb6  main       -> origin/main
Updating 924a8d6..874adb6
Fast-forward
 README.md | 7 +++++++
 1 file changed, 7 insertions(+)
 create mode 100644 README.md

```
