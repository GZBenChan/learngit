Git is a distributed version control system.
Git is the free software distributed under the GPL.
Git has a mutable index called stage.
Creating a new branch is quick and simple.

Important command:
git branch

git branch <name>

git checkout <name>

git checkout -b <name>

git merge <name>

git branch -d <name>

git log --graph --pretty=oneline --abbrev=commit

git merge <branch name>
git merge --no-ff -m "merge with no-ff" <branch name>

git stash
git stash list
git stash apply git stash drop
git stash pop
git stash apply stash@{0}

git branch -d feature-vulcan
error: The branch 'feature-vulcan' is not fully merged.
If you are sure you want to delete it, run 'git branch -D feature-vulcan'.
