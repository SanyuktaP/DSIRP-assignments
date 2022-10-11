### 1) git config
##### This command sets the author name and email address respectively to be used with your commits.
```bash
git config –global user.name “[name]”
git config –global user.email “[email address]”
```

### 2) git init
##### This command is used to start a new repository.
```bash
git init [repository name]
```

### 3) git clone
##### This command is used to obtain a repository from an existing URL.
```bash
git clone [url]
```

### 4) git add
##### This command adds a file to the staging area.
```bash
git add [file]
```

##### This command adds one or more to the staging area.
```bash
Usage: git add *
```

### 5) git commit
##### This command records or snapshots the file permanently in the version history.
```bash
git commit -m “[ Type in the commit message]”
```

##### This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
```bash
git commit -a
```

### 6) git diff
##### This command shows the file differences which are not yet staged.
```bash
git diff
```

##### This command shows the differences between the files in the staging area and the latest version present.
```bash
git diff –staged
```

##### This command shows the differences between the two branches mentioned.
```bash
git diff [first branch] [second branch]
```

### 7) git reset
##### This command unstages the file, but it preserves the file contents.
```bash
git reset [file]
```

##### This command undoes all the commits after the specified commit and preserves the changes locally.
```bash
git reset [commit]
```

##### This command discards all history and goes back to the specified commit.
```bash
git reset –hard [commit]
```

### 8) git status
##### This command lists all the files that have to be committed.
```bash
git status
```

### 9) git rm
##### This command deletes the file from your working directory and stages the deletion.
```bash
git rm [file]
```

### 10) git log
##### This command is used to list the version history for the current branch.
```bash
git log
```

##### This command lists version history for a file, including the renaming of files also.
```bash
git log –follow[file]
```

### 11) git show
##### This command shows the metadata and content changes of the specified commit.
```bash
git show [commit]
```

### 12) git tag
##### This command is used to give tags to the specified commit.
```bash
git tag [commitID]
```

### 13) git branch
##### This command lists all the local branches in the current repository.
```bash
git branch
```

##### This command creates a new branch.
```bash
git branch [branch name]
```


