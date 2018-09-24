## Git Config

設定使用者帳號跟repository的configuration

```git
git config --list
git config -l 		
git config --global user.name "user_name"
git config --global user.email someone@some.domain

# 讓 gitk (或是其他Git GUI)可以顯示中文
git config --global gui.encoding utf-8

# 把local repo目前所在branch更新到remote repo對應的branch
git config --global push.default simple

# 把local repo 跟remote repo 中, 已經存在且同名的branch都更新一遍
git config --global push.default matching		

# 將local repo中所有branch都更新到 remote repo
git config --all								

# 開放 repo權限給group的人看, group成員可以去 /etc/group 看
# Linux系統更改檔案權限 : chgrp -R [group name] [file]
git config core.sharedRepository group			
```
### 使用help 查看 config文件

```git
git help config
<Git Configuration>
	user.name=[user name]
	user.email=[user email]
	gui.encoding=[utf-9/...]
	remote.origin.url=[remote repo path]
	remote.origin.fetch=+ref/heads/*:refs/remotes/origin/*	
	branch.[branch name].remote=origin			#這個branch對應著remote git repo
	branch.[branch name].merge=refs/heads/master
```