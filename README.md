shfmt mirror
================

Mirror of shfmt shell linter for pre-commit. Created with [pre-commit-mirror-maker](https://github.com/pre-commit/pre-commit-mirror-maker).

For pre-commit: see https://github.com/pre-commit/pre-commit

For shfmt: see https://github.com/mvdan/sh

### Using shfmt with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/mxr/mirrors-shfmt
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: shfmt
```
