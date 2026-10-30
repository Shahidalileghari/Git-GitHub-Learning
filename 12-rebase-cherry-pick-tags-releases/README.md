# 12 — Rebase, cherry-pick, tags, and releases

```bash
git switch feature
git fetch origin
git rebase origin/main
git cherry-pick <commit>
git tag -a v1.0.0 -m "First learning release"
git push origin v1.0.0
```

Rebase replays commits onto a new base and rewrites commit IDs. Avoid rebasing commits that others are already using unless coordinated. Cherry-pick applies a selected commit onto the current branch. Tags mark specific points in history; annotated tags are useful for releases.

Exercise: rebase a private feature branch, then create an annotated tag and publish a GitHub release.
