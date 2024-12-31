# How to delete a git branch locally and remotely

## 1. Delete branch locally
  
```bash
git branch -d <branchname>
git branch -D <branchname>
```

## 2.Delete branch remotely
```bash
git push origin --delete <branchname> 
```
# How to list tags locally

```bash
git tag
```

# How to delete a tag locally and remotely

## 1. Delete tag locally
  
```bash
git tag -d <tagname>
git tag -D <tagname>
```

## 2.Delete tag remotely
```bash
git push origin --delete <tagname> 
```

# what is git rebase?
`git rebase` is a Git command used to integrate changes from one branch into another by "replaying" commits. Unlike merging, which creates a new merge commit, rebasing rewrites commit history to produce a linear sequence of commits.


### When to Use Git Rebase:
- To keep a branch's commit history clean and linear.
- To incorporate updates from a base branch (e.g., `main`) into a feature branch.

### Basic Syntax:
```bash
git rebase <base_branch>
```

# Add img
![Alt text](https://logowik.com/content/uploads/images/git6963.jpg)
