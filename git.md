## Use git checkout --ours / --theirs to keep 1 version
http://www.kevinold.com/2009/02/24/better-git-conflict-resolution-between-binaries-with-theirs.html

## Undo changes during a git rebase -i

git checkout HEAD -- path/to/file/

## Cancel a git add, http://stackoverflow.com/a/3688108
git reset HEAD -- .

## partly cherry-picking, get a patch, but don't commit (-n = --no-commit )
git cherry-pick -n 

## preview a stash before applying it
git stash list
git stash show -p stash@{1}
git stash apply stash@{1}
