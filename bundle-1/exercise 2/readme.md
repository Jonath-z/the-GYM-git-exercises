# Exercise 2 

## Code history

```bash

z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash -u
Saved working directory and index state WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash -u
Saved working directory and index state WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash -u
Saved working directory and index state WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash pop
Already up-to-date!
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/team.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped refs/stash@{0} (87932828d13207a96a70986de33fd375adf44f08)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash -u
Saved working directory and index state WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash list
stash@{0}: WIP on dev: 0783471 files stuctured by bandle/exercise
stash@{1}: WIP on dev: 0783471 files stuctured by bandle/exercise
stash@{2}: WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash pop stash@{1}
Already up-to-date!
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/about.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{1} (0d0389457937296f4e5a134556d32814fe924e42)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash list
stash@{0}: WIP on dev: 0783471 files stuctured by bandle/exercise
stash@{1}: WIP on dev: 0783471 files stuctured by bandle/exercise
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash pop stash@{1}
Already up-to-date!
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/about.html
        bundle-1/home.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{1} (34e2a86302d3f50f17a3eb9090437539328fd220)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "exercise two"
[dev 7ec3f8b] exercise two
 2 files changed, 20 insertions(+)
 create mode 100644 bundle-1/about.html
 create mode 100644 bundle-1/home.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git stash pop stash@{0}
Already up-to-date!
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/team.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{0} (2404efbb95ab9920d7a3557a8debf9dc55b20e21)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/team.html

nothing added to commit but untracked files present (use "git add" to track)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin dev
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 580 bytes | 290.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   0783471..7ec3f8b  dev -> dev
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git reset --hard
HEAD is now at 7ec3f8b exercise two
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bundle-1/team.html

nothing added to commit but untracked files present (use "git add" to track)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git status
```
