# Git Diff

## Definition

The ‘git diff’-command is used to compare two input-datasets from a repository and gives an output regarding the amendment between them by color-highlighting additions and deletions. You could can address different stages of data sources among others like commits, branches or files. 
The ‘git diff’-command is often used together with other commands like ‘git status’ or ‘git log’, to get an impression about the current status of the git-repository, to which the input-datasets belongs to.

## Example

If you are working on a Python-based program, possibly together with several others or just on your own, and you would like to find out, how the code has been developed. With ‘git diff’ you can take a look at the development or may be find the difference you were looking for. 

## Code Snippet

Precondition: at least one document in the repository has been changed.


In order to compare the working directory with the last commit, just:
```
 git diff
```

You want to compare your last commit with another one, which should be named between <>? 
```
Git diff <commits1>
```

You want to compare two special commits?
```
Git diff <commits1><commits2>
```

Has a comparison of the versions to be done? 
```
Git diff <commits1> --filename
```


## Related Terms

You can find more details at https://git-scm.com/docs/git-diff 

Provide a list of terms that are related to this term. This can be other git commands, or other concepts that are closely related to this one, and explain how they are connected.






