# Git Command Line Interface

## Initial Configuration
```
git config –global core.editor “nano”
git config –global user.name “<my full name>”
git config –global user.email “<my email address>”
```

## Branch Creation, First Commit & Push
```
git clone <url>
git status
git branch <my new branch name>
git checkout <my new branch name>

git add <file-name>
git commit -am “<my commit message>”
git log
git push --set-upstream origin <my new branch name>
```

```
## Merging and Handling Merge Conflicts
```
git checkout main
git merge <my new branch name>
```
Fix merge conflicts in the conflicting files with an editor
```
git commit -am “fixing merge conflicts”
git push
```

---

[Link to Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
