# Git Commit

## Definition

A git commit is a command that saves a snapshot of the project’s currently staged changes. Each commit acts as a “save point,” capturing the current state of the project, allowing developers to track changes, revert to previous versions, and collaborate effectively

## Example

You are developing a new feature in a local Git repository. You’ve modified several files and want to save these changes along with a descriptive message about what you’ve done.

First, you stage your changes using git add, then you run the git commit command to save a snapshot of the staged changes.

A new commit is created that contains the staged changes and a message explaining those changes, which you and other developers can refer to later.

## Code Snippet



```
# Stage all changes
git add .

# Create a commit with a descriptive message
git commit -m "Fix issue with user authentication system"

# Modify the last commit message or include newly staged changes
git commit --amend -m "Correct previous commit message"

# Commit all tracked changes without manually staging them
git commit -a -m "Quick update on tracked files"
```


## Related Terms

•	git add: Stages changes to be included in the next commit. It must be used before git commit to specify which changes should be saved.	
•	git status: Displays the current state of the working directory and the staging area, helping you see which files are staged for the next commit.
•	git log: Shows the commit history, allowing you to review past commits and their messages.
•	git diff: Displays differences between the working directory and the staging area or between commits, useful for reviewing changes before committing.
•	git push: Uploads your committed changes to a remote repository, making them available to others.
•	git reset: Used to undo changes by un-staging them or reverting to a previous commit.