# 14 — Professional workflows and troubleshooting

## A practical feature workflow
1. Update local main from the remote.
2. Create a short-lived feature branch.
3. Make small, coherent commits.
4. Run tests and inspect the final diff.
5. Push the branch and open a focused PR.
6. Respond to review feedback.
7. Merge according to team policy.
8. Delete the feature branch and update local main.

## Troubleshooting
- Wrong author: inspect `git config --list --show-origin`.
- Detached HEAD: create a branch if you need to keep new commits.
- Push rejected: fetch and integrate remote changes; do not blindly force-push.
- Accidentally committed secret: revoke/rotate the credential immediately; deleting the file in a later commit does not erase it from history.
- Untracked file not ignored: check whether the file is already tracked and inspect `.gitignore` patterns.

## Team etiquette
Write focused PRs, explain trade-offs, review kindly, keep issues actionable, and communicate before changing shared history.
