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
