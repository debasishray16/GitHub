# apnacollege-demo

This is my first Git Repository.
<br>
Author - Debasish Ray (3rd Year B-Tech Student)

##

```
git config --global user.name "username"
git config --global user.email "your-email"
```

To check if Git is already configured, you can type: **git config --list**

1. To initialize a git repository

```
git init
```

2. To check the status of the repository:

```
git status
```

3. Add all files for tracking:

### Terminologies

- rerere (REuse REcorder REsolution)

```bash
git config --global rerere.enabled true
```

- To observe branches in different column format.

```bash
git config --global column.ui auto
git config --global branch.sort -committerdate

# This will allow you to view different branches in column format.
# Instead in one line.
git branch
```


```bash
git log --all --graph
```

```bash
git commit --amend -m "final changes"
git push --force-with-lease
```
