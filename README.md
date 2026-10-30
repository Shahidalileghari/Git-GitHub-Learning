# Git & GitHub: From Hello to Collaboration

A learning-only, hands-on course that takes you from your first Git repository to collaborative GitHub workflows. This repository is a tutorial and practice lab, not a production software project.

## Learning outcomes
By completing the path, you should be able to:
- Explain Git's working tree, staging area, commits, branches, and object model.
- Configure Git, initialize or clone repositories, and make meaningful commits.
- Inspect history, compare changes, undo mistakes safely, and recover with reflog.
- Work with branches, merges, rebases, conflicts, tags, and releases.
- Use GitHub repositories, issues, discussions, pull requests, reviews, and projects.
- Collaborate through forks, upstream remotes, feature branches, and pull requests.
- Understand GitHub Actions, branch protection concepts, CODEOWNERS, and contribution etiquette.
- Use SSH authentication safely and avoid committing secrets.

## Who this is for
Learners who want to understand Git and GitHub from the first command through real collaboration. No prior Git knowledge is required. Basic terminal familiarity is helpful.

## Quick start
1. Install Git: https://git-scm.com/downloads
2. Create or sign in to a GitHub account: https://github.com/
3. Open a terminal in this repository.
4. Follow `00-start-here/README.md` and work through the numbered modules.
5. Use the practice repository under `practice/hello-git/` for commands.

Check your installation:
```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
Use an email address you intend to associate with your commits. You can use GitHub's private noreply address if preferred.

## Course map
| Module | Topic |
|---|---|
| 00 | Start here: Git vs GitHub |
| 01 | Installation and first configuration |
| 02 | Your first repository and first commit |
| 03 | Working tree, staging, status, diff |
| 04 | Commit history and useful inspection |
| 05 | Branching and merging |
| 06 | Merge conflicts and safe resolution |
| 07 | Undoing changes and recovery |
| 08 | Remotes, clone, push, pull, fetch |
| 09 | GitHub repositories and collaboration |
| 10 | Pull requests, reviews, issues, discussions |
| 11 | Forks and upstream contribution workflow |
| 12 | Rebase, cherry-pick, tags, releases |
| 13 | GitHub Actions and contribution automation |
| 14 | Professional workflows and troubleshooting |

## Suggested study method
- Read one module, then run every command in a disposable practice repository.
- Before destructive commands, inspect `git status` and understand what will be affected.
- Make small commits with clear messages.
- Deliberately create a merge conflict and resolve it.
- Open a practice pull request between two branches or fork your own repository.
- Keep a command journal: command, purpose, expected result, and observed result.

## Important safety rules
- Never commit passwords, API keys, tokens, private keys, `.env` files, or personal data.
- Avoid `git push --force` on shared branches. Prefer `--force-with-lease` only when you understand the consequences and have coordinated with collaborators.
- `git reset --hard` and `git clean -fd` can permanently discard uncommitted work. Inspect first and back up important files.
- Do not rewrite shared history unless the team explicitly agrees.
- A `.gitignore` does not remove files that are already tracked.

## Repository structure
```text
00-start-here/ ... 14-professional-workflows/
practice/hello-git/
cheatsheets/
exercises/
projects/
templates/
docs/
```

## Completion checklist
- [ ] Create a local repository and make three commits.
- [ ] Create a feature branch and merge it.
- [ ] Resolve a real merge conflict.
- [ ] Recover a deleted commit using reflog in a disposable repository.
- [ ] Push a branch to GitHub and open a pull request.
- [ ] Review a pull request and respond to feedback.
- [ ] Fork a repository and contribute through an upstream workflow.
- [ ] Create a tag and GitHub release.
- [ ] Understand a basic GitHub Actions workflow.
