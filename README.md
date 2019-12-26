markdown-link-check mirror
================

Mirror of markdown-link-check package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For markdown-link-check: https://github.com/tcort/markdown-link-check

### Using markdown-link-check with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/lorenzwalthert/precommit-markdown-link-check
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: markdown-link-check
