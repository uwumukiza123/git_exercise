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

 ## bundle 2

 ### exercise 2

 ```bash
 
ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ ls
index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git pull
Already up to date.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ ls
index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git pull origin ft/bundle-2
From https://github.com/uwumukiza123/git_exercise
 * branch            ft/bundle-2 -> FETCH_HEAD
Updating c7df712..2151132
Fast-forward
 README.md     | 150 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 services.html |  11 +++++
 2 files changed, 161 insertions(+)
 create mode 100644 README.md
 create mode 100644 services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ ls
README.md  index.html  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git checkout ft/service-redesign
error: pathspec 'ft/service-redesign' did not match any file(s) known to git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ ls
README.md  index.html  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git add .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git commit -m 'chenged service.html file'
[ft/service-redesign 7cf4c5e] chenged service.html file
 1 file changed, 1 insertion(+)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$  git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/service-redesign
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git commid -m 'changed service file'
git: 'commid' is not a git command. See 'git --help'.

The most similar command is
        commit

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git commit -m 'changed service file'
[main 4547740] changed service file
 1 file changed, 2 insertions(+), 1 deletion(-)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwumukiza123/git_exercise.git
   c7df712..4547740  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git diff

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign|MERGING)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign|MERGING)
$ git commit -m 'merged main with ft/service-redesign branches'
[ft/service-redesign 8719f36] merged main with ft/service-redesign branches

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 420 bytes | 210.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwumukiza123/git_exercise.git
   7cf4c5e..8719f36  ft/service-redesign -> ft/service-redesign

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/git-exercise (ft/service-redesign)
$

 ```
