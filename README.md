# Git exercise

## Bundle 1

### exercise 1


```bash
ABC@DESKTOP-8KGAEGA MINGW64 ~
$ cd Desktop/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop
$ cd git-exercise/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise
$ git status
fatal: not a git repository (or any of the parent directories): .git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise
$ git init
Initialized empty Git repository in C:/Users/ABC/Desktop/git-exercise/.git/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (master)
$ git branch -M main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git add index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git commit -m 'add index.html'
[main (root-commit) c7df712] add index.html
 1 file changed, 12 insertions(+)
 create mode 100644 index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git remote add origin https://github.com/uwumukiza123/git_exercise.git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$  git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 392 bytes | 78.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/dev
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      dev -> dev

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/test
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      test -> test

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (test)
$ git status
On branch test
nothing to commit, working tree clean

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (test)
$ git branch -D test
error: Cannot delete branch 'test' checked out at 'C:/Users/ABC/Desktop/git-exercise'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (test)
$ git branch dev
fatal: a branch named 'dev' already exists

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (test)
$ git checkout dev
Switched to branch 'dev'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$ git branch -D test
Deleted branch test (was c7df712).

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$ git push origin --delete test
To https://github.com/uwumukiza123/git_exercise.git
 - [deleted]         test

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (dev)
$
```
 ## Bundle 2

 ### exercise 1
 ```bash
 ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/bundle-2)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/bundle-2)
$ git commit -m 'add service file'
[ft/bundle-2 f5ea35d] add service file
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 937 bytes | 234.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/bundle-2
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/bundle-2)
$

 ```
