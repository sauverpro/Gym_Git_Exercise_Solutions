# Git Exercises Solution
## ***Bundle 1***
### *solution 1*
``` bash

$ git init

Initialized empty Git repository in E:/ojemba/git/Gym _Git_Exercise_Solutions/.git/

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (master)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (master)
$ git add README.md
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (master)
$ git branch -M main

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git add README.md
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git commit -m "First Commit on README file for solution one"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main (root-commit) aaf46be] First Commit on README file for solution one
 1 file changed, 3 insertions(+)
 create mode 100644 README.md

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git commit -m "modifying README File"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main 72db96f] modifying README File
 1 file changed, 1 insertion(+), 1 deletion(-)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git remote add origin https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 526 bytes | 8.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git branch -b dev
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/dev
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      dev -> dev

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git checkout -b test
Switched to a new branch 'test'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (test)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch test
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (test)
$ git pus origin test
git: 'pus' is not a git command. See 'git --help'.

The most similar commands are
        push
        pull

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/test
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      test -> test

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (test)
$ git checkout dev
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'dev'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git branch -D test
Deleted branch test (was 72db96f).

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git push origin --delete test
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 - [deleted]         test
```
### *solution 2*

``` bash

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 72db96f modifying README File
stash@{1}: WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 72db96f modifying README File
stash@{1}: WIP on dev: 72db96f modifying README File
stash@{2}: WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash pop stash@{1}
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (ad8fe04f78dd743e545fbfcb3449b7cc85e4e866)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 72db96f modifying README File
stash@{1}: WIP on dev: 72db96f modifying README File

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash pop stash@{1}
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (4fa6770656c116b8ace76f9cec9fb9362e97bb63)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git commit about.html -m "about page first commit"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[dev 0c80edb] about page first commit
 1 file changed, 13 insertions(+)
 create mode 100644 about.html
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git commit home.html -m "home page first commit"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[dev a1ae140] home page first commit
 1 file changed, 14 insertions(+)
 create mode 100644 home.html
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 777 bytes | 194.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
   72db96f..a1ae140  dev -> dev
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.
nothing to commit, working tree clean
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 72db96f modifying README File
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git stash pop
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html
Dropped refs/stash@{0} (cc1292e490bc63b83c6d31106457ffaf16461c3c)
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git reset --hard
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
HEAD is now at a1ae140 home page first commit
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.
nothing to commit, working tree clean
```
## ***Bundle 2***
### *solution 1*

``` bash

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (dev)
$ git checkout -b ft/-bundle-2
Switched to a new branch 'ft/-bundle-2'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/-bundle-2)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/-bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        servises.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/-bundle-2)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/-bundle-2)
$ git commit -m "this the servise page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/-bundle-2 6161c4d] this the servise page
 1 file changed, 14 insertions(+)
 create mode 100644 servises.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/-bundle-2)
$ git push
fatal: The current branch ft/-bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/-bundle-2


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/-bundle-2)
$ git push --set-upstream origin ft/-bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 510 bytes | 13.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/-bundle-2' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/-bundle-2
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/-bundle-2 -> ft/-bundle-2
branch 'ft/-bundle-2' set up to track 'origin/ft/-bundle-2'.

```