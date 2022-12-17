分支代码合并：
$ git merge  --no-ff

查看提交日志：
$ git log

修改上一条提交日志：
$ git commit --amend

找不到changeId:
$ gitdir=$(git rev-parse --git-dir);
$ scp -p -P 29418 weixingtai@review.rnd..com:hooks/commit-msg ${gitdir}/hooks/
$ git commit --amend

查看可视化提交日志界面：
$ gitk

添加提交代码：
$ git add .

提交代码：
$ git commit -m  "[手机安全管家] #0 首页动画优化"

代码推送：
$ git push origin HEAD:refs/for/

代码更新：
$ git pull --rebase

代码暂存：
$ git stash

代码取出：
$ git stash pop
