# 11 — Forks and upstream collaboration

Fork workflow:
```bash
git clone https://github.com/YOUR-USERNAME/PROJECT.git
cd PROJECT
git remote add upstream https://github.com/ORIGINAL-OWNER/PROJECT.git
git remote -v
git fetch upstream
git switch -c docs/fix-example
# make a focused change
git add .
git commit -m "docs: clarify setup example"
git push -u origin docs/fix-example
```

Then open a pull request from your fork's branch to the original repository's target branch.

Keep your fork synchronized:
```bash
git fetch upstream
git switch main
git merge upstream/main
git push origin main
```

Respect contribution guidelines and the project's code of conduct. Do not open low-quality or unrelated PRs merely to increase activity.
