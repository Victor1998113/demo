```
git config --global user.name "Victor1998"
git config --global user.email "victor1998113@outlook.com"
```

创建 git 仓库:

```
mkdir mvictorcore
cd mvictorcore
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://gitee.com/victor1998/mvictorcore.git
git push -u origin master
```

已有仓库?

```
cd existing_git_repo
git remote add origin https://gitee.com/victor1998/mvictorcore.git
git push -u origin master
```