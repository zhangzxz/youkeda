git init  将一个文件夹初始化为一个git仓库，出现Initialized。。。为初始化成功
          出现Reinitialized表示已经是git仓库，无需初始化
          
git remote -v  显示是空白，即无绑定，可以进行远程仓库的绑定，否则冲突

git remote add origin 仓库地址   绑定远程仓库
git remote add origin git@github.com:zhangzxz/youkeda.git

git remote remove origin  移除绑定
