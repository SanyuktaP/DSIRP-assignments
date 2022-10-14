# Git Basic commands

### 1) git config
##### This command sets the author name and email address respectively to be used with your commits.
```bash
git config --global user.name "[name]"
```
```bash
git config --global user.email "[email address]"
```
![t1](https://user-images.githubusercontent.com/97040413/195196121-11e1aeb8-c9a6-4d14-b25f-51304af19b46.png)


### 2) git init
##### This command is used to start a new repository.
```bash
git init [repository name]
```
![t2](https://user-images.githubusercontent.com/97040413/195196207-754a7bad-68a5-4146-b6ab-6211feb8a584.png)

### 3) git clone
##### This command is used to obtain a repository from an existing URL.
```bash
git clone [url]
```
![t3](https://user-images.githubusercontent.com/97040413/195196219-043ea087-053e-4ee9-b8b1-015782fd9376.png)

### 4) git add
##### This command adds a file to the staging area.
```bash
git add [file]
```
![t4](https://user-images.githubusercontent.com/97040413/195196257-694ee1c3-4245-4d3a-8b63-479ea5b8d76e.png)

##### This command adds one or more to the staging area.
```bash
git add .
```
![T4(1)](https://user-images.githubusercontent.com/97040413/195196326-e358a845-dd69-460f-9b93-3d3f8cd1d564.png)

### 5) git commit
##### This command records or snapshots the file permanently in the version history.
```bash
git commit -m “[ Type in the commit message]”
```
![t5](https://user-images.githubusercontent.com/97040413/195196372-145e4e60-16e7-4a8c-b517-193f164635d0.png)

### 6) git diff
##### This command shows the file differences which are not yet staged.
```bash
git diff
```
![t6](https://user-images.githubusercontent.com/97040413/195196474-3597cce1-5dae-4d6e-bd48-a85d47842217.png)

##### This command shows the differences between the files in the staging area and the latest version present.
```bash
git diff –staged
```
![t6(2)](https://user-images.githubusercontent.com/97040413/195196503-e072d2dd-273c-4dc3-b7b3-544f60210fa6.png)

##### This command shows the differences between the two branches mentioned.
```bash
git diff [first branch] [second branch]
```
![t6(3)](https://user-images.githubusercontent.com/97040413/195196520-1cf59e1a-eeb5-4603-bf78-2555a1ce045b.png)

### 7) git reset
##### This command unstages the file, but it preserves the file contents.
```bash
git reset [file]
```
![t7](https://user-images.githubusercontent.com/97040413/195196536-d9f0e174-a1a0-4943-93fa-c544ced37e67.png)

### 8) git status
##### This command lists all the files that have to be committed.
```bash
git status
```
![t8](https://user-images.githubusercontent.com/97040413/195196560-6fcb0414-583b-4233-9360-ed2ceb6f6e15.png)

### 9) git rm
##### This command deletes the file from your working directory and stages the deletion.
```bash
git rm [file]
```
![t9](https://user-images.githubusercontent.com/97040413/195196573-aa3e2aa8-8a2d-412d-91c4-c7229d136822.png)

### 10) git log
##### This command is used to list the version history for the current branch.
```bash
git log
```
![t10](https://user-images.githubusercontent.com/97040413/195196606-ba8875bc-b66b-45bf-ae60-7f99c551c1a4.png)

##### This command lists version history for a file, including the renaming of files also.
```bash
git log –follow[file]
```
![t10(1)](https://user-images.githubusercontent.com/97040413/195196624-05eed33b-8457-431b-974c-32dda89fef3c.png)

### 11) git show
##### This command shows the metadata and content changes of the specified commit.
```bash
git show [commit]
```
![t11](https://user-images.githubusercontent.com/97040413/195196640-83940937-0530-4b93-a0d0-78d04a77b957.png)

### 12) git tag
##### This command is used to give tags to the specified commit.
```bash
git tag [commitID]
```
![t12](https://user-images.githubusercontent.com/97040413/195196658-d0fe1b6e-e238-43cf-a748-32137c2ca0ea.png)

### 13) git branch
##### This command lists all the local branches in the current repository.
```bash
git branch
```
![t13](https://user-images.githubusercontent.com/97040413/195196746-9d460d23-9358-4a1e-a903-731a4cbafd99.png)

##### This command creates a new branch.
```bash
git branch [branch name]
```
![t13(2)](https://user-images.githubusercontent.com/97040413/195196685-8fabfb3d-d111-4d5c-a9ff-af76ad5415e2.png)


### 14) git Merge 
##### This command is used to merge the specified branch?s history into the current branch.
```bash
git merge [BranchName] 
```
![t14](https://user-images.githubusercontent.com/97040413/195196782-253ef397-dfed-4213-8d05-99c3039ac32c.png)

### 15) git push 
##### This command sends the changes made on the master branch, to your remote repository.
```bash
git push [variable name] master  
```
![t15](https://user-images.githubusercontent.com/97040413/195425355-a3bae639-1572-4a87-ab6f-8a7a046300a2.png)

### 16) Git pull 
##### Pull command is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.
```bash
git pull [URL]  
```
![t16](https://user-images.githubusercontent.com/97040413/195425996-63b1dfe6-5279-493a-a6c8-774c9bd3f8d9.png)

