COMANDOS UTILIZADOS EN GIT BASH

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git push -u origin main
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/camilalescano/QALAB2023.git/'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git push -u origin main
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (14/14), 2.21 KiB | 377.00 KiB/s, done.
Total 14 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/camilalescano/QALAB2023.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git checkout dev
Switched to branch 'dev'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git checkout feature-hu-292
Switched to branch 'feature-hu-292'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git checkout dev
Switched to branch 'dev'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git status
On branch dev
nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git commit -m "Se añade AppArrays/ & ArrayMulti/ a la rama dev"
On branch dev
nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git push -u origin dev
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (23/23), 3.62 KiB | 284.00 KiB/s, done.
Total 23 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/camilalescano/QALAB2023/pull/new/dev
remote:
To https://github.com/camilalescano/QALAB2023.git
 * [new branch]      dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git checkout feature-hu-292
Switched to branch 'feature-hu-292'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git commit -m "Se agrega POO_Game/ a la rama feature-hu-292"
On branch feature-hu-292
nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git push -u origin feature-hu-292
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 4 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (20/20), 5.06 KiB | 576.00 KiB/s, done.
Total 20 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature-hu-292' on GitHub by visiting:
remote:      https://github.com/camilalescano/QALAB2023/pull/new/feature-hu-292
remote:
To https://github.com/camilalescano/QALAB2023.git
 * [new branch]      feature-hu-292 -> feature-hu-292
Branch 'feature-hu-292' set up to track remote branch 'feature-hu-292' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git checkout dev
Already on 'dev'
A       .idea/.gitignore
A       .idea/QALAB2023.iml
A       .idea/misc.xml
A       .idea/modules.xml
A       .idea/vcs.xml
M       AppArrays/src/Main.java
Your branch is up to date with 'origin/dev'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .idea/.gitignore
        new file:   .idea/QALAB2023.iml
        new file:   .idea/misc.xml
        new file:   .idea/modules.xml
        new file:   .idea/vcs.xml
        modified:   AppArrays/src/Main.java


HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git commit -m "Cambio en archivo main, nuevo String"
[dev 96d2ae7] Cambio en archivo main, nuevo String
 6 files changed, 40 insertions(+), 1 deletion(-)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/QALAB2023.iml
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/vcs.xml

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git push -u origin dev
To https://github.com/camilalescano/QALAB2023.git
 ! [rejected]        dev -> dev (fetch first)
error: failed to push some refs to 'https://github.com/camilalescano/QALAB2023.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git status
On branch dev
Your branch is ahead of 'origin/dev' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git ^C

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git commit -m "Nuevo String user en Main"
On branch dev
Your branch is ahead of 'origin/dev' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git push -u origin dev
Enumerating objects: 21, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (13/13), 1.86 KiB | 317.00 KiB/s, done.
Total 13 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/camilalescano/QALAB2023.git
   8ddb18c..168beae  dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (dev)
$ git status
On branch feature-hu-292
Your branch is up to date with 'origin/feature-hu-292'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .idea/misc.xml
        new file:   .idea/workspace.xml
        modified:   POO_Game/src/Main.java


HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git commit -m "Comentario en Main"
[feature-hu-292 f8d7a0a] Comentario en Main
 3 files changed, 68 insertions(+)
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/workspace.xml

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git push -u origin feature-hu-292
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.86 KiB | 477.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/camilalescano/QALAB2023.git
   00045ff..f8d7a0a  feature-hu-292 -> feature-hu-292
Branch 'feature-hu-292' set up to track remote branch 'feature-hu-292' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git checkout test
error: pathspec 'test' did not match any file(s) known to git

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (feature-hu-292)
$ git checkout -b test
Switched to a new branch 'test'

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git merge dev
CONFLICT (add/add): Merge conflict in .idea/misc.xml
Auto-merging .idea/misc.xml
Automatic merge failed; fix conflicts and then commit the result.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test|MERGING)
$ git commit -m "Resolucion conflicto 1"
[test 2499693] Resolucion conflicto 1

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git merge feature-hu-292
Already up to date.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git status
On branch test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .idea/workspace.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git push -u origin test
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 539 bytes | 269.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/camilalescano/QALAB2023/pull/new/test
remote:
To https://github.com/camilalescano/QALAB2023.git
 * [new branch]      test -> test
Branch 'test' set up to track remote branch 'test' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        .idea/workspace.xml
Please commit your changes or stash them before you switch branches.
Aborting

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git status
On branch test
Your branch is up to date with 'origin/test'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .idea/workspace.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git add .idea/workspace.xml
warning: LF will be replaced by CRLF in .idea/workspace.xml.
The file will have its original line endings in your working directory

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git commit -m "Resolucion de conflicto 2"
[test 71251ae] Resolucion de conflicto 2
 1 file changed, 4 insertions(+), 1 deletion(-)

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git status
On branch test
Your branch is ahead of 'origin/test' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git push -u origin test
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 444 bytes | 444.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/camilalescano/QALAB2023.git
   2499693..71251ae  test -> test
Branch 'test' set up to track remote branch 'test' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (test)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git merge test
Updating c851a14..71251ae
Fast-forward
 .idea/.gitignore                                |   8 ++
 .idea/QALAB2023.iml                             |   9 ++
 .idea/misc.xml                                  |   6 ++
 .idea/modules.xml                               |  10 ++
 .idea/vcs.xml                                   |   6 ++
 .idea/workspace.xml                             |  64 +++++++++++++
 AppArrays/.idea/.gitignore                      |   3 +
 AppArrays/.idea/misc.xml                        |   6 ++
 AppArrays/.idea/modules.xml                     |   8 ++
 AppArrays/AppArrays.iml                         |  11 +++
 AppArrays/out/production/AppArrays/Main.class   | Bin 0 -> 1165 bytes
 AppArrays/src/Main.java                         |  34 +++++++
 ArrayMulti/.idea/.gitignore                     |   3 +
 ArrayMulti/.idea/misc.xml                       |   6 ++
 ArrayMulti/.idea/modules.xml                    |   8 ++
 ArrayMulti/ArrayMulti.iml                       |  11 +++
 ArrayMulti/out/production/ArrayMulti/Main.class | Bin 0 -> 742 bytes
 ArrayMulti/src/Main.java                        |  18 ++++
 POO_Game/.idea/.gitignore                       |   3 +
 POO_Game/.idea/misc.xml                         |   6 ++
 POO_Game/.idea/modules.xml                      |   8 ++
 POO_Game/POO_Game.iml                           |  11 +++
 POO_Game/out/production/POO_Game/Auto.class     | Bin 0 -> 3222 bytes
 POO_Game/out/production/POO_Game/Main.class     | Bin 0 -> 1187 bytes
 POO_Game/out/production/POO_Game/Nissan.class   | Bin 0 -> 231 bytes
 POO_Game/out/production/POO_Game/Toyota.class   | Bin 0 -> 294 bytes
 POO_Game/src/Auto.java                          | 122 ++++++++++++++++++++++++
 POO_Game/src/Main.java                          |  50 ++++++++++
 POO_Game/src/Nissan.java                        |   6 ++
 POO_Game/src/Toyota.java                        |   8 ++
 texto1.txt                                      |   1 +
 texto2.txt                                      |   1 +
 32 files changed, 427 insertions(+)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/QALAB2023.iml
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/vcs.xml
 create mode 100644 .idea/workspace.xml
 create mode 100644 AppArrays/.idea/.gitignore
 create mode 100644 AppArrays/.idea/misc.xml
 create mode 100644 AppArrays/.idea/modules.xml
 create mode 100644 AppArrays/AppArrays.iml
 create mode 100644 AppArrays/out/production/AppArrays/Main.class
 create mode 100644 AppArrays/src/Main.java
 create mode 100644 ArrayMulti/.idea/.gitignore
 create mode 100644 ArrayMulti/.idea/misc.xml
 create mode 100644 ArrayMulti/.idea/modules.xml
 create mode 100644 ArrayMulti/ArrayMulti.iml
 create mode 100644 ArrayMulti/out/production/ArrayMulti/Main.class
 create mode 100644 ArrayMulti/src/Main.java
 create mode 100644 POO_Game/.idea/.gitignore
 create mode 100644 POO_Game/.idea/misc.xml
 create mode 100644 POO_Game/.idea/modules.xml
 create mode 100644 POO_Game/POO_Game.iml
 create mode 100644 POO_Game/out/production/POO_Game/Auto.class
 create mode 100644 POO_Game/out/production/POO_Game/Main.class
 create mode 100644 POO_Game/out/production/POO_Game/Nissan.class
 create mode 100644 POO_Game/out/production/POO_Game/Toyota.class
 create mode 100644 POO_Game/src/Auto.java
 create mode 100644 POO_Game/src/Main.java
 create mode 100644 POO_Game/src/Nissan.java
 create mode 100644 POO_Game/src/Toyota.java
 create mode 100644 texto1.txt
 create mode 100644 texto2.txt

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 9 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$ git push -u origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/camilalescano/QALAB2023.git
   c851a14..71251ae  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

HP@DESKTOP-7DR90R4 MINGW64 ~/Documents/NTT_DATA_CAPACITACIONES/Pruebas/PRUEBA_GIT/QALAB2023 (main)
$
