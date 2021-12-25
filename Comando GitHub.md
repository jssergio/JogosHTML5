jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5
$ ls
Códigos/  css/  fontes/  imgs/  index.html  js/  sons/

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5
$ git init
Initialized empty Git repository in C:/Users/js058/Downloads/POO/JogosHTML5/.git/

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ ls -a
 ./   ../   .git/  'Comando GitHub.md'   Códigos/   css/   fontes/   imgs/   index.html   js/   sons/
jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git add *
warning: LF will be replaced by CRLF in js/jquery-1.11.1.min.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in js/jquery-collision.min.js.
The file will have its original line endings in your working directory

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git commit -m "Iniciar Projeto"
jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Comando GitHub.md

no changes added to commit (use "git add" and/or "git commit -a")
jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=true
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=sergio2119wyz@gmail.com
user.name=jssergio
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git remote add origin git@github.com:jssergio/jogosHTML5.git

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git remote -v
origin  git@github.com:jssergio/jogosHTML5.git (fetch)
origin  git@github.com:jssergio/jogosHTML5.git (push)

jsergio@LAPTOP-CBSQ8HH4 MINGW64 ~/Downloads/POO/JogosHTML5 (master)
$ git push origin master
Enter passphrase for key '/c/Users/js058/.ssh/id_ed25519':
Enumerating objects: 64, done.
Counting objects: 100% (64/64), done.
Delta compression using up to 8 threads
Compressing objects: 100% (61/61), done.
Writing objects: 100% (64/64), 1.63 MiB | 1.92 MiB/s, done.
Total 64 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/jssergio/jogosHTML5/pull/new/master
remote:
To github.com:jssergio/jogosHTML5.git
 * [new branch]      master -> master
 



