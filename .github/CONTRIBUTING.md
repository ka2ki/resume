# 職務経歴書の更新

1. 該当ファイルの.md を編集する

```
/docs/README.md
```

2. `yarn lint` で textlint を実行
3. master プッシュで `pages-build-deployment` の Actions が走り githubPages へデプロイ
4. タグ付け（v0.0.n など）しプッシュすることで、`build pdf` の Actions が走る
