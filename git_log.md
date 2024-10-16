# Git Log

## Definition

The `git log` command is used to display the commit history of a Git repository. It shows a list of commits made to the repository, including details such as the commit hash, author, date, and commit message. This command is essential for tracking changes and understanding the evolution of a project.

## Example

You work on a collaborative project and need to review the changes made by your teammates to see the history of commits to understand which features were added or which bugs were fixed. You run the `git log` command to view the commit history.

**Initial Situation:**  
You are in the directory of your Git repository.

**Action:**  
You execute the command `git log`.

**Expected Outcome:**  
You see a list of commits with their hashes, authors, dates, and messages, allowing you to review the project's history.

## Code Snippet

Here are some common usages of the `git log` command:

```bash
# Basic usage to view the commit history
git log

# View a one-line summary of each commit
git log --oneline

# View commits with a specific author
git log --author="Author Name"

# View commits that modified a specific file
git log -- <file_path>

# View commits within a specific date range
git log --since="2023-01-01" --until="2023-12-31"

# View a graph of the commit history
git log --graph --oneline --all
```

# Related Terms

- **Commit**: A snapshot of changes in the repository. Each commit is recorded in the log.

- **Branch**: A pointer to a specific commit. The log can show commits from different branches.
- **Merge**: Combining changes from different branches. Merges are also recorded in the log.
- **Rebase**: A way to integrate changes from one branch into another. The log can help visualize the history before and after a rebase.
- **Diff**: The difference between commits. You can use git diff in conjunction with git log to see what changes were made in each commit.
