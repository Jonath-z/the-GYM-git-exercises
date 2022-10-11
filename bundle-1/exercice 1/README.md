# The Gym bundle 1 / Exercise 1

## Commande history

```bash
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git remote add origin https://github.com/Jonath-z/the-GYM-git-exercises.git
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch -m main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/

nothing added to commit but untracked files present (use "git add" to track)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add bundle-1/
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "git exercise 1"
[main (root-commit) 6356539] git exercise 1
 3 files changed, 20 insertions(+)
 create mode 100644 bundle-1/about.html
 create mode 100644 bundle-1/exercise-1.md
 create mode 100644 bundle-1/index.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 563 bytes | 563.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      main -> main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b dev
Switched to a new branch 'dev'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b test
Switched to a new branch 'test'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout dev
Switched to branch 'dev'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch delete test
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
  delete
* dev
  main
  test
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch --delete test
Deleted branch test (was 6356539).
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch --delete delete
Deleted branch delete (was 6356539).
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
* dev
  main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$
```
