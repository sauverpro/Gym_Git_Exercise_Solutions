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
## *solution 2*

``` bash
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git pull
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Already up to date.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
error: pathspec 'ft/service-redesign' did not match any file(s) known to git

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/service-redesign
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   servises.html


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git commit -m "servises modified"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/service-redesign c1740bd] servises modified
 1 file changed, 2 insertions(+), 1 deletion(-)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 337 bytes | 67.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git checkout main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git pull
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 706 bytes | 0 bytes/s, done.
From https://github.com/sauverpro/Gym_Git_Exercise_Solutions
   4f61719..00ddde4  main       -> origin/main
Updating 4f61719..00ddde4
Updating 4f61719..00ddde4
Updating 4f61719..00ddde4
Fast-forward
 servises.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
Fast-forward
 servises.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout ft/service-redisign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
error: pathspec 'ft/service-redisign' did not match any file(s) known to git

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ 

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git merge main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
$ git merge main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Auto-merging servises.html
#
CONFLICT (content): Merge conflict in servises.html
Automatic merge failed; fix conflicts and then commit the result.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git merge --continue
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/service-redesign d70d841] rrge branch 'main' into ft/service-redesign

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/service-redesign)
$ git push -f
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 248 bytes | 22.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
   c1740bd..d70d841  ft/service-redesign -> ft/service-redesign


```
# Bundle 3

## **solution 1**

``` bash

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git commit -m "this is the team page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/team-page c2e5be1] this is the team page
 1 file changed, 14 insertions(+)
 create mode 100644 team.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/team-page
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 496 bytes | 70.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/team-page
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git checkout main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git checkout ft/team-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
commit c2e5be1822530a01640733257ad80aa2446fda7e (HEAD -> ft/team-page, origin/ft/team-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 01:26:40 2023 +0300

    this is the team page

commit 47d7545be9dd2494fa847773640233452404be88 (main, ft/contact-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 01:16:57 2023 +0300

    bundle 2 selution 2

commit 7c20006e7d97083cdd984077aec93e145eb06efe
:...skipping...
commit c2e5be1822530a01640733257ad80aa2446fda7e (HEAD -> ft/team-page, origin/ft/team-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 01:26:40 2023 +0300

    this is the team page

commit 47d7545be9dd2494fa847773640233452404be88 (main, ft/contact-page)
commit c2e5be1822530a01640733257ad80aa2446fda7e (HEAD -> ft/team-page, origin/ft/team-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 01:26:40 2023 +0300

    this is the team page

commit 47d7545be9dd2494fa847773640233452404be88 (main, ft/contact-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 01:16:57 2023 +0300

    bundle 2 selution 2

commit 7c20006e7d97083cdd984077aec93e145eb06efe
Merge: 00ddde4 d70d841
Author: CYUSA Alain Tresor <alaintresorcyusa683@gmail.com>
Date:   Mon May 15 21:53:07 2023 +0200

    Merge pull request #4 from sauverpro/ft/service-redesign
    

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/team-page)
$ git checkout ft/contact-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/contact-page'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git cherry-pick c2e5be1822530a01640733257ad80aa2446fda7e
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/contact-page a4b2728] this is the team page
 Date: Tue May 16 01:26:40 2023 +0300
 1 file changed, 14 insertions(+)
 create mode 100644 team.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git commit -m "This is contact page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/contact-page 5c5e64c] This is contact page
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 808 bytes | 80.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 808 bytes | 80.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/contact-page        
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git commit -m "feat: faq page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/faq-page f0f9ef2] feat: faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 456 bytes | 50.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/faq-page
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git log
commit f0f9ef24b817e93b3a4aac8224f2af4f0b9764e8 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 11:04:19 2023 +0300

    feat: faq page

commit 5c5e64c46785550f4c4e6a319b086b5e018b1ddb (origin/ft/contact-page, ft/contact-page)
Author: sauvepro <unsauvechriss@gmail.com>
Date:   Tue May 16 02:27:41 2023 +0300

    This is contact page

commit a4b2728a7febd4f2365872fabf74a8f61fc26d9e
Author: sauvepro <unsauvechriss@gmail.com>

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git push
Everything up-to-date
SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git push
Everything up-to-date

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

nothing to commit, working tree clean

```
## **solution 2**

``` bash

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout ft/faq-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git checkout main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git commit -m "feat: home page redesign"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main 44435e2] feat: home page redesign
 1 file changed, 1 insertion(+)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 346 bytes | 1024 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: Bypassed rule violations for refs/heads/main:
remote:
remote: - At least 1 approving review is required by reviewers with write access.
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
   36edd9f..44435e2  main -> main

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (main)
$ git checkout ft/home-page-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/home-page-redesign'

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git rebase main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Successfully rebased and updated refs/heads/ft/home-page-redesign.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/home-page-redesign
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git commit -m "feat: adding description"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/home-page-redesign a5cfec4] feat: adding description
 1 file changed, 2 insertions(+), 1 deletion(-)

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign


SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 335 bytes | 67.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/sauverpro/Gym_Git_Exercise_Solutions/pull/new/ft/home-page-redesign  
remote:
To https://github.com/sauverpro/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/Gym _Git_Exercise_Solutions (ft/home-page-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/home-page-redesign
Your branch is up to date with 'origin/ft/home-page-redesign'.

nothing to commit, working tree clean


```