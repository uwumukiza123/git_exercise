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

 ## Bundle 3

### exercise 1

```bash
ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ ls
README.md  index.html  services.html  team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git add team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git commit -m 'add team page'
[ft/team-page 8bf01b9] add team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 475 bytes | 475.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/team-page
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/team-page -> ft/team-page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git log
commit 8bf01b9c67c7e2347617c8d10f14909a00eaf5c0 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue Jul 25 11:37:20 2023 +0200

    add team page

commit 9820a3d649b15493e300ffd916322afa21f29893 (origin/ft/service-redesign, ft/service-redesign)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 07:30:42 2023 +0200

    add bundle2 on readme file

commit 8719f36e7488fa42b87b5003ff4ac82eef06cc5b
Merge: 7cf4c5e 4547740
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 07:28:19 2023 +0200

    merged main with ft/service-redesign branches

commit 4547740c57540079efe32b3cdb4cf3c90a972dcc (origin/main, origin/HEAD, main, ft/contact-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 07:00:33 2023 +0200

    changed service file

commit 7cf4c5e07d5c469122513221e8377ed3990060ec
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 06:49:55 2023 +0200

    chenged service.html file

commit 215113247105cce17bf82255aac2fa412e125d62 (origin/ft/bundle-2)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 06:15:33 2023 +0200

    rename home to index

commit 17a713407ea7b3318fb9a93c05e3ba0007c0a155
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 06:06:15 2023 +0200

    add bundle 2-exercise1 ro readme file

commit f5ea35d02a9705053994e200d7c06b9e59cb6b5f
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 05:13:29 2023 +0200

    add service file


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git cherry-pick 8bf01b9c67c7e2347617c8d10f14909a00eaf5c0
[ft/contact-page e1ad7a0] add team page
 Date: Tue Jul 25 11:37:20 2023 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ ls
README.md  index.html  services.html  team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ touch contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ ls
README.md  contact.html  index.html  services.html  team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git add contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git commit -m 'add contact page'
[ft/contact-page c13c34a] add contact page
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 842 bytes | 421.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/contact-page
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ touch faq.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git add faq.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git commit -m 'add fag page'
[ft/faq-page db14699] add fag page
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 450 bytes | 450.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/faq-page
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git revert 8bf01b9c67c7e2347617c8d10f14909a00eaf5c0
[ft/faq-page 0714e2e] Revert "add team page"
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git log
commit 0714e2e7ba5de63289f7c1c241b579738a1e1675 (HEAD -> ft/faq-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue Jul 25 12:16:00 2023 +0200

    Revert "add team page"

    This reverts commit 8bf01b9c67c7e2347617c8d10f14909a00eaf5c0.

commit db14699fc47e42e7ab556c92b42fe945a24d31da (origin/ft/faq-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue Jul 25 12:10:59 2023 +0200

    add fag page

commit c13c34a4dc2bd820dfe0cfeb3dc6b6c931719a2e (origin/ft/contact-page, ft/contact-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue Jul 25 11:55:22 2023 +0200

    add contact page

commit e1ad7a02a7d9fde4eb1c5543db6d081fa9e936be
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue Jul 25 11:37:20 2023 +0200

    add team page

commit 4547740c57540079efe32b3cdb4cf3c90a972dcc (origin/main, origin/HEAD, main)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 07:00:33 2023 +0200

    changed service file

commit 215113247105cce17bf82255aac2fa412e125d62 (origin/ft/bundle-2)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 06:15:33 2023 +0200

    rename home to index

commit 17a713407ea7b3318fb9a93c05e3ba0007c0a155
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 06:06:15 2023 +0200

    add bundle 2-exercise1 ro readme file

commit f5ea35d02a9705053994e200d7c06b9e59cb6b5f
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Fri Jul 14 05:13:29 2023 +0200

    add service file

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git add .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git commit -m 'revert the commit on team page'
On branch ft/faq-page
nothing to commit, working tree clean

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git push orogin ft/faq-page
fatal: 'orogin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 285 bytes | 142.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwumukiza123/git_exercise.git
   db14699..0714e2e  ft/faq-page -> ft/faq-page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$

```

## Bundle 3

### exercise 1
```bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git add index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git commit -m 'add index file'
[main 24e875a] add index file
 1 file changed, 1 insertion(+), 1 deletion(-)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 401 bytes | 200.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwumukiza123/git_exercise.git
   4547740..24e875a  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git checkout -b ft/home-page-redesign
fatal: a branch named 'ft/home-page-redesign' already exists

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git rebase main
Current branch main is up to date.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git checkout
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ ls
README.md  contact.html  faq.html  index.html  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ git add index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ git commit -m 'add some changes to an index file'
[ft/home-page-redesign 576e33f] add some changes to an index file
 1 file changed, 8 insertions(+)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 4 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 4.38 KiB | 1.09 MiB/s, done.
Total 17 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git_exercise/pull/new/ft/home-page-redesign
remote:
To https://github.com/uwumukiza123/git_exercise.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/ALL IN ONE/git_exercise (ft/home-page-redesign)
$

```
