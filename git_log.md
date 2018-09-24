## Git Log

```git
git log 						# 看目前為止的commit log
git log --graph					# 圖表化commit
git log --oneline					# 每筆commit只顯示一行
git log --pretty=oneline 				# 每筆commit只顯示一行
git log --auther=’auther_name’			# 只顯示某作者的commit
git log --shortstat					# 顯示commit資料改變數目(changed/insertion/deletion)
git log --stat
git log --after='yyyy-mm-dd hh:mm' --before='yyyy:mm:dd hh:mm'	
git log origin/master
git log --decorate 					# 加入branch
git log --decorate --all
git log --all 						# 顯示所有branch的commit
git log --graph --oneline --all --decorate
git shortlog						# 顯示作者 跟 所commit		
git log --author="xxxx"					# 顯示xxxx作者所有commit
git log --grep="xxxx"					# 顯示commit敘述含xxxx的所有commit
```