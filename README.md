# Sequence of creating and committing changes
1. git checkout main
1. git pull
1. git checkout -b <new-branch-name>
1. git branch
1. git status
1. git diff
1. git add .
1. git commit -m "commit msg"
1. git push origin <branch-name>
1. gh pr create 
1. (then merge the PR)
1. git pull (to pull remote changes into local)

If your current branch is outdated compared to main branch:
1. git rebase main

Fix merge conflicts, then
1. git add .
1. git rebase --continue
1. git push origin <branch-name> -f


Other handy dandy commands
1. git stash (to stash local changes)
1. git stash pop (to bring back the changes you just stashed)

Other from "oh my zsh" plugin:
1. gaa – git add all
1. gdca – git diff --cached
1. gp – git push
1. gpf! – git push --force
1. grhh – git reset --hard
1. gst – git status

