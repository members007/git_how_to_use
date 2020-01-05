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
## trouble shooting
### config
`$git config --global user.email ここに自分のアドレス`
`$git config --global user.name ここに自分の名前`

