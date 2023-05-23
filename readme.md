# Git Exercises
This Project will be use to save all the git outputs of my terminal 
## Bundle One

### Exercise One
```bash
belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership
$ mkdir git-exercise

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership
$ cd git-exercise/

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise
$ code .

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise
$ git init
Initialized empty Git repository in C:/Users/belek/Desktop/The GYM Trainership/git-exercise/.git/

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (master)
$ git branch -M main

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.md

nothing added to commit but untracked files present (use "git add" to track)

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$ git add .

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$ git commit -m "setting up my readme.md file"
[main (root-commit) 6d0c393] setting up my readme.md file
 1 file changed, 6 insertions(+)
 create mode 100644 readme.md

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$ git remote add origin https://github.com/TimothyBelekollie/Gym-Git-Exercise-Solutions.git

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 83.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/TimothyBelekollie/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (main)
$

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (dev)
$ git stash save "team stash"
Saved working directory and index state On dev: team stash

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (dev)
$ git stash list
stash@{0}: On dev: team stash
stash@{1}: On dev: about stash
stash@{2}: WIP on dev: 5a164c2 new changes

belek@TimothyBelekoll MINGW64 ~/Desktop/The GYM Trainership/git-exercise (dev)
$ git stash pop stash@{1}
error: Your local changes to the following files would be overwritten by merge:
        readme.md
Please commit your changes or stash them before you merge.
Aborting
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html
        team.html

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.
