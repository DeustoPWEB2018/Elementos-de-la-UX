C:\Users\ihern> cd Repositorios/Elementos-de-la-UX

C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git status

On branch documentar
nothing to commit, working tree clean

C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git pull origin documentar

remote: Enumerating objects: 27, done.
remote: Counting objects: 100% (27/27), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 23 (delta 15), reused 11 (delta 6), pack-reused 0
Unpacking objects: 100% (23/23), done.
From https://github.com/DeustoPWEB2018/Elementos-de-la-UX
 * branch            documentar -> FETCH_HEAD
   46a8cad..5acb4cf  documentar -> origin/documentar
Updating 46a8cad..5acb4cf
Fast-forward
 1-estrategia/documentar.md                              |   5 ++---
 1-estrategia/evaluaciones/OdriozolaInaki-20181003.xlsx  | Bin 17920 -> 0 bytes
 .../evaluaciones/OdriozolaI\303\261aki-20181003.xlsx"   | Bin 17920 -> 0 bytes
 3 files changed, 2 insertions(+), 3 deletions(-)
 delete mode 100644 1-estrategia/evaluaciones/OdriozolaInaki-20181003.xlsx
 delete mode 100644 "1-estrategia/evaluaciones/OdriozolaI\303\261aki-20181003.xlsx"

<<<<<<< HEAD
C:\Users\ihern\Repositorios\Elementos-de-la-UX **git status
=======
C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git status
>>>>>>> 6780dc628ebfae39babfcbb269a3fcd8e0d617c6

On branch documentar
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   1-estrategia/documentar.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git add .

<<<<<<< HEAD
=======
C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git status
>>>>>>> 6780dc628ebfae39babfcbb269a3fcd8e0d617c6

On branch documentar
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   1-estrategia/documentar.md


C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git commit -m "Added modifications with markdown"

[documentar 44e5c4b] Added modifications with markdown
 1 file changed, 12 insertions(+), 12 deletions(-)
 rewrite 1-estrategia/documentar.md (90%)

C:\Users\ihern\Repositorios\Elementos-de-la-UX> **git push origin documentar

Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 522 bytes | 261.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/DeustoPWEB2018/Elementos-de-la-UX.git
   5acb4cf..44e5c4b  documentar -> documentar

C:\Users\ihern\Repositorios\Elementos-de-la-UX>
