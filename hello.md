绑定远程仓库
将一个文件夹初始化为一个git仓库  git init
命令来查看当前git仓库绑定的远程仓库	 git remote -v
刚刚初始化的仓库一般来说是没有绑定远程仓库的，而从线上clone下来的仓库是必然有远程绑定的。
如果使用git remote -v命令，显示是空白，即无绑定，我们才可以进行远程仓库的绑定，否则就会提示冲突。
绑定远程仓库：git remote add origin 仓库地址
移除绑定  git remote remove origin