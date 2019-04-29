# @now/node express basic auth example


これは https://zeit.co の now という paas で @now/node ビルダーと express を使って
静的な web サイトを basic 認証付きで提供するサンプルです。

basic 認証ですので、クリティカルな用途には向きませんが、最低限の認証をつけて web ページで情報を共有するには便利だと思います。

## 使い方

* https://zeit.co/ でアカウントを使って `now` をインストールしてください。
* `index.js` 中の `myid` と `mypassword` を書き換えてください
* 必要に応じて `now.json` 中の `"name"` や `"alias"` の値を書き換えてください。
* `public` ディレクトリー以下を提供したい物と入れ替えてください。
* `now` コマンドでデプロイしてください。
