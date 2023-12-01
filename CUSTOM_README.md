1、第一次操作需要先添加上游目录 （操作过一次之后，以后就不用再操作了。将地址改为上游项目的具体地址）
git remote add upstream https://github.com/pichillilorenzo/flutter_inappwebview.git
2、拉取上游最新的代码
git fetch upstream
3、合并到本地（有时候可能会有冲突，需要解决冲突）
git merge upstream/master
4、提交到自己底fork目录
git push origin master
5、需要到github界面上提交pull request ，请求合并到上游项目。在左边菜单的 “Merge Requests”菜单。提交完成后就等待对方同意了合并。

