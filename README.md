
#### New Repository

```
git init
```

#### Clone Repository:

```
git clone https://github.com/user/repository
```

#### Status Control:

```
git status
```

#### Add changes to commit.

```
git add file.txt    # All changes
git add .           # All changes
```

#### Git commit:

```
git commit -m "commit message"
```

#### Branches:

```
git branch
git branch new-feature           # Creates a branch but stays in the existing
git checkout feature             # Change to "feature" branch
git checkout -b new-feature      # Creates and change to new branch
```

#### Merge branches:

```
git checkout main          # Go to main
git merge feature          # Merge the ‘feature’ branch into ‘main’.
```

#### Remote Repository:

```
git remote -v
```

#### Send changes to remote repository:

```
git push origin main
```

#### Send to local the remote repository changes and merge:

```
git pull origin main
```

#### Send to local some remote branch no merge

````
git fetch origin
git checkout nombre-rama
````

#### Send to local some PR branch:

```
git fetch origin pull/{PR_ID}/head:pr-feat
git checkout pr-feat
````
#### Differences between branches:

```
git diff branch1..branch2
```

#### Modify changes:

```
git diff
```

#### HEAD movement history:

```
git reflog
```

#### Moves history to that commit, but keeps subsequent changes as staging files:

```
git reset --soft <commit hash>
```

#### Move your current branch to the commit with that hash and delete everything that came after it, including subsequent commits.

```
git reset --hard <commit hash>
```

#### Discard no added changes:

```
git checkout -- file.txt
```

#### Temporal store no commit changes:

```
git stash
```

#### Recover the changes and apply:

```
git stash pop
```

#### Clear stored stashes:

```
git stash clear
```

#### Recover especific stash:

```
git stash list

git stash apply stash@{0}
```
