# TestGit

…or create a new repository on the command line

用命令行创建新的仓库

```bash
echo "# TestGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/zhangze2/TestGit.git
git push -u origin master
```

…or push an existing repository from the command line
 
Push 一个已经存在的仓库

```bash
git remote add origin https://github.com/zhangze2/TestGit.git
git branch -M master
git push -u origin master
```

## 使用 ssh 连接 

1. 生成密钥对 SSH-Key
ssh-keygen -t rsa -b 4096 -C “zhangze.zz@qq.com”

2. 添加公钥到远程存储库
将公钥 id_rsa.pub 配置到 自己的账户 SSH 设置下

3 git clone克隆远程存储库项目
执行 clone 命令，从远程存储库克隆项目。
```bash
git@github.com:cohen-zhang/iterative.git
```
