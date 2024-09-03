# secretmanagerjdbcdemo
[aws-secretmanager-jdbc](https://github.com/aws/aws-secretsmanager-jdbc)のデモ

## 説明
- Spring Bootのアクティブプロファイル `local` を指定すると、application-local.ymlに指定した接続情報からDocker上に起動したMySQLに接続します。
- Spring Bootのアクティブプロファイル `product` を指定すると、AWS SecretManagerから取得した接続情報からDocker上に起動したMySQLに接続します。
