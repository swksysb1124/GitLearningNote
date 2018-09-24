## Git Cherry-Pick

```git
# 將 某筆commit內容合併到目前最新commit
git cherry-pick [commit sha1]		

# 還在cherry-picking, 放棄cherry-pick
git cherry-pick --abord			

# 修正conflict及git add後, 繼續cherry-pick
git cherry-pick --continue			

# 剛剛cherry-pick的想要反悔
git reset --hard HEAD^			
```