# git-rebase

- Commit all changes in feature branch
- Switch to `main` branch and pull new changes
- Switch back to feature branch, type `git rebase main` (Sourcetree rebase current changes onto main)
- Follow rebase instructions
- Delete feature branch if it exists on `origin`
- Push feature branch to `origin`
- Create PR to merge `feature` branch into `main` branch
- `squash and merge` to keep all commits history (usefull when need `cherry pick`)
