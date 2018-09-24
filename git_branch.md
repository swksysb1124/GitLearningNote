## Git Branch

產生新的分支

```git
# create a new branch at from a certain commit
git branch [new branch name] [commit sha1]

git branch bug/unexpected-crash [commit sha1]

git branch feat/add-rename [commit sha1]

# 列出 local & remote repo所有branch
git branch -a				
	
# 列出 local repo中所有branch
git branch --list				

# list all feature branches
git branch --list feat/*			

# list all bug branches
git branch --list bug/*			

# modify current branch name
git branch -m [modified branch name]		

# delete a branch which was merged.
git branch -d [branch name]			

# delete a branch forcely
git branch -D [branch name]			
```