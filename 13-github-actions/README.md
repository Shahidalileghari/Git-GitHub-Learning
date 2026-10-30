# 13 — GitHub Actions basics

GitHub Actions automates repository workflows using YAML files under `.github/workflows/`.

The sample workflow in this repository runs on push and pull request events. It checks out code, configures Git, and runs a small shell validation.

Understand:
- workflow, event, job, runner, step, action
- `permissions` and least privilege
- secrets and environment protection
- dependency pinning and supply-chain considerations
- status checks as merge requirements

Never echo secrets into logs. Grant only the permissions a workflow needs.
