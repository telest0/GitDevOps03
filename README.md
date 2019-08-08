# DevOps03

mkdir GitDevOps03

git init

vim README.md

git add .

git commit -m "Initialization and README added"

git config --global user.name '******'

git config --global user.email '******'

git config --global color.diff 'auto'

git config --global color.status 'auto'

git config --global color.branch 'auto'

git config --global credential.helper store

git config --global push.default simple

git config --global core.autocrlf false

git config --global core.eol lf

git config --list

`git branch` see all branches
`git checkout -b branch2.1`
git checkout master
cat .git/HEAD
cat .git/logs/HEAD
git log --oneline --decorate --graph --all
git checkout master
git merge hostfix
git branch -v
git branch -d issu53
git branch --no-merged
