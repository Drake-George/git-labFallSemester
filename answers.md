answer 1:
git version 2.34.1

answer 2:
user.name=Drake-George
user.email=dg872123@ohio.edu

answer 3:
       This command updates the index using the current content found in the working tree, to prepare the content
       staged for the next commit. It typically adds the current content of existing paths as a whole, but with
       some options it can also be used to add content with only part of the changes made to the working tree files
       applied, or remove paths that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working tree, and it is this snapshot that is taken as
       the contents of the next commit. Thus after making any changes to the working tree, and before running the
       commit command, you must use the add command to add any new or modified files to the index.

       This command can be performed multiple times before a commit. It only adds the content of the specified
       file(s) at the time the add command is run; if you want subsequent changes included in the next commit, then
       you must run git add again to add the new content to the index.

       The git status command can be used to obtain a summary of which files have changes that are staged for the
       next commit.

       The git add command will not add ignored files by default. If any ignored files were explicitly specified on
       the command line, git add will fail with a list of ignored files. Ignored files reached by directory
       recursion or filename globbing performed by Git (quote your globs before the shell) will be silently
       ignored. The git add command can be used to add ignored files with the -f (force) option.

       Please see git-commit(1) for alternative ways to add content to a commit.


answer 4:

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)


answer 5:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)
dgeorge@odd13:~/git-lab$ git add README.md
dgeorge@odd13:~/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md


answer 6:

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md


answer 7:

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md

dgeorge@odd13:~/git-lab$ git commit -m "Initial commit"
[master (root-commit) d338e57] Initial commit
 2 files changed, 87 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
dgeorge@odd13:~/git-lab$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

answer 8:
commit d338e5774722bf4b10825eef40d0bc4af3e0cbb0 (HEAD -> master)
Author: Drake-George <dg872123@ohio.edu>
Date:   Fri Sep 6 16:46:16 2024 -0400

    Initial commit
dgeorge@odd13:~/git-lab$ 


answer 9:

Command 'gti' not found, did you mean:
  command 'gtg' from snap getting-things-gnome (0.6)
  command 'gmi' from deb lieer (1.3-6)
  command 'gt5' from deb gt5 (1.5.0~20111220+bzr29-4)
  command 'gth' from deb genomethreader (1.7.3+dfsg-6)
  command 'gli' from deb ruby-gli (2.14.0-1.1)
  command 'ti' from deb ticgit (1.0.2.17-2.1)
  command 'bti' from deb bti (034-6)
  command 'gsi' from deb gambc (4.9.3-1.2)
  command 'ghi' from deb ghi (1.2.0-1.1)
  command 'git' from deb git (1:2.34.1-1ubuntu1.11)
  command 'gt' from deb genometools (1.6.2+ds-2)
  command 'gtf' from deb xserver-xorg-core (2:21.1.4-2ubuntu1.7~22.04.11)
See 'snap info <snapname>' for additional versions.

answer 10:

Dg872123@ohio.edu
I recorded my answers under the answers.md file

answer 11:

! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Drake-George/git-labFallSemester.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

answer 12:

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1023 bytes | 28.00 KiB/s, done.
From https://github.com/Drake-George/git-labFallSemester
   cd78af3..b7330bf  main       -> origin/main
Updating cd78af3..b7330bf
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
dgeorge@odd13:~/git-lab$ 


answer 13:
.  ..  git-lab-2FallSemester  Labs
I Named it different than the recommended due to having a previous file already named git-lab-2
