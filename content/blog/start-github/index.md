---
title: 初めての git push
date: "2019-12-31T22:12:03.284Z"
description: "ブログを開設しました。よろしくお願いします！"
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

```
git push -u origin master
```
