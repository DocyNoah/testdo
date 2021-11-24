# Branch Test

## Branch
- Add 
  > git branch [branch_name]

- Checkout 
  > git checkout [branch_name]

- Add and Checkout
  > git checkout -b [branch_name]

- Delete
  - local
     > git branch -d [local_branch]
  - local --force
     > git branch -D [local_branch]
  - remote
     > git push [remote_repo] --delete [remote_branch]

- Pull new remote branch
  > git checkout -t [remote_repo]/[remote_branch]

- View
  - local
    > git branch
  - remote branch
    > git branch -r
  - local and remote
    > git branch -a