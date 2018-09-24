## Git Rebase

```git
git checkout draft				
git rebase master			# 做基準master, 重新改變目前branch的root 
git rebase --continue		# 修正conflict及git add後, 繼續rebase
git rebase --abort			# 不要rebase
```