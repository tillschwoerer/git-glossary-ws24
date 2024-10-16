# Git Commit

## Definition

The `git init` command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. 

## Example

Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project. 

Executing `git init` creates a `.git` subdirectory in the current working directory, which contains all of the necessary Git metadata for the new repository. This metadata includes subdirectories for objects, refs, and template files. A `HEAD` file is also created which points to the currently checked out commit.

## Code Snippet

```bash
git init                # Initialize a new repository in the current directory
git init <directory>    # Initialize a new repository in the specified directory
```

## Related Terms

- A related git command is `git clone`, which is used to create a copy of an existing repository.

