# git使い方
## gitの使用宣言
`$ git init`
## remote repositoryを作る
git gubのサイト上で新しいリポジトリを作成する。そのurlをコピーしておく。
## gitのremoteと自分のPCを関連付ける
`$ git remote add origin <URL>`
## add commit push pull で回す
### add
`git add *file*`
### commit
`git commit -m "message"`
### push 
`git push origin master`
### pull
`git pull origin master`
## other commands
### check added file
`git status`
### check differences
`git diff`
## branch
ひとつのrepositoryの中に複数の流れを作成し、それぞれ独立に作業を進める。作業が終了したらmergeしてひとつの流れに統合することも出来る。
### create branch
`$ git branch <branchname>`
e.g.)
`$ git branch issue1`
`$ git branch`
`issue1 * master`
`*` is current prepository

config branch using
`$ git branch`
### checkout branch
to edit the contents of branch we have to checkout
e.g)
checkout issue1
`$ git checkout issue1`
after checkout we can use git as ususal
### merge
1. move to master
`$ git checkout master`
2. merge
$ git merge issue1
### delete branch
`$ git branch -d <branchname>`

## trouble shooting
### config
`$git config --global user.email ここに自分のアドレス`
`$git config --global user.name ここに自分の名前`

