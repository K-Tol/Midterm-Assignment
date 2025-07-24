## Koleen Tolentino's Midterm Assignemnt

# git## git merge <branch-name>
```bash
git merge <branch-name>
```

### What it does:
Combines the changes from two branches

### Narrative:
It takes changes from a seperate branch and merges them in your current branch. You must be in the branch
you want to merge into before begining, like main/master for example.

## git cherry-pick <commit-hash>
```bash
git cherry-pick <commit-hash>
```

### What it does:
Takes one or multiple commits from a different branch and applies it to another

### Narrative:
Like the name entails, you grab a specific commit from on branch to another. This is great
if you want a specific change so that you don't have to merge entire branches. Be wary of
conflicts that may arise since you're bringing one change to another.

## git remote -v
```bash
git remote -v
```

### What it does:
Shows you which repos are linked to your local git repo

### Narrative:
This is great to see which remote repo your local repo is connected to, if you have a lot of repos.
Also great for troubleshooting fetch, pull, or push issues.