# Git
###########################use relevant git command###################################

# 追蹤所有更動過的檔案
git add-all
# 切換到指定branch
git checkout "branch name"
# 創建branch,切換過去
git checkout -b "branch name"
# 合併branch,全部連成一線
git merge
# 合併branch,不會連成一線
git merge -no-ff ""
# 刪除branch
git branch -d "branch name"


# 設定帳戶 ＆ 電子郵件
git config --global user.name "<Your Name>"
git config --global user.email "<your@gmail.com>"

# 將專案資料夾初始化
git init

# 工作環境狀態
git status

# 流程
git add "file"

git commit -m ""

######## 取消 add ############

git rm --cached ""

# 連接github
git config --global user.username <你的 github 使用者名稱>
# push
git remote add origin <remote 網址>

git push -u origin master
