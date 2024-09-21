# Twitter APIの使い方
## 参考：Twitter Developer Tutorial: https://developer.x.com/en/docs/x-api/tutorials
## 関連するキーは以下の5つ
### Twitter Developer Portal: https://developer.x.com/en/portal/dashboard にて以下を取得
access_token<br>
access_token_secret<br>
api_key<br>
api_key_secret<br>
bearer_token

## ユーザIDの取得
```
curl --request GET 'https://api.x.com/2/users/by/username/USER_NAME' --header 'Authorization: Bearer XXXXXX'
```

## ツイートの取得(有料版のみ...)
```
curl --request GET 'https://api.x.com/2/users/USER_ID/tweets' --header 'Authorization: Bearer XXXXXX'
```