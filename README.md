# serverless-nextjs-example

## デプロイ

`~/.aws/credentials`に資格情報を設定していることが前提条件

```shell
npm install
npx serverless
```

## 公式の方法と違う点

バージョン更新に気づけるように`@sls-next/serverless-component`をインストールしている

```yaml
component: "./node_modules/@sls-next/serverless-component"
```
