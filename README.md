# READ ME
Eslaam Mohamed Attia

## Annonated tags vs Lightweight tags
### Lightweight tags
We use `git tag v1.7` for lightweight tags.

It doesn't support messages and doesn't conatin metadata. Just pointer to a commit. 

Used as a quick reference to commits.

### Annonated tags
We use `git tag -a v1.7 -m "message"` for Annonated tags.

Support messages and conatins metadata. More like an object.

Used more for public releases.

---------------------------------------------

## When to use Rebase
Rebase is mainly used for maintaining a cleaner, more linear commit history, especially when you've finished working on a feature branch and no longer need to track commits and merges there.

---------------------------------------------


## How to list tags?
We use `git tag` to list all tags

---------------------------------------------


## How to delete a tag locally and remotely?
Locally `git tag -d v1.7`

Remotely `git push --delete v1.7`

`v1.7` is just the tag name.

---------------------------------------------


## Image
![Alt text](image.png)