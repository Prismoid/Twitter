# Twitter APIの使い方
## 関連するキーは以下の5つ
### Twitter Developer Portal: https://developer.x.com/en/portal/dashboard にて以下を取得
access_token¥n
access_token_secret¥n
api_key¥n
api_key_secret¥n
bearer_token

## ツイートの取得
```
curl --request GET 'https://api.x.com/2/users/by/username/USER_NAME' --header 'Authorization: Bearer XXXXXX'
```
