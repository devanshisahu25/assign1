This repository contains the complete assignment 1 of DevOps 
---
1. **Local Repository Initialization & Branch Setup**: Created and initialized a local Git repository, configured the default `main` branch, tracked initial assets, and contrasted unstaging workflows using `git restore --staged` vs. `git reset HEAD`.
2. **Remote Synchronization & GitHub Web Operations**: Linked the remote repository, pushed initial commits, pulled remote web edits using `git pull origin main`, staged multiple files, and performed selective unstaging.
3. **Branching & Pull Request Workflow**: Created remote branch `g1`, checked it out locally via `git fetch` and `git checkout`, committed `g1_file.txt`, and successfully merged a clean Pull Request into `main`.
4. **Local Inspection, Resets & Interactive Staging**: Executed `git fetch` and `git merge origin/main`, tested soft reset (`git reset --soft HEAD~1`), hard reset (`git reset --hard HEAD~1`), inspected branch differences (`git diff main g1`), managed divergent branches (`b1`, `b2`, `b3`), and performed mixed resets alongside interactive hunk staging (`git add -p`).
5. **Merge Conflict Resolution & Cleanup**: Intentionally introduced a content collision in `initial.txt` between branches `b3` and `b2`, resolved conflict markers manually, completed successive branch merges (`b3` -> `b2` -> `b1` -> `main`), and cleaned up local and remote branches (`git branch -d`, `git push origin --delete`).
6. **Fork Management & Cross-Repo PR**: Forked the repository into an organization workspace, cloned the fork locally, committed `forked.txt`, and raised a Pull Request from the fork back to the upstream `main` branch.
7. **Advanced Unstaging, Stash & Recovery**: Performed multi-file unstaging, interactive patch staging, provoked and resolved a stash-pop collision, executed file deletion tracking via `git rm`, and safely reverted commits using `git revert`.

---

**Question 3 PR (Branch `g1` -> `main`)**:
  [https://github.com/devanshisahu25/assign1/pull/1](https://github.com/devanshisahu25/assign1/pull/1)
**Question 6 PR (Forked `assign1` -> Original `main`)**:
  [https://github.com/devanshisahu25/assign1/pull/2](https://github.com/devanshisahu25/assign1/pull/2)
