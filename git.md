# Git Practice
## 如何跳到其他branch?
- git checkout [branch_name]

## 如何刪除stage 裡面的資料？
1. 若該檔案不在repository內 : git rm --cached 檔案名稱
2. 若檔案已經在repository內 : git reset HEAD 檔案名稱

##如何刪除commit裡的資料？
- git reset [branch_name]^


## 刪除遠端 Branch
- git push origin :new_branch # 刪除遠端的 branch
- git push origin --delete new_branch # 刪除遠端的 branch

## 看遠端有什麼 branch
- git branch -r 

## 上傳文件SOP
1. git checkout origin/new_branch -b new_branch # 建立 local new_branch 並與遠端連接
2. 修改東西
3. git push origin new_branch

