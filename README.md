# git-utils

My collection of stuff to help with git.

Install:
```
git clone https://github.com/romgrk/git-utils
git config --global core.hooksPath $(pwd)/git-utils/hooks
```

## pre-commit hook

This hook prevents the commit from completing if some restricted keywords
are present in the commit text. The default keywords are `XXX` and `PREVENT_COMMIT`.
You can also define your own keywords by setting the env var `GIT_PREVENT_COMMIT` to
a comma-separated list of restricted keywords.

![demo](./assets/demo.png)
