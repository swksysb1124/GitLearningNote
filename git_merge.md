## Git Merge

```git
git checkout [branch A] 		# 將branch B 內容合併到 branch A
git merge [branch B]			# 合併成功後, 會在branch A產生新的commit
git merge --abort  				# 還有merging, 放棄merge
git merge --no-ff				# 不要使用 fast-forwar merge
git commit 						# 修正conflict 就可以commit, 完成merge。
								# conflict之所以發生, 是由於兩個branch都改到同一個檔案的同一位置
git reset --hard HEAD^			# 剛剛merge的想要反悔
```