# Bandle 3 / exercise 2

```bash
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
  dev
  ft/bundle-2
  ft/contact-page
* ft/faq-page
  ft/service-redesign
  ft/team-page
  main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/home-page-redesign
error: pathspec 'ft/home-page-redesign' did not match any file(s) known to git
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: added README file for exercise 2 / bandle 3"
[main 9eee582] feat: added README file for exercise 2 / bandle 3
 1 file changed, 1 insertion(+)
 create mode 100644 bandle-2/exercice 2/README.md
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 455 bytes | 455.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   0dc0852..9eee582  main -> main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout  ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
* ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: content added to the home page"
[ft/home-page-redesign ca7b081] feat: content added to the home page
 1 file changed, 3 insertions(+), 1 deletion(-)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/home-page-redesign
Enumerating objects: 34, done.
Counting objects: 100% (34/34), done.
Delta compression using up to 4 threads
Compressing objects: 100% (21/21), done.
Writing objects: 100% (27/27), 6.27 KiB | 713.00 KiB/s, done.
Total 27 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/home-page-redesign
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$
```
