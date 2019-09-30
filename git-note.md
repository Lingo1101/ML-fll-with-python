# 目录
windows 中 打开E盘  `cd /E/`

1. 显示子文件 `ls -a`

2. 打开目录 `cd xx`

3. 其他的查看 `linux 命令`

` 现在打开你想要的目录吧~继续 nothing to commit, working tree clean


# git 日常命令

1. `git add ./` 刚才修改完文件了 需要 1
2. `git commit -m "aaa"`  添加完之后 写描述    -m 就是写
3. `git status`  这个就是查看当前状态的 没有提交显示 `nothing to commit, working tree clean`
4. `git pull`   远程下载到本地  现在远程比本地多了东西 要同步的话 记得先这个  
5. `git push`  本地推到远程    现在本地改了东西 yao推送到github推送到github 是

· 说明呢 自己寻找 我给你演示一下

# 流程
1. github创建仓库, 记得初始化仓库，然后复制ssh链接
2. git clone xxx ，自动下载
3. cd {仓库name} 进入
3. git remote -v 查看是否正确关联到远程的fll
4. 编辑你的文件{一大堆代码print('hello world)} 
5. git add ./ ，  ./的意思是当前目录下所有的文件
6. git commit -m "desc" , 写清楚这次的提交描述
7. git push, 推送到远程的github
