# Exercise 1 / bandle 2

## Command history

```bash
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
* dev
  main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "service page added"
[ft/bundle-2 1ea5146] service page added
 1 file changed, 10 insertions(+)
 create mode 100644 bandle-2/exercise 1/service.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/bundle-2
Enumerating objects: 32, done.
Counting objects: 100% (32/32), done.
Delta compression using up to 4 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (32/32), 3.83 KiB | 979.00 KiB/s, done.
Total 32 (delta 7), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (7/7), done.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/bundle-2
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$
```

## After renaming README

```bash
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "readme renamed to README"
[ft/bundle-2 6868ebd] readme renamed to README
 3 files changed, 0 insertions(+), 0 deletions(-)
 rename bandle-2/exercise 1/{readme.md => README.md} (100%)
 rename bundle-1/exercice 1/{readme.md => README.md} (100%)
 rename bundle-1/exercise 2/{readme.md => README.md} (100%)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/bundle-2
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 653 bytes | 72.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   b7c52e1..6868ebd  ft/bundle-2 -> ft/bundle-2
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$
```

# Exercise 2/ command history

```bash
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git pull origin main
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 619 bytes | 619.00 KiB/s, done.
From https://github.com/Jonath-z/the-GYM-git-exercises
 * branch            main       -> FETCH_HEAD
   09af14d..d12c551  main       -> origin/main
Updating 6356539..d12c551
Fast-forward
 bandle-2/exercise 1/README.md        | 54 ++++++++++++++++++++++++++++++++++++++++++++++++++++++
 bandle-2/exercise 1/service.html     | 10 ++++++++++
 bundle-1/exercice 1/README.md        | 56 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 bundle-1/{ => exercice 1}/about.html |  0
 bundle-1/{ => exercice 1}/index.html |  0
 bundle-1/exercise 2/README.md        | 94 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 bundle-1/exercise 2/about.html       | 10 ++++++++++
 bundle-1/exercise 2/home.html        | 10 ++++++++++
 bundle-1/exercise 2/team.html        | 10 ++++++++++
 bundle-1/exercise-1.md               |  0
 10 files changed, 244 insertions(+)
 create mode 100644 bandle-2/exercise 1/README.md
 create mode 100644 bandle-2/exercise 1/service.html
 create mode 100644 bundle-1/exercice 1/README.md
 rename bundle-1/{ => exercice 1}/about.html (100%)
 rename bundle-1/{ => exercice 1}/index.html (100%)
 create mode 100644 bundle-1/exercise 2/README.md
 create mode 100644 bundle-1/exercise 2/about.html
 create mode 100644 bundle-1/exercise 2/home.html
 create mode 100644 bundle-1/exercise 2/team.html
 delete mode 100644 bundle-1/exercise-1.md
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git reset
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "content added in service page"
[ft/service-redesign f3c8a33] content added in service page
 1 file changed, 3 insertions(+), 1 deletion(-)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/service-redesign
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 499 bytes | 38.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/service-redesign
remote: 
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "content added in service page"
[main 0dc0852] content added in service page
 1 file changed, 3 insertions(+), 1 deletion(-)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 494 bytes | 494.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   d12c551..0dc0852  main -> main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git diff
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git diff @ @{upstream}
fatal: no upstream configured for branch 'ft/service-redesign'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch -a
  dev
  ft/bundle-2
* ft/service-redesign
  main
  remotes/origin/dev
  remotes/origin/ft/bundle-2
  remotes/origin/ft/service-redesign
  remotes/origin/main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git diff ft/service-redesign origin/ft/service-redesign
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git diff ft/service-redesign origin/main
diff --git a/bandle-2/exercise 1/service.html b/bandle-2/exercise 1/service.html
index cc5db33..a6ae518 100644
--- a/bandle-2/exercise 1/service.html  
+++ b/bandle-2/exercise 1/service.html  
@@ -7,6 +7,6 @@
     <title>Service | page</title>
   </head>
   <body>
-    <h1>Hello from service page</h1>
+    <h1>Service page title</h1>
   </body>
 </html>
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git merge ft/service-redesign
Already up-to-date.
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git merge main
Auto-merging bandle-2/exercise 1/service.html
CONFLICT (content): Merge conflict in bandle-2/exercise 1/service.html
Automatic merge failed; fix conflicts and then commit the result.
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ 
```
