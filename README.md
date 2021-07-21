# OAuth 2.0 登入前端專案

本專案是為了展示前端如何基於 OAuth 2.0 Authorization Code Flow，採用 Facebook 登入取得 Authorization Code，以利後續串接後端服務進行完整 OAuth 2.0 Authorization Code Flow

目前僅展示 Facebook 登入，但 Line 或 Google 登入也一樣

## TL;DR

1. 到 [Facebook for Developers](https://developers.facebook.com/apps) 新增測試 App 並取得 App ID，redirect url 不用填寫
2. 打開 index.html 將剛取得的 App ID 填入第 9 行的 facebookAppId
3. 找個 web server 把此資料夾 host 在本機的 8888 port
4. 打開瀏覽器進入 [此網頁](http://localhost:8888/index.html)

## Reference

[Facebook for Developers Manually Build a Login Flow](https://developers.facebook.com/docs/facebook-login/manually-build-a-login-flow/)
