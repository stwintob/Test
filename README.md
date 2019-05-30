# Test


Komplette Befehle:


stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1
$ git init
Initialized empty Git repository in H:/Desktop/Test1/.git/

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git add .

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git commit
[master (root-commit) 210b1fb] C1
 Committer: Winkler <stwintob2@dida140600.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 TESST.txt

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git add .

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git commit
[master 0fef79f] C2
 Committer: Winkler <stwintob2@dida140600.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch hotfix

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch iss53

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git checkout iss53
Switched to branch 'iss53'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (iss53)
$ git add .

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (iss53)
$ git commit
[iss53 12fbcf7] C3
 Committer: Winkler <stwintob2@dida140600.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 1 deletion(-)

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (iss53)
$ git checkout hotfix
Switched to branch 'hotfix'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git add .

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git commit
[hotfix a621ca9] C4
 Committer: Winkler <stwintob2@dida140600.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 1 deletion(-)

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git log
commit a621ca951444c74b8217abe48aeef72dbcd0ccb4 (HEAD -> hotfix)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:47:19 2019 +0200

    C4

commit 0fef79fffd892d4d39cedef9b548b3e77b2e3098 (master)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:53 2019 +0200

    C2

commit 210b1fb8be1ca17cc1da508bb3cfa9e77b9ea211
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:14 2019 +0200

    C1

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (help)
$ git checkout master
Switched to branch 'master'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -a
  hotfix
  iss53
* master

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git log
commit 0fef79fffd892d4d39cedef9b548b3e77b2e3098 (HEAD -> master)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:53 2019 +0200

    C2

commit 210b1fb8be1ca17cc1da508bb3cfa9e77b9ea211
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:14 2019 +0200

    C1

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git checkout hotfix
Switched to branch 'hotfix'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git log
commit a621ca951444c74b8217abe48aeef72dbcd0ccb4 (HEAD -> hotfix)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:47:19 2019 +0200

    C4

commit 0fef79fffd892d4d39cedef9b548b3e77b2e3098 (master)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:53 2019 +0200

    C2

commit 210b1fb8be1ca17cc1da508bb3cfa9e77b9ea211
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:14 2019 +0200

    C1

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git log
commit a621ca951444c74b8217abe48aeef72dbcd0ccb4 (HEAD -> hotfix)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:47:19 2019 +0200

    C4

commit 0fef79fffd892d4d39cedef9b548b3e77b2e3098 (master)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:53 2019 +0200

    C2

commit 210b1fb8be1ca17cc1da508bb3cfa9e77b9ea211
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:14 2019 +0200

    C1

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git branch -f hotfix 0fef79
fatal: Cannot force update the current branch.

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (hotfix)
$ git checkout master
Switched to branch 'master'
stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -f hotfix 0fef79

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -f hotfix master

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -f iss53 master

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git checkout iss53
Switched to branch 'iss53'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (iss53)
$ git log
commit 0fef79fffd892d4d39cedef9b548b3e77b2e3098 (HEAD -> iss53, master, hotfix)
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:53 2019 +0200

    C2

commit 210b1fb8be1ca17cc1da508bb3cfa9e77b9ea211
Author: Winkler <stwintob2@dida140600.local>
Date:   Thu May 30 09:45:14 2019 +0200

    C1

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (iss53)
$ git checkout master
Switched to branch 'master'

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -D iss53
Deleted branch iss53 (was 0fef79f).

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git branch -D hotfix
Deleted branch hotfix (was 0fef79f).

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git remote add origin https://github.com/stwintob/Test.git

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 422 bytes | 32.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/stwintob/Test.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

stwintob2@140600WPC2008 MINGW64 /h/Desktop/Test1 (master)
$
