# 04 — Commit history and inspection

```bash
git log --oneline --graph --decorate --all
git show HEAD
git show <commit>
git diff HEAD~1 HEAD
git blame README.md
git status --short
```

A commit has an ID, author metadata, message, tree, and parent reference(s). Branch names are movable references to commits.

Exercise: find the commit that introduced a line and inspect the full change.
