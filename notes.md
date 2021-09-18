
```


StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching    
$ git clone git@github.com:amaddatu/monkey-patching.git .
Cloning into '.'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (main)
$ mkdir -p assets/js

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (main)
$ touch index.html assets/js/main.js

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (main)
$ git checkout -b anthony
Switched to a new branch 'anthony'

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (main)
$ git checkout anthony
Switched to branch 'anthony'

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)
$ git add -A

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)
$ git commit -m "Add initial files"
[anthony 61c9879] Add initial files
 2 files changed, 13 insertions(+)
 create mode 100644 assets/js/main.js
 create mode 100644 index.html

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git push
fatal: The current branch anthony has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin anthony


StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git push --set-upstream origin anthony
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 642 bytes | 214.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'anthony' on GitHub by visiting:
remote:      https://github.com/amaddatu/monkey-patching/pull/new/anthony
remote:
To github.com:amaddatu/monkey-patching.git
 * [new branch]      anthony -> anthony
Branch 'anthony' set up to track remote branch 'anthony' from 'origin'.

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git add -A

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git commit -m "Add an einstein quote and more logs"
[anthony 9f28c68] Add an einstein quote and more logs
 1 file changed, 2 insertions(+), 1 deletion(-)

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 439 bytes | 219.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:amaddatu/monkey-patching.git
   61c9879..9f28c68  anthony -> anthony

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$ git pull origin main
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 13 (delta 3), reused 4 (delta 1), pack-reused 0
Unpacking objects: 100% (13/13), 3.04 KiB | 3.00 KiB/s, done.
From github.com:amaddatu/monkey-patching
 * branch            main       -> FETCH_HEAD
   4d0ccb3..fd13a26  main       -> origin/main
Updating 9f28c68..fd13a26
Fast-forward
 assets/js/main.js | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

StreamMachine@Stream-Machine MINGW64 /g/workspace/fsf-aug-2021/project-work/monkey-patching (anthony)       
$
```
