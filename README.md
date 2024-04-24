git init  # 初始化一個新的 Git 儲存庫

git clone <遠端儲存庫的URL>  # 複製遠端儲存庫到本地

git status  # 檢視目前工作目錄的狀態

git add <文件名或目錄名>  # 將文件或目錄添加到 Git 的暫存區

git commit -m "提交訊息"  # 提交暫存區中的更改並添加提交訊息

git push <遠端名稱> <本地分支名稱>  # 將本地分支推送到遠端儲存庫

git pull <遠端名稱> <遠端分支名稱>  # 從遠端儲存庫拉取更新到本地

git branch  # 列出所有本地分支

git checkout <分支名稱>  # 切換到指定的分支

git merge <分支名稱>  # 將指定分支合併到當前分支

git remote -v  # 檢視遠端儲存庫的URL

git log  # 顯示提交記錄

git reset <文件名>  # 取消對文件的暫存

git config --global user.name "你的名字"  # 設置全局使用者名稱

git config --global user.email "你的郵件地址"  # 設置全局郵件地址
