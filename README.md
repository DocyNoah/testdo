# Branch Test

## Add branch
git branch [branch_name]

## Checkout branch
git checkout [branch_name]

## Add and checkout branch
git checkout -b [branch_name]

## Delete local branch
git branch -d [local_branch]

### force
git branch -D [local_branch]

## Delete remote branch
git push [remote_repo] --delete [remote_brnach]

## Pull new remote branch
git checkout -t [remote_repo]/[remote_branch]

## View local branch name
git branch

## View remote branch name
git branch -r

## View all branch name
git branch -a