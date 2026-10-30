# 03 — Working tree, staging, and diff

Commands:
```bash
git status
git add file.txt
git add .
git diff
git diff --staged
git restore file.txt
git restore --staged file.txt
```

- Working tree: files currently checked out.
- Staging area/index: proposed content for the next commit.
- `git diff`: unstaged changes.
- `git diff --staged`: staged changes compared with the current commit.

Be careful: `git restore file.txt` discards unstaged edits to that file. Read the diff first.

Exercise: stage only one of two modified files and inspect both diffs.
