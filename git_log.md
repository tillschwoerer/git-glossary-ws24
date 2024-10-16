# Git Commit

## Definition

`git log` is a command used in Git to display the commit history of a repository. It shows a list of commits made in the repository, along with details such as the commit hash, author, date, and commit message. This command is essential for tracking changes, understanding project history, and reviewing contributions.

## Example

Imagine you are working on a collaborative project with multiple contributors. You want to review the recent changes made to the codebase before merging a pull request. By using git log, you can see a chronological list of commits, including who made each change and what the changes were about.

Initial Situation: You have a repository with multiple commits made by different contributors.

Action: You run the command git log in your terminal.

Expected Outcome: You receive a detailed list of commits, allowing you to understand the recent changes and their context, helping you make informed decisions about the pull request.

## Code Snippet

Here are some common usages of the git log command:

```bash
# Basic usage to view the commit history
git log

# View a one-line summary of each commit
git log --oneline

# View commits with a specific author
git log --author="Author Name"

# View commits within a specific date range
git log --since="2023-01-01" --until="2023-12-31"

# View commits that modified a specific file
git log -- path/to/file.txt

# View the commit history with a graph representation
git log --graph --oneline --decorate
```

## Related Terms

**Commit**: A snapshot of changes made to the repository. Each commit has a unique hash and contains metadata such as the author and timestamp.

**Branch**: A pointer to a specific commit in the repository. Branches allow for parallel development and feature isolation.

**Merge**: The process of combining changes from different branches. Understanding the commit history is crucial when resolving merge conflicts.

**Rebase**: A command that allows you to integrate changes from one branch into another by rewriting commit history. The git log command can help visualize the history before and after a rebase.

**Checkout**: A command used to switch between branches or restore working tree files. The commit history can inform which branch to check out based on recent changes.
