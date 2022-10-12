# Bandle 3 / exercise 1

## Command history

```bash

z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: team page added "
[ft/team-page 03a84ff] feat: team page added
 2 files changed, 133 insertions(+)
 create mode 100644 bandle 3/exercice1/team.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/team-page
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (8/8), 2.50 KiB | 511.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/team-page
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/team-page -> ft/team-page
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout main
Switched to branch 'main'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/team-page
Switched to branch 'ft/team-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git log
commit 03a84ff64b83105de485004ec7a71a4257cb6af7 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Wed Oct 12 16:23:21 2022 +0200

    feat: team page added

commit 0ed3b95dbbbc2204ea657bc97e17e3e03c7ace91 (origin/ft/service-redesign, ft/service-redesign)
Merge: f3c8a33 0dc0852
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:41:33 2022 +0200

    conflict resolved in service page

commit 0dc085206caaf2e9ba6c4ccdf3cdc97907c103d5 (origin/main, main, ft/contact-page)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:30:19 2022 +0200

    content added in service page

commit f3c8a333e33a84be4e3d787556f361434ae0e75b
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:26:53 2022 +0200

    content added in service page

commit d12c5511b32ee48b41f4cda5065043b30b61fb0f
Merge: 09af14d 8451672
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Tue Oct 11 17:08:35 2022 +0200

    Merge pull request #1 from Jonath-z/ft/bundle-2

    Ft/bundle 2

commit 8451672aec089d4773216065aad1d66f3327a02e (origin/ft/bundle-2, ft/bundle-2)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:52:23 2022 +0200

    eadme renamed to README

commit 6868ebd18182f14fc7c986ec01d34a53c1334c4a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:50:47 2022 +0200

    readme renamed to README

commit b7c52e14dd847b2ca12244e683ead9ccf0f90ff8
Merge: 1ea5146 09af14d
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:44:43 2022 +0200

    exercice-1 moved to the exercise 1 folder

commit 1ea5146114d0c80b3ba506c954157ecae50bf68a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:16:45 2022 +0200

    service page added

commit 09af14d0dfa3891409a684f434f1a5d17ee0e11d
Author: @Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 08:42:28 2022 +0200

    Update exercise-1.md

commit 055ecac1c22317799eb164dcf7bb613efb34b842 (origin/dev, dev)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 20:47:03 2022 +0200
Date:   Mon Oct 10 20:47:03 2022 +0200

    file structered

commit 7ec3f8bea87655658baef702c350d9bc1b460965
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 19:26:04 2022 +0200

    exercise two

commit 0783471a1aa14a22461c531a322fadd78f7d57c8
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:39 2022 +0200

    files stuctured by bandle/exercise

commit fa7eccdaaa3f030f5ec8d8a6a18306876425b603
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:07 2022 +0200

    files stuctured by bandle/exercise

commit 63565391a8e6af916992d7d314c36f7a1e032f0a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 16:26:24 2022 +0200

    git exercise 1

z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git cherry-pick 03a84ff64b83105de485004ec7a71a4257cb6af7
[ft/contact-page 1add68f] feat: team page added
 Date: Wed Oct 12 16:23:21 2022 +0200
 2 files changed, 133 insertions(+)
 create mode 100644 bandle 3/exercice1/team.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: ft/team-page last commint applied to ft/contact-page"
On branch ft/contact-page
nothing to commit, working tree clean
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/contact-page
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (8/8), 2.50 KiB | 365.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/contact-page
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/contact-page -> ft/contact-page
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: faq page added"
[ft/faq-page a92a33f] feat: faq page added
 1 file changed, 10 insertions(+)
 create mode 100644 bandle 3/exercice1/faq.html
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/faq-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 611 bytes | 203.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Jonath-z/the-GYM-git-exercises/pull/new/ft/faq-page
remote:
To https://github.com/Jonath-z/the-GYM-git-exercises.git
 * [new branch]      ft/faq-page -> ft/faq-page
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git log
commit a92a33f221082f5803cc0f078f1053bd392bab47 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Wed Oct 12 17:19:29 2022 +0200

    feat: faq page added

commit 1add68fd374dea38b6d0f6313805687a551ad871 (origin/ft/contact-page, ft/contact-page)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Wed Oct 12 16:23:21 2022 +0200

    feat: team page added

commit 0dc085206caaf2e9ba6c4ccdf3cdc97907c103d5 (origin/main, main)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:30:19 2022 +0200

    content added in service page

commit d12c5511b32ee48b41f4cda5065043b30b61fb0f
Merge: 09af14d 8451672
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Tue Oct 11 17:08:35 2022 +0200

    Merge pull request #1 from Jonath-z/ft/bundle-2

    Ft/bundle 2

commit 8451672aec089d4773216065aad1d66f3327a02e (origin/ft/bundle-2, ft/bundle-2)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:52:23 2022 +0200

    eadme renamed to README

commit 6868ebd18182f14fc7c986ec01d34a53c1334c4a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:50:47 2022 +0200

    readme renamed to README

commit b7c52e14dd847b2ca12244e683ead9ccf0f90ff8
Merge: 1ea5146 09af14d
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:44:43 2022 +0200

    exercice-1 moved to the exercise 1 folder

commit 1ea5146114d0c80b3ba506c954157ecae50bf68a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:16:45 2022 +0200

    service page added

commit 09af14d0dfa3891409a684f434f1a5d17ee0e11d
Author: @Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 08:42:28 2022 +0200

    Update exercise-1.md

commit 055ecac1c22317799eb164dcf7bb613efb34b842 (origin/dev, dev)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 20:47:03 2022 +0200

    file structered

commit 7ec3f8bea87655658baef702c350d9bc1b460965
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 19:26:04 2022 +0200

    exercise two

commit 0783471a1aa14a22461c531a322fadd78f7d57c8
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:39 2022 +0200

    files stuctured by bandle/exercise

commit fa7eccdaaa3f030f5ec8d8a6a18306876425b603
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:07 2022 +0200

    files stuctured by bandle/exercise

commit 63565391a8e6af916992d7d314c36f7a1e032f0a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 16:26:24 2022 +0200

    git exercise 1
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/faq-page
Already on 'ft/faq-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git chekout ft/team-page
git: 'chekout' is not a git command. See 'git --help'.

The most similar command is
        checkout
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/team-page
Switched to branch 'ft/team-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git log
commit 03a84ff64b83105de485004ec7a71a4257cb6af7 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Wed Oct 12 16:23:21 2022 +0200

    feat: team page added

commit 0ed3b95dbbbc2204ea657bc97e17e3e03c7ace91 (origin/ft/service-redesign, ft/service-redesign)
Merge: f3c8a33 0dc0852
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:41:33 2022 +0200

    conflict resolved in service page

commit 0dc085206caaf2e9ba6c4ccdf3cdc97907c103d5 (origin/main, main)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:30:19 2022 +0200

    content added in service page

commit f3c8a333e33a84be4e3d787556f361434ae0e75b
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 18:26:53 2022 +0200

    content added in service page

commit d12c5511b32ee48b41f4cda5065043b30b61fb0f
Merge: 09af14d 8451672
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Tue Oct 11 17:08:35 2022 +0200

    Merge pull request #1 from Jonath-z/ft/bundle-2

    Ft/bundle 2

commit 8451672aec089d4773216065aad1d66f3327a02e (origin/ft/bundle-2, ft/bundle-2)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:52:23 2022 +0200

    eadme renamed to README

commit 6868ebd18182f14fc7c986ec01d34a53c1334c4a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:50:47 2022 +0200

    readme renamed to README

commit b7c52e14dd847b2ca12244e683ead9ccf0f90ff8
Merge: 1ea5146 09af14d
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:44:43 2022 +0200

    exercice-1 moved to the exercise 1 folder

commit 1ea5146114d0c80b3ba506c954157ecae50bf68a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 16:16:45 2022 +0200

    service page added

commit 09af14d0dfa3891409a684f434f1a5d17ee0e11d
Author: @Jonath-z <jonathanzihindula95@gmail.com>
Date:   Tue Oct 11 08:42:28 2022 +0200

    Update exercise-1.md

commit 055ecac1c22317799eb164dcf7bb613efb34b842 (origin/dev, dev)
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 20:47:03 2022 +0200

    file structered

commit 7ec3f8bea87655658baef702c350d9bc1b460965
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 19:26:04 2022 +0200

    exercise two

commit 0783471a1aa14a22461c531a322fadd78f7d57c8
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:39 2022 +0200

    files stuctured by bandle/exercise

commit fa7eccdaaa3f030f5ec8d8a6a18306876425b603
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 17:12:07 2022 +0200

    files stuctured by bandle/exercise

commit 63565391a8e6af916992d7d314c36f7a1e032f0a
Author: Jonath-z <jonathanzihindula95@gmail.com>
Date:   Mon Oct 10 16:26:24 2022 +0200

    git exercise 1
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git revert 03a84ff64b83105de485004ec7a71a4257cb6af7
Removing bandle 3/exercice1/team.html
[ft/faq-page 0b2289c] Revert "feat: team page added"
 2 files changed, 54 insertions(+), 187 deletions(-)
 delete mode 100644 bandle 3/exercice1/team.html
 rewrite bandle-2/exercise 1/README.md (72%)
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .,
fatal: pathspec '.,' did not match any files
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git add .
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git commit -m "feat: faq page added"
On branch ft/faq-page
nothing to commit, working tree clean
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$ git push origin ft/faq-page
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 607 bytes | 303.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Jonath-z/the-GYM-git-exercises.git
   a92a33f..0b2289c  ft/faq-page -> ft/faq-page
z-001@z001-ThinkPad-T460s:~/the-GYM-git-exercises.git$

```
