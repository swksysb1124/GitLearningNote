## Git Grep

```git
# 尋找特定字串在那些檔案
git grep "尋找的字串" [commit sha1]				

# 不區分大小寫
git grep -i "尋找的字串" [commit sha1]				

# 只列出字串所在檔案
git grep -l "尋找的字串" [commit sha1]				

# 列出所在檔案及字串發生次數
git grep -c "尋找的字串" [commit sha1]				

# 尋找多個字串, 以 or 方式
git grep -e "尋找字串1" -e "尋找字串2" [commit sha1]  		

# 尋找多個字串, 以 and 方式
git grep -e "尋找字串1" --and -e "尋找字串2" [commit sha1]  		

# and or 混用 
git grep -e "尋找字串1" --and \( -e "尋找字串2" -e "尋找字串3" \) [commit sha1] 	
```