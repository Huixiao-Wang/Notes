# 初始化

```bash
git init # 初始化当前文件夹下 .git 文件夹
```

# 将本地与终端仓库关联

```bash
git remote add origin git@github.com:Huixiao-Wang/CV-self-learning.git # 后面为仓库SSH key
git remote -v # 查看关联仓库信息
```

# 提交文件至暂存区

```bash
git add . # . 表示提交所有文件
```

# 提交至本地仓库

```bash
git commit -m "commit message" # 附带提交信息
```

# 将本地仓库推送至Github

```bash
git push -u origin main # main为现主流分支
```