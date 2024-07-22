Git 命令行提交

第n次（n>1）把本地代码上传或更新到gitee:

1.输入命令  git pull                 （先获取gitee上别人上传的代码）

2.输入命令  git add .                 (注意命令后面有个“.”。将本地文件夹加入本地库)

3.输入命令  git commit -m"xxx"        (提交到本地库,"XXX"为提交备注或说明）

4.输入命令  git push origin master    成功后可在gitee上查看，未成功很有可能是你没有在第一步输入命令git pull获取代码,导致代码冲突。

(补充一个强制提交代码到gitee上的命令git push -u origin master -f，能用git push origin master就不要用强制上传命令）
