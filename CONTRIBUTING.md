# Contribution Guide

Use a short, descriptive commit message with a Conventional Commit type such as feat, fix, docs, refactor, or chore.
Local Git hooks check staged files and commit messages before each commit.

## Sharing the hooks

The .git/hooks directory is local to each clone and is not pushed to GitHub. Shared hook scripts are stored in the tracked .githooks/ directory. After cloning, enable them with:

git config core.hooksPath .githooks

The --no-verify option bypasses client-side hooks and should not be used to skip these checks.
