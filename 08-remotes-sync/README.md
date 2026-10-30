# 08 — Remotes and synchronization

```bash
git remote -v
git remote add origin https://github.com/OWNER/REPO.git
git fetch origin
git branch -a
git pull --ff-only
git push -u origin main
```

- `fetch` downloads remote objects and updates remote-tracking refs; it does not merge into your current branch.
- `pull` fetches and then integrates changes (merge or rebase depending on configuration/options).
- `push` publishes local commits to a remote.
- `origin` is only a conventional remote name.

Exercise: create a GitHub repository, add it as `origin`, push your local main branch, and verify the remote history.
