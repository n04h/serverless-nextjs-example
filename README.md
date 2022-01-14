# serverless-nextjs-example

## 環境構築

```shell
npm install
```

## Next.jsのサーバー起動

```shell
npm run dev
```

## デプロイ

※ `~/.aws/credentials`に資格情報を設定していることが前提条件

```shell
npx serverless
```

## デプロイしたリソースの削除

現状できなさそう...？

https://github.com/serverless-nextjs/serverless-next.js/issues/881

## 公式の方法と違う点

バージョン更新に気づけるように`@sls-next/serverless-component`をインストールしている

```yaml
component: "./node_modules/@sls-next/serverless-component"
```
