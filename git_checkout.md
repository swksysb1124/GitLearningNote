## Git Checkout

```git
# 取出某個commit中的檔案, 資料夾中檔案會被覆蓋
git checkout [commit sha1] [file1] [file2] ... 		

# 取出某的tag的檔案, 資料夾中檔案會被覆蓋
git checkout [tag] [file1] [file2] ... 			

# 取出所有檔案的最新版本, 資料夾中檔案會被覆蓋
git checkout .						

# 取出file1目前最新版本, 資料夾中檔案會被覆蓋
git checkout [file1]						

# checkout to a given branch, work tree will also change. 
git checkout [branch name]				

# create a new branch and checkout to the branch
git checkout -b [new branch name] [commit sha1]	
```