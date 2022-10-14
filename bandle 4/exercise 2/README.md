# Bandle 4 / Exercise 2

```bash

z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: footer page added"
[ft/footer 1d1ca77] feat: footer page added
 1 file changed, 10 insertions(+)
 create mode 100644 bandle 4/exercise 1/footer.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: footer title added"
[ft/footer b014036] feat: footer title added
 1 file changed, 3 insertions(+), 1 deletion(-)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/footer
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (10/10), 1.03 KiB | 131.00 KiB/s, done.
Total 10 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/footer
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/footer -> ft/footer
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git merge --squash ft/footer
Updating 4a1266b..b014036
Fast-forward
Squash commit -- not updating HEAD
 bandle 4/exercise 1/footer.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 bandle 4/exercise 1/footer.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: footer changes squashing"
[ft/squashing 137a5db] feat: footer changes squashing
 1 file changed, 12 insertions(+)
 create mode 100644 bandle 4/exercise 1/footer.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/squashing
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 632 bytes | 316.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/squashing
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/squashing -> ft/squashing
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$

```
