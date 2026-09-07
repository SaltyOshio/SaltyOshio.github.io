# おしおの工作置き場

GitHub Pagesで公開するための静的サイト一式です。

## 構成

```text
/
├─ index.html
├─ .nojekyll
└─ works/
   └─ shine-muscat/
      ├─ index.html
      ├─ shuffle.html
      └─ cards.html
```

## 公開手順

1. GitHubで `<あなたのGitHubユーザー名>.github.io` という名前の公開リポジトリを作成します。
2. このフォルダの中身を、そのリポジトリのルートにアップロードします。
3. リポジトリの `Settings` → `Pages` を開きます。
4. `Build and deployment` の `Source` を `Deploy from a branch` にします。
5. Branchを `main`、フォルダを `/ (root)` にして保存します。
6. 公開後、 `https://<あなたのGitHubユーザー名>.github.io/` からアクセスできます。
