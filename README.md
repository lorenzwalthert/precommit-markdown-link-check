markdown-link-check mirror
================

**DEPRECATED** 

Please use the hooks directly in https://github.com/tcort/markdown-link-check. 


Mirror of markdown-link-check package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For markdown-link-check: https://github.com/tcort/markdown-link-check

### Using markdown-link-check with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/lorenzwalthert/precommit-markdown-link-check
        rev: v0.0.0.9002  # Use the sha / tag you want to point at
        hooks:
        -   id: markdown-link-check

### Limitations

- only works for README files and only for one at the time, because
  of tcort/markdown-link-check#78. In theory, we could use this also to check
  links in documentation and vignettes otherwise.
