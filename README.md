# Twitter APIの使い方
## 関連するキーは以下の5つ
### Twitter Developer Portal: https://developer.x.com/en/portal/dashboard にて以下を取得
access_token<br>
access_token_secret<br>
api_key<br>
api_key_secret<br>
bearer_token

## ツイートの取得
```
curl --request GET 'https://api.x.com/2/users/by/username/USER_NAME' --header 'Authorization: Bearer XXXXXX'
```
