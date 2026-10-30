# 01 — Installation and configuration

Install Git from https://git-scm.com/downloads, then verify:
```bash
git --version
```

Set your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list --show-origin
```

Useful defaults:
```bash
git config --global init.defaultBranch main
git config --global core.editor "code --wait"
```

The editor command assumes VS Code is installed and available on PATH. Skip it if not applicable.

Inspect scopes:
- `--system`: machine-wide configuration
- `--global`: user configuration
- local repository config: `.git/config`

Exercise: set your identity, inspect where it is stored, and explain which scope takes precedence.
