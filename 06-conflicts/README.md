# 06 — Merge conflicts

A conflict occurs when Git cannot automatically combine changes.

Workflow:
```bash
git status
# open each conflicted file and resolve conflict markers
git add path/to/resolved-file
git commit
```

Conflict markers:
```text
<<<<<<< HEAD
current branch content
=======
incoming branch content
>>>>>>> feature-branch
```

Do not blindly choose one side. Understand both intentions, edit the final desired content, run relevant checks, then stage the resolution.

Exercise: create a conflict by editing the same line differently on two branches.
