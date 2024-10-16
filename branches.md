# Git branch

## Definition

With this command you can list, create, rename or delete branches

## Example

Imagine you want to create a git glossary as a group project in class.
To create your own branch to work on and not mess up anything on the main branch, the command git branch can be used. You can also rename or delete your branch and get a list of existing branches.  

## Code Snippet

```
git branch               # List local branches
git branch -r            # List remote branches
git branch -a            # List all (local + remote) branches
git branch <newbranch>   # Create new branch
git branch -m <newname>  # Rename current branch
git branch -d            # Delete local branch
git branch -D            # Force delete local branch even if not yet merged

```


## Related Terms

- git switch  - with this command you can switch to other branches
- git merge   - with this command you can merge the specified branch into the currently checked out branch

