# READ ME

## <u>Annonated tags vs Lightweight tags</u>
### Lightweight tags
We use `git tag v1.7` for lightweight tags.

It doesn't support messages and doesn't have conatin metadata. Just pointer to a commit.
### Annonated tags
We use `git tag -a v1.0 -m "message"` for Annonated tags.

Support messages and conatins metadata. More like an object.

## <u>When to use Rebase?</u>
Rebase is mainly used for maintaining a cleaner, more linear commit history, especially when you've finished working on a feature branch and no longer need to track commits and merges there.

## <u>How to list tags?</u>
We use `git tag` to list all tags

## <u>How to delete a tag locally and remotely?</u>
Locally `git tag -d v1.0`

Remotely `git push --delete v1.0`

`v1.0` is just the tag name.

## <u>Image</u>
![Alt text](image.png)