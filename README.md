# READ ME

## Annonated tags vs Lightweight tags
### Lightweight tags
We use `git tag v1.7` for lightweight tags.
It doesn't support messages and doesn't have conatin metadata. Just pointer to a commit.
### Annonated tags
We use `git tag -a v1.0 -m "message"` for Annonated tags.
Support messages and conatins metadata. More like an object.

## When to use Rebase
Rebase is mainly used for maintaining a cleaner, more linear commit history, especially when you've finished working on a feature branch and no longer need to track commits and merges there.

