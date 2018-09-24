## Git Push

```git
git push [remote] [branch]

# 將tag 更新到remote repository
git push origin [tag]			

# 當local repo有產生新的branch要更新到remote repo, 加上 -u
git push -u					

# 上傳到 remote origin 的 指定 branch, config 檔不會紀錄 local repo branch 跟remote repo branch的關係
git push origin [branch]			
git push -u origin [branch name]	
						
# 上傳新的 branch
git push --set-upstream origin [new branch]	

# 上傳所有的 branch
git push --set-upstream --all	

# 上傳所有的 tag	
git push --tags				
```
### 當git push rejected
1. 先`git pull`
2. 如果有conflict發生, 解決conflict, 再 `git commit`
3. 最後`git push` 