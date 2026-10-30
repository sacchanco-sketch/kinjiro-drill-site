# 金次郎ドリル 公開サイト

アプリ「金次郎ドリル」のプライバシーポリシーとサポートのページです。ビルド不要の、素の HTML と CSS で、GitHub Pages でそのまま公開できます。

| ページ | ファイル |
|---|---|
| トップ | `index.html` |
| プライバシーポリシー | `privacy.html` |
| サポート | `support.html` |

## 公開の手順(GitHub Pages)

1. GitHub で、新しいリポジトリ `kinjiro-drill-site` を、**Public** で作る(README や .gitignore は追加しない)。
2. このフォルダで、次を実行する。

   ```powershell
   git remote add origin https://github.com/sacchanco-sketch/kinjiro-drill-site.git
   git push -u origin main
   ```

3. GitHub のリポジトリで、Settings > Pages を開き、Build and deployment の Source を「Deploy from a branch」にして、Branch を `main`、フォルダを `/ (root)` にして Save する。
4. 1〜2分ほど待つと、次の URL で公開される。

   - https://sacchanco-sketch.github.io/kinjiro-drill-site/
   - https://sacchanco-sketch.github.io/kinjiro-drill-site/privacy.html
   - https://sacchanco-sketch.github.io/kinjiro-drill-site/support.html

App Store Connect には、プライバシーポリシーの URL に `privacy.html`、サポート URL に `support.html` の URL を登録する。

## 更新するとき

ファイルを編集して、commit・push すれば、自動で反映される。`privacy.html` を変更したときは、本文の「最終更新日」(2か所)も書き換える。
