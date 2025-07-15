# Chapter 3: Working with Branches

## Creating and Switching Branches (git branch, git checkout/git switch)
Create a new branch:
```
git branch <branch-name>
```
Switch to another branch:
```
git checkout <branch-name>
```
Or (recommended for new Git):
```
git switch <branch-name>
```

**Example:**
You want to try a new feature without affecting your main code. Run `git branch feature-x` to create a branch, then `git switch feature-x` to start working on it.

## Merging Branches (git merge)
Merge a branch into the current branch:
```
git merge <branch-name>
```

**Example:**
After finishing your feature, switch back to `main` and run `git merge feature-x` to combine your changes.
