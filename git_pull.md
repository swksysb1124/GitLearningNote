## Git Pull

從 remote repo 取回目前所在 branch最新資訊, 並將 取回來的資料合併到local repo 中目前的branch
預設上，git pull = git fetch + git merge

```git
git pull 						# 與 remote repo 
git pull --all					# 跟 remote repo 所有 branch做更新
git pull --rebase  				# 用 git rebase 取代 git merge, 
								# git pull --rebase = git fetch + git rebase origin/master
```