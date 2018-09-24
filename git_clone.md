## Git Clone

```git
git clone [src path] [dst path]

# 備份 local repository, 生成remote bare格式
git clone --bare [project] [remote repo path]  		

# 當remote & local repo都在同一台電腦的時候, 進行repo 複製
git clone [remote repo path] [local repo path]		

# 當remote repo在LAN上電腦時, 進行repo複製
git clone //[computer name]/[remote repo path] [local repo path]			

# 當 remote repo在Web Git Server時, 進行repo複製
git clone http://[Web Git Server or IP]/[remote repo path] [local repo path] 		

# 當 remote repo在SSH Git Server時, 進行repo複製 
git clone [user.name]@[SSH Git Server or IP]:[remote repo path] [local repo path]	

# 複製特定分支下來
git clone -b [branch name] //[computer name]/[remote repo path] [local repo path]              
```