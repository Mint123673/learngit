Git is a distributed version control system.
Git is free software distributed under the GpL.
Git has multable index called stage.
Git tracks changes.
git checkout -- "readme.txt"  撤销工作区的修改
git reset HEAD readme.txt   把暂存区的修改撤回工作区，重新放回工作区，HEAD表示最新的版本
唉，怎么还不成功呀！！难过
git checkout -b dev  创建并切换到dev分支  //使用git switch -c a  创建并切换到新的分支a
git checkout dev_1  切换到dev_1分支       //git switch a   直接切换到a分支
啊啊啊！！！竟然成功了，意外之喜啊
试试？
？离谱   I don't want to change anything.No,you want.
想要修改文件并且提交，步骤：vim <file name> -> git add <file name> -> git commit -m <file name> 才能真
