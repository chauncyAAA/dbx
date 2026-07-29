https://dbxio.com/cn/docs/what-is-dbx
## fork仓库
```shell
git clone https://github.com/<你的 GitHub 用户名>/dbx.git
cd dbx
git remote add upstream https://github.com/t8y2/dbx.git
git remote -v
```

## 本地拉一个新分支
```shell
推荐每个 Issue 使用一个独立分支：
git switch -c fix/issue-1234-short-description
```

## 同步主仓库
```shell
git switch main
git fetch upstream
git rebase upstream/main
git push origin main
```
