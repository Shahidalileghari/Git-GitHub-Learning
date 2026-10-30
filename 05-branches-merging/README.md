# 05 — Branches and merging

A branch is a lightweight movable name pointing to a commit.

```bash
git switch -c feature/add-intro
# edit files
git add .
git commit -m "docs: add introduction"
git switch main
git merge feature/add-intro
git branch -d feature/add-intro
```

Use branches to isolate work. Merge commits preserve the relationship between histories; fast-forward merges move the branch pointer when possible.

Exercise: create two feature branches and merge both into main.
