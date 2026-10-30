# 07 — Undoing changes and recovering work

Choose a command based on what you want to undo:

| Situation | Command |
|---|---|
| Unstage a file | `git restore --staged file` |
| Discard unstaged edits | `git restore file` |
| Create a new commit that reverses an old commit | `git revert <commit>` |
| Move branch pointer (careful) | `git reset <mode> <commit>` |
| Find prior HEAD positions | `git reflog` |

`git revert` is usually safer for shared history because it adds a new reversing commit. `git reset --hard` discards tracked working-tree changes. Practice reset and reflog only in a disposable repository first.

Exercise: make a commit, reset a test branch, then recover the commit using reflog.
