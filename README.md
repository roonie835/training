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

anveshsahu@LOXTIPL00006226 MINGW64 ~
$ git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

anveshsahu@LOXTIPL00006226 MINGW64 ~
$ ls
'3D Objects'/
 Anaconda3/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 K16AV13.0.1.0.SGBINXM.log
 Links/
'Local Settings'@
 Microsoft/
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Untitled.ipynb
 Videos/
'global AI scene'/
 logcatJ6A.log
 logcatJ6A13.log
 logcatK6T0.1.log
 logcatK6T0.5.0.log
 logcatL19A.log
 logcatL19A2.log
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 shell.docx

anveshsahu@LOXTIPL00006226 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/anveshsahu/.git/

anveshsahu@LOXTIPL00006226 MINGW64 ~ (master)
$ ls .a
ls: cannot access '.a': No such file or directory

anveshsahu@LOXTIPL00006226 MINGW64 ~ (master)
$ cd downloads

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads (master)
$ mkdir newproject

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads (master)
$ cd newproject

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .a
ls: cannot access '.a': No such file or directory

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git init
Initialized empty Git repository in C:/Users/anveshsahu/Downloads/newproject/.git/

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .a
ls: cannot access '.a': No such file or directory

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .a
ls: cannot access '.a': No such file or directory

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git init
Reinitialized existing Git repository in C:/Users/anveshsahu/Downloads/newproject/.git/

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .a
ls: cannot access '.a': No such file or directory

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cd..
bash: cd..: command not found

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls -a
./  ../  .git/

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .git
HEAD  config  description  hooks/  info/  objects/  refs/

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ touch names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ gti status
bash: gti: command not found

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        names.txt

nothing added to commit but untracked files present (use "git add" to track)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   names.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ gti commi -m "names.txt is added"
bash: gti: command not found

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "names.txt is added"
\[master (root-commit) becbec4] names.txt is added
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ vim names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cat names.txt
anvesh sahu
sachin tendulkar
lewis hamilton

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   names.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ gti add .
bash: gti: command not found

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   names.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .
warning: in the working copy of 'names.txt', LF will be replaced by CRLF the next time Git touches it

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   names.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ gti restore --staged names.txt
bash: gti: command not found

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git restore --staged names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   names.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .
warning: in the working copy of 'names.txt', LF will be replaced by CRLF the next time Git touches it

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   names.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "file is added again"
[master f3055ae] file is added again
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 insertions(+)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit f3055aebe2cfde3d1180d9aea8ea0f5aa0e0d008 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:50:04 2022 +0530

    file is added again

commit becbec4daad1ae8fa7ac583ff977738c2ff1b796
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ rm -rf names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    names.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "file is deleted"
[master 64129dc] file is deleted
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 deletions(-)
 delete mode 100644 names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit 64129dc4ecaa1c22dc646894f70a2df264b2bbf6 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:54:09 2022 +0530

    file is deleted

commit f3055aebe2cfde3d1180d9aea8ea0f5aa0e0d008
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:50:04 2022 +0530

    file is added again

commit becbec4daad1ae8fa7ac583ff977738c2ff1b796
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git reset becbec4daad1ae8fa7ac583ff977738c2ff1b796
Unstaged changes after reset:
D       names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit becbec4daad1ae8fa7ac583ff977738c2ff1b796 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    names.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    names.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ touch surnames.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    names.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        surnames.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ vim surnames.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ touch houses.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .
warning: in the working copy of 'surnames.txt', LF will be replaced by CRLF the next time Git touches it

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    names.txt -> houses.txt
        new file:   surnames.txt


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git stash
Saved working directory and index state WIP on master: becbec4 names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit becbec4daad1ae8fa7ac583ff977738c2ff1b796 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cat names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git stash pop
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   houses.txt
        new file:   surnames.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    names.txt

Dropped refs/stash@{0} (658720828b1574392841f9ac4a0cdf9f0f392e05)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git stash
Saved working directory and index state WIP on master: becbec4 names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git stash clear

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls
names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cat names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit becbec4daad1ae8fa7ac583ff977738c2ff1b796 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git remote add origin https://github.com/roonie835/firstrepo.git

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git remote -v
origin  https://github.com/roonie835/firstrepo.git (fetch)
origin  https://github.com/roonie835/firstrepo.git (push)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/roonie835/firstrepo.git
 * [new branch]      master -> master

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ touch hotel.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit-m "hotel is added"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "hotel is added"
[master 6c0f508] hotel is added
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hotel.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ touch rollno.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "rollno is added"
[master 1d8533a] rollno is added
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 rollno.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ vim rollno.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   rollno.txt

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git add .
warning: in the working copy of 'rollno.txt', LF will be replaced by CRLF the next time Git touches it

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git commit -m "rollno is modified"
[master a1b2179] rollno is modified
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit a1b217949ea9092d3dfd673ce2e99e0f88008716 (HEAD -> master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:24:34 2022 +0530

    rollno is modified

commit 1d8533a322c88bdf4bf2dbcedaff55584a10d5c4
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:23:14 2022 +0530

    rollno is added

commit 6c0f5084db2a70785e5beb6bf33d763536da3faa
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:22:42 2022 +0530

    hotel is added

commit becbec4daad1ae8fa7ac583ff977738c2ff1b796 (origin/master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls .git
COMMIT_EDITMSG  ORIG_HEAD  description  index  logs/     refs/
HEAD            config     hooks/       info/  objects/

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git push origin master
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 646 bytes | 323.00 KiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/roonie835/firstrepo.git
   becbec4..a1b2179  master -> master

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git log
commit a1b217949ea9092d3dfd673ce2e99e0f88008716 (HEAD -> master, origin/master)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:24:34 2022 +0530

    rollno is modified

commit 1d8533a322c88bdf4bf2dbcedaff55584a10d5c4
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:23:14 2022 +0530

    rollno is added

commit 6c0f5084db2a70785e5beb6bf33d763536da3faa
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 11:22:42 2022 +0530

    hotel is added

commit becbec4daad1ae8fa7ac583ff977738c2ff1b796
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 10:46:17 2022 +0530

    names.txt is added

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ^C

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git clone https://github.com/roonie835/commclassroomOP.git
Cloning into 'commclassroomOP'...
remote: Enumerating objects: 35, done.
remote: Total 35 (delta 0), reused 0 (delta 0), pack-reused 35
Receiving objects: 100% (35/35), 8.82 KiB | 602.00 KiB/s, done.
Resolving deltas: 100% (7/7), done.

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cd commclassroomop

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ ls
README.md

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ cd

anveshsahu@LOXTIPL00006226 MINGW64 ~ (master)
$ cd downloads

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads (master)
$ cd newproject

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git remote add upstream https://github.com/roonie835/commclassroomOP.git

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ git remote -v
origin  https://github.com/roonie835/firstrepo.git (fetch)
origin  https://github.com/roonie835/firstrepo.git (push)
upstream        https://github.com/roonie835/commclassroomOP.git (fetch)
upstream        https://github.com/roonie835/commclassroomOP.git (push)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ ls
commclassroomOP/  hotel.txt  names.txt  rollno.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject (master)
$ cd commclassroomop

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ ls
README.md

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ cat readme.md
# Community Classroom is OP

- Kunal Kushwaha says that this community is amazing.
- More power to kunal. love the work which your are doing for the community.
- Anirudh Sharma finds the Community Classroom initiative really great!

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ vi readme.md

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git branch anvesh

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git checkout anvesh
Switched to branch 'anvesh'
M       README.md

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git commit -m "anvesh added a message"
[anvesh af40305] anvesh added a message
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 2 insertions(+), 1 deletion(-)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git log
commit af40305e66fe0ede4391d37b53c1592355640975 (HEAD -> anvesh)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 16:53:36 2022 +0530

    anvesh added a message

commit 49f66576100aa1e9cfb436548c73adc3609d47bf (origin/main, origin/HEAD, main)
Merge: 0d9e167 9f573b6
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:26 2021 +0530

    Merge pull request #26 from R11manish/greeting

    greetings

commit 9f573b6cb721ca734b183a29bd577722804901ef
Merge: e134a1e 0d9e167
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:20 2021 +0530

    Merge branch 'main' into greeting

commit 0d9e16703d23abada8605d45091d0d90adbfc299
Merge: 642eabd 8b41812
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:34:59 2021 +0530

    Merge pull request #27 from AnirudhBot/Anirudh_Sharma

    Anirudh modified readme

commit e134a1e374a669bfcd138cf139eae576240f89a4
Author: Manish Rawat <github.jmtss@gmail.com>
Date:   Sun Aug 1 18:31:24 2021 +0530

    greetings

commit 8b41812b3dbd43755ca986b0e37dfe0314e2134e
Author: Anirudh Sharma <anirudh1304@gmail.com>
Date:   Sun Aug 1 18:15:04 2021 +0530

:...skipping...
commit af40305e66fe0ede4391d37b53c1592355640975 (HEAD -> anvesh)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 16:53:36 2022 +0530

    anvesh added a message

commit 49f66576100aa1e9cfb436548c73adc3609d47bf (origin/main, origin/HEAD, main)
Merge: 0d9e167 9f573b6
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:26 2021 +0530

    Merge pull request #26 from R11manish/greeting

    greetings

commit 9f573b6cb721ca734b183a29bd577722804901ef
Merge: e134a1e 0d9e167
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:20 2021 +0530

    Merge branch 'main' into greeting

commit 0d9e16703d23abada8605d45091d0d90adbfc299
Merge: 642eabd 8b41812
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:34:59 2021 +0530

    Merge pull request #27 from AnirudhBot/Anirudh_Sharma

    Anirudh modified readme

commit e134a1e374a669bfcd138cf139eae576240f89a4
Author: Manish Rawat <github.jmtss@gmail.com>
Date:   Sun Aug 1 18:31:24 2021 +0530

    greetings

commit 8b41812b3dbd43755ca986b0e37dfe0314e2134e
Author: Anirudh Sharma <anirudh1304@gmail.com>
Date:   Sun Aug 1 18:15:04 2021 +0530

    Anirudh modified readme

    Anirudh modified readme

commit 642eabdf4ffc3533bbbaaedd85a44be11700f924
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 13:08:12 2021 +0530

    Update README.md

commit 1bb5c8484b472a4c9b7fcd965faee2c5b3ea5a3e
Merge: 97d9769 8da5685
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 13:05:39 2021 +0530

    Merge pull request #3 from kunal-kushwaha/temp

    kunal changed line 4

commit 8da568584cee152751162a246296b419e11513e9
Merge: 56039e8 97d9769
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 13:05:08 2021 +0530

    Merge branch 'main' into temp

commit 97d9769a65b87510116cdc64c897a9e3044c71de
:
commit af40305e66fe0ede4391d37b53c1592355640975 (HEAD -> anvesh)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 16:53:36 2022 +0530

    anvesh added a message

commit 49f66576100aa1e9cfb436548c73adc3609d47bf (origin/main, origin/HEAD, main)
Merge: 0d9e167 9f573b6
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:26 2021 +0530

    Merge pull request #26 from R11manish/greeting

    greetings

commit 9f573b6cb721ca734b183a29bd577722804901ef
Merge: e134a1e 0d9e167
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:20 2021 +0530

    Merge branch 'main' into greeting

commit 0d9e16703d23abada8605d45091d0d90adbfc299
Merge: 642eabd 8b41812
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:34:59 2021 +0530

    Merge pull request #27 from AnirudhBot/Anirudh_Sharma

    Anirudh modified readme

commit e134a1e374a669bfcd138cf139eae576240f89a4
Author: Manish Rawat <github.jmtss@gmail.com>
Date:   Sun Aug 1 18:31:24 2021 +0530

    greetings

commit 8b41812b3dbd43755ca986b0e37dfe0314e2134e
Author: Anirudh Sharma <anirudh1304@gmail.com>
Date:   Sun Aug 1 18:15:04 2021 +0530


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git push origin anvesh
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'anvesh' on GitHub by visiting:
remote:      https://github.com/roonie835/commclassroomOP/pull/new/anvesh
remote:
To https://github.com/roonie835/commclassroomOP.git
 * [new branch]      anvesh -> anvesh

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ touch names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git commit -m "names.txt is added"
[anvesh b52ee13] names.txt is added
 Committer: Anwesh Sahu <anveshsahu@xiaomi.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 names.txt

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git push origin anvesh
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 282 bytes | 282.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/roonie835/commclassroomOP.git
   af40305..b52ee13  anvesh -> anvesh

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git status
On branch anvesh
nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git log
commit b52ee13a2ef2c27652cc01adc69e5cd0b49f8479 (HEAD -> anvesh, origin/anvesh)
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 17:02:04 2022 +0530

    names.txt is added

commit af40305e66fe0ede4391d37b53c1592355640975
Author: Anwesh Sahu <anveshsahu@xiaomi.com>
Date:   Wed Aug 31 16:53:36 2022 +0530

    anvesh added a message

commit 49f66576100aa1e9cfb436548c73adc3609d47bf (origin/main, origin/HEAD, main)
Merge: 0d9e167 9f573b6
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:26 2021 +0530

    Merge pull request #26 from R11manish/greeting

    greetings

commit 9f573b6cb721ca734b183a29bd577722804901ef
Merge: e134a1e 0d9e167
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:35:20 2021 +0530

    Merge branch 'main' into greeting

commit 0d9e16703d23abada8605d45091d0d90adbfc299
Merge: 642eabd 8b41812
Author: Kunal Kushwaha <kunalkushwaha453@gmail.com>
Date:   Sun Aug 1 18:34:59 2021 +0530

    Merge pull request #27 from AnirudhBot/Anirudh_Sharma

    Anirudh modified readme

commit e134a1e374a669bfcd138cf139eae576240f89a4
Author: Manish Rawat <github.jmtss@gmail.com>
Date:   Sun Aug 1 18:31:24 2021 +0530


anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git reset af40305e66fe0ede4391d37b53c1592355640975

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git status
On branch anvesh
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        names.txt

nothing added to commit but untracked files present (use "git add" to track)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git add .

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git stash
Saved working directory and index state WIP on anvesh: af40305 anvesh added a message

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git push origin anvesh -f
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/roonie835/commclassroomOP.git
 + b52ee13...af40305 anvesh -> anvesh (forced update)

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git checkou
git: 'checkou' is not a git command. See 'git --help'.

The most similar command is
        checkout

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git status
On branch anvesh
nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git fetch -all --prune
error: did you mean `--all` (with two dashes)?

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git fetch --all --prune

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (anvesh)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git reset --hard upstream/main
fatal: ambiguous argument 'upstream/main': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

anveshsahu@LOXTIPL00006226 MINGW64 ~/downloads/newproject/commclassroomop (main)
$ git
