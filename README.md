# MyGitBook
lean git



基本操作相关：

- `git init`:创建新文件夹，打开，以创建新的 git 仓库
- `git add .`,`git add filename`:
- `git commit -m 'Hello'`





分支相关：

- `git checkout -b develop`
- `git checkout master`
- `git branch -d develop`
- `git merge develop`





远程相关：

- `git remote add origin git@github.com`
- `git pull origin develop `
- `git push origin develop` 
- `git clone git@github.com`





查看状态相关：

- `git log`
- `git status`




其他：

- `git fetch`
- `git checkout -- filename`
- `git fetch origin`
- `git reset --hard origin`
- `git branch fix`:创建fix分支


技巧：

- `git log --graph`
- `git log --graph`
- `git reset filename`
- `git reset -- hard filename`




git checkout -- filename

git reset HEAD filename