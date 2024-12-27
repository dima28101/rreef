rreef@HAPO4ka MINGW64 /c
$ git status
fatal: not a git repository (or any of the parent directories): .git

rreef@HAPO4ka MINGW64 /c
$ git clone https://github.com/dima28101/rreef.git
Cloning into 'rreef'...
info: please complete authentication in your browser...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

rreef@HAPO4ka MINGW64 /c
$ cd rreef

rreef@HAPO4ka MINGW64 /c/rreef (main)
$ git checkout -b new-branch
Switched to a new branch 'new-branch'

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ echo "text1" > file.txt

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git add file.txt
warning: in the working copy of 'file.txt', LF will be replaced by CRLF the next time Git touches it

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git commit -m "commit1"
[new-branch eeb69f7] commit1
 1 file changed, 1 insertion(+)
 create mode 100644 file.txt

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ echo "text2" > file.txt

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git add file.txt
warning: in the working copy of 'file.txt', LF will be replaced by CRLF the next time Git touches it

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git commit -m "commit2"
[new-branch 0de7ad2] commit2
 1 file changed, 1 insertion(+), 1 deletion(-)

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ echo "text3" > file.txt

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git add file.txt
warning: in the working copy of 'file.txt', LF will be replaced by CRLF the next time Git touches it

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git commit -m "commit3"
[new-branch 685da4b] commit3
 1 file changed, 1 insertion(+), 1 deletion(-)

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git add README.md

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
$ git push origin new-branch
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 20 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 893 bytes | 893.00 KiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'new-branch' on GitHub by visiting:
remote:      https://github.com/dima28101/rreef/pull/new/new-branch
remote:
To https://github.com/dima28101/rreef.git
 * [new branch]      new-branch -> new-branch

rreef@HAPO4ka MINGW64 /c/rreef (new-branch)
# rreef
