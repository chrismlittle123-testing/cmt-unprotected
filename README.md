# cmt-unprotected

Test repository for check-my-toolkit branch protection checks.

This repo has **NO** branch protection configured, so the repo check should fail.

## Configuration

```toml
[process.repo]
enabled = true
require_branch_protection = true
```
