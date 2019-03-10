This project is just a demo how to use Git

// git init
// git status
// git add
// git commit

// git log   (show log)
// git show  (show detail one commit)
// git diff  (only file modified)

// working directory (Folder working: has files (file has red color))
// staging area      (When commit, files has change at working directory then add into staging area (file has green color))
// git repository    (Save change of commits)

// git checkout -- <file>
// git reset

// git checkout -b <branch> (branching)
// git checkout <branch>
// git merge
A <-- B
git checkout A
git merge B
master <-- feature/dog-class
// git branch -D <branch> (delete a branch)

// git reset --soft <to_comit>  (return status of files commit into staging area (file has green color))
// git reset --mixed <to_comit> (return status of files commit into working directory (file has red color))
// git reset --hard <to_comit>  (delete completed files commit (same discard))

// git revert <comit>

// .gitignore (The purpose is to ignore the files you don't want to commit)