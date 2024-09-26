# git function 
git --version 版本
git config --global user.name " " 使用者名稱
git config --global user.email " " 使用者信箱 
git init 開啟
clear 清除
git status 查看檔案狀態 **變動後提交

--git 檔案狀態
1. Untracked 未追蹤
2. Tracked 已追蹤
3. Staged 已暫存
4. Committed 已提交 **想成醫院掛號1
Staging Area 暫存區

git add +檔案名稱(.md) 未追蹤 >已追蹤 顯示(A) 中間空白鍵相隔 檔案名一次加多個 
git add *.md 一次新增.md 所有的
git add . 一次新增.
git commit -m " " **變動後用
git log 歷史紀錄 按q 退出記錄模式
git log --oneline 簡化版 git log
git diff +(id ex 4fa698f)-- +(檔案名稱.md) 比較新舊版本的內容差異
git checkout +(id) -- +(檔案名稱.md)
git reset --hard +(id) 還原到目標還原點 #操作不可逆
--
.gitignore 在目錄新增檔案 檔案內*.(檔名or副檔名) #忽略檔案內的檔名的檔案
git config --list 檢查設定值
git remote add origin +(github 網址) 連結本地與遠端資料庫
git branch -M (要的參數) 更改主線名稱 if main 
git push -u origin (brunch名稱)  後面也是main 推送資料到雲端
-1