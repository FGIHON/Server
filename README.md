# GIHON GitHub Server

## Note

### /cookie
Cookieの使えないサービス（GAS WebAppなど）で擬似的にCookieを利用するためのファイル。
`url`パラメータに`encodeURIComponent()`したURLを渡すことで、`id`パラメータにCookie用IDを加えた上で埋め込む。
