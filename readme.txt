Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
git checkout -- filename 让文件回退到最近一次git commit或者git add 的状态
git reset HEAD filename 让上一次的git add作废
git diff 默认是工作区和最近一次提交的区别
git diff HEAD --filename是比较工作区和版本库的区别
git remote add origin git@github.com:michaelliao/learngit.git 本地关联github仓库
git push -u origin master 将本地库所有内容推送到远程库中
git push origin master 将本地master分支的最新修改推送给github