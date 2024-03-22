# corp.craft-bank.com

以下のページについてのソースコードです。

- [クラフトバンクオフィス](https://corp.craft-bank.com/cbo)
- [クラフトバンク総研](https://corp.craft-bank.com/cb-souken)


## サーバー環境

領域 | 利用サービス
--|--
Hosting | [Netlify](https://netlify.com)
CMS | [Contentful](https://contentful.com)
Mail Form | [formrun](https://form.run)

## 実装環境構築

node環境が必要です

インストール
```
npm i
```

開発環境の起動
```
npm start
```

> [!NOTE]
> ローカル環境でContentfulをプレビューするには [.env](https://www.notion.so/psephopaiktes/Blog-Portfolio-Renewal-ad291ee9ac9d445489982f8ca9daf450)🔒 ファイルがルートに必要です



## 本番デプロイ
以下がhookされてNetlifyに自動デプロイされます。

* GitHubの`main`ブランチ更新
* Contentfulの更新
