# Git Commit

## Definition

git status is a command used in Git to display the current state of the working directory and staging area. It shows which changes have been staged, which haven’t, and which files aren’t being tracked by Git. It helps users see what’s going on in their repository and provides information on what the next steps should be.

## Example

Situation:
You are working on a project and have modified a few files. You want to know which files are changed, which ones have been staged for a commit, and which are still untracked by Git.

Action:
You run the git status command to check the current state of your working directory. It shows which files have been modified, whether there are any untracked files, and whether you have any files staged for the next commit.

Expected Outcome:
A clear overview of which files are modified, staged for commit, or untracked.
Guidance on what actions can be taken next, like using git add or git commit for staged changes.

## Code Snippet

Please provide code examples that demonstrate the command or feature in action. You do not need to show all possible variants, but try to cover the most common use cases. You code blocks here.

```
# Standard Use Case
git status

# Short Form
git status -s

# Branch information
git status -b

# Show also ignored files (gitignore)
git status --ignored
```


## Related Terms

git add: Stages changes for the next commit. Files shown in git status under "Changes not staged for commit" or "Untracked files" can be staged using git add.

git commit: Creates a new commit from the staged changes. After running git status and ensuring the correct files are staged, you can use git commit to save those changes.

git diff: Shows the differences between the working directory and the staging area. If git status indicates there are changes not staged for commit, you can use git diff to view those changes.

git restore: Used to discard changes in the working directory, restoring files to their last committed state. If git status shows modified files, git restore can be used to undo those modifications.