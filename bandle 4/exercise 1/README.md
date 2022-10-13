# Bandle 4 / Exercise

```bash

z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git remote add origin https://github.com/Jonath-z/git-exrcises-part-2.git
error: remote origin already exists.
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git remote add git-copy  https://github.com/Jonath-z/git-exrcises-part-2.git
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git remote -v
git-copy        https://github.com/Jonath-z/git-exrcises-part-2.git (fetch)
git-copy        https://github.com/Jonath-z/git-exrcises-part-2.git (push)
origin  https://github.com/Jonath-z/the-GYM-git-exercises.git (fetch)
origin  https://github.com/Jonath-z/the-GYM-git-exercises.git (push)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: new content added to the home page"
[main 1d83f8e] feat: new content added to the home page
 1 file changed, 3 insertions(+), 1 deletion(-)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 502 bytes | 502.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   9eee582..1d83f8e  main -> main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push git-copy main
Enumerating objects: 69, done.
Counting objects: 100% (69/69), done.
Delta compression using up to 4 threads
Compressing objects: 100% (52/52), done.
Writing objects: 100% (69/69), 8.78 KiB | 749.00 KiB/s, done.
Total 69 (delta 13), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (13/13), done.
To https://github.com/Jonath-z/git-exrcises-part-2.git
 * [new branch]      main -> main
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$

```
