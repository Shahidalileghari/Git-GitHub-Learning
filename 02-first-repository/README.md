# 02 — Your first repository

From a new folder:
```bash
mkdir hello-git
cd hello-git
git init
echo "# Hello Git" > README.md
git status
git add README.md
git commit -m "docs: add initial README"
git log --oneline
```

Alternative: clone an existing remote:
```bash
git clone https://github.com/OWNER/REPOSITORY.git
```

A repository contains the working files plus the `.git` database. Do not manually edit `.git`.

Exercise: create `about.txt`, commit it, change it, and commit the second version.
