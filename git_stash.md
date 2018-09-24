## Git Stash

```git
git stash	 						# 儲藏檔案
git stash							# 列出儲藏
git stash apply						# 採用儲藏
git stash apply	stash@{1}			# 採用指定儲藏
git stash drop stash@{1}			# 丟棄指定儲藏
git stash pop						# 從儲藏堆疊中移出並採用
git stash branch [branch name]		# 建立新分支並將採用儲藏
```