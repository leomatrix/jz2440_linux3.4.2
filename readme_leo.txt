git:
git branch --set-upstream-to=origin/master master

>>> git branch -vv
* master                fb4d1d9 [origin/master] [add]: add leo.yang readme.txt file to record development
  pm_manager_of_wds_3th 7cfd815 [origin/pm_manager_of_wds_3th] patch for wds 3th power manager

### push command:
git push -u origin master HEAD:refs/for/master

### 合并远端最近的两个提交方法:
git rebase -i HEAD~2
git push -u origin master HEAD:refs/for/master -f
