---
title: 初めての git push
date: "2019-12-31T22:12:03.284Z"
description: "リモートリポジトリヘ push するまでの手順を解説します。"
---


## git push までの手順
ローカルリポジトリの作成
```
git init
```

commit範囲を指定  
`.`は全範囲選択
```
git add .
```

コミット  
`-m "コミットメッセージ"`
```
git commit -m "first commit"
```

ローカルリポジトリにリモートリポジトリを紐付ける
```
git remote add origin <ssh>
```

ローカルリポジトリの変更内容をリモートリポジトリに反映させる  
`-u`オプションで次回から`git push`だけで push できる
```
git push -u origin master
```
