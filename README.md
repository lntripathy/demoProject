# Pushing Local Repo to Github

```
git init
```
- Initialize a .git file in the folder.


```
git remonte origin <link>
```
- To set the remote as origin.
- <link> is the link to your github repository.


```
git remote -v
```
- To verify git remote.


```
git branch
```
- To check the branch of github.
- (by default master)

```
git branch -M main
```
- Renaming branch from master to main.
- (github default branch is main)


```
git push origin main
```
or

```
git push -u origin main
```
then

```
git push
```
- Pushing to github



```
git commit -am "MSG"
```
- To add and commit in single command.
- No untracted file created.



# 🚀 Git Branching & Pull Commands (Quick Cheat Sheet)

## 🌿 Branch Commands

- `git branch branch-name`  
  Create a new branch.

- `git checkout -b branch-name`  
  Create and switch to a new branch.

- `git checkout branch-name`  
  Switch to an existing branch.

- `git branch`  
  List all local branches.

- `git branch -r`  
  List all remote branches.

- `git branch -a`  
  List both local and remote branches.

- `git branch -m new-name`  
  Rename the current branch.

- `git branch -M new-name`  
  Force rename the current branch.

- `git branch -d branch-name`  
  Safely delete a merged branch.

- `git branch -D branch-name`  
  Force delete a branch.

---

## 🔄 Pull & Fetch Commands

- `git pull origin main`  
  Pull latest changes from remote into your current branch.

- `git pull --rebase origin main`  
  Pull and rebase for a cleaner commit history.

- `git fetch origin`  
  Fetch latest changes without merging.

- `git pull origin main --allow-unrelated-histories`  
  Merge two projects with different histories.

---








  