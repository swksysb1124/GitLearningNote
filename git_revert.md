## Git Revert

```git
git revert HEAD				# 回到HEAD^節點狀態, 資料夾也更改並產生新的commit
						# git reset HEAD^ 也有類似功能; 
                  					# 不同的是, revert不會刪除 HEAD節點
git revert [commit sha1]			# 回到[commit sha1]前一個commit狀態, 資料夾也更改並產生新的commit
git reset --hard HEAD^			# 剛剛revert想要反悔
```