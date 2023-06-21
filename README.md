git status 
git add .
git commit -m "1st commit"
git push origin main
git fetch
git merge
git pull (fetch + merge)
git commit --amend -m "change happen with in previous commit"
git mv demo.txt renamedemo.txt  (rename file)
git rm --cached remove.txt (remove file from local)
git rm -f remove.txt (remove from local repo and machine)
git branch (all branch list)
git checkout dev (switch to dev branch)
git cherry-pick 0680bc3 (take this perticular commit only)
git log --online (get all commit list)
git reset --soft 0680bc3 (undo previous commit and take upto this comit)





SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ git config --global user.name "suvadip"

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ git config --global user.email "suvadipmaiti5@gmail.com"

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ git config --global user.password "smservice"

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ torch
bash: torch: command not found

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ touch
touch: missing file operand
Try 'touch --help' for more information.

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ touch .gitignore

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/SMSERVICEONLINE/sm/.git/

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (master)
$ git add .

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore


SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (master)
$ git commit -m "first commit"
[master (root-commit) e1d110b] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (master)
$ git branch -M main

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (main)
$ git remote add origin git@github.com:SuvadipMaiti/sm.git

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (main)
$ ssh-keygen -t ed25519 -C "suvadipmaiti5@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/User/.ssh/id_ed25519):
/c/Users/User/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/User/.ssh/id_ed25519
Your public key has been saved in /c/Users/User/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:j/MZN1bZYFp7pAFOo5BaolexNbVXquudv3rXUYqi/UA suvadipmaiti5@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|        ooo.=   .|
|      . ++ = + o |
|     . =. . o B .|
|    . o      * O.|
|     .  S E o.=.+|
|         +. .o.o |
|        oo+.=   o|
|        .o.B o oo|
|          o.o.=o+|
+----[SHA256]-----+

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (main)
$ cat /c/Users/User/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIMF9Hz2hLBv/RvhFe6QXaWBqmq6Q5ojbBcU8O4yb+c+g suvadipmaiti5@gmail.com

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 211 bytes | 21.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:SuvadipMaiti/sm.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

SUVADIP@DESKTOP-MH2O29V MINGW64 ~/Desktop/SMSERVICEONLINE/sm (main)
