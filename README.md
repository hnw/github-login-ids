[ユーザー情報を取得するGitHub API](https://developer.github.com/v3/users/#get-all-users)を利用して作った、GitHub login IDの一覧を公開します。

dataディレクトリの下に、100万ID刻みで取得したカンマ区切りファイルが置いてあります。このカンマ区切りファイルの各行には、次の3カラムが記録されています。

| Name     | Description           |
|--------- | --------------------- |
| ID       | 連番と思われる数値のID   |
| login ID | ログインID             |
| type     | UserまたはOrganization |

