## Git Reset

```git
git reset --soft [commit sha1 / tag] [file]	 		# 回到某筆commit的狀態，staged的檔案保留
git reset [commit sha1 / tag] [file]				# 回到某筆commit的狀態，staged的檔案變成 unstaged
git reset --hard [commit sha1 / tag] [file]			# 回到某筆commit的狀態，staged的檔案直接刪除

```