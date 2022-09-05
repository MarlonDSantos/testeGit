
MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub
$ cd gitInicialDevs2Blu

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu
$ git init
Initialized empty Git repository in C:/Users/marlo/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu/.git/

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git remote add origin https://github.com/MarlonDSantos/testeGit.git

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/MarlonDSantos/testeGit.git'

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Terminal.md

nothing added to commit but untracked files present (use "git add" to track)

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git add .

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Terminal.md


MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git commit -m "Primeiro commit devs2blu"
[master (root-commit) ad0b064] Primeiro commit devs2blu
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Terminal.md

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 243 bytes | 243.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MarlonDSantos/testeGit.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

MaRLoN@DESKTOP-PEOQS69 MINGW64 ~/OneDrive/Documentos/Projetos-GitHub/gitInicialDevs2Blu (master)
$
