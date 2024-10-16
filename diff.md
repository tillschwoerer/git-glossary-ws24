The git "diff" command:

This command highlights the differences between two specified git commits. There are several syntax cases:

git diff -> Compare working directory to last commit (HEAD)
git diff <Commit> -> Compare specified commit to last commit (HEAD)
git diff <Commit1> <Commit2> -> Compare the two specified commits
git diff HEAD~2 HEAD -> Compare the third last commit to the last commit (HEAD)