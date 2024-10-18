# Git LFS

## Definition

Git Large File Storage (LFS) is a tool that replaces large files up to several GB in size with text pointers in Git and stores the actual files themselves on a remote server. 

## Example

Git LFS can be used for projects that need to deal with large files, for example audio recordings, videos or datasets. To enable version control of these large files, we can install Git LFS and specify per rerepository which file types (e.g. ".mpeg4") should be managed by Git LFS. At this point, we can continue with the normal Git workflow.

## Code Snippet

First, we specify the extension of each file type that should be tracked with Git LFS. New file types can also be added later.

```
git lfs track "*.mpeg4"
```

Then we make sure that the .gitattributes file is tracked.

```
git add .gitattributes
```

Now we can continue with the normal Git workflow

```
git add file.mpeg4
git commit -m "added video file"
git push origin main
```


## Related Terms

- repository
- git add
- git commit
- git push