# `gh issue-branch` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension that switches to a branch with
issue number and title (and creates if it doesn't exist)

## Usage

```
gh issue-branch <issue_number>
```

It will switch to a branch following the structure `issue/<issue_number>-<sanitized_issue_title>`
