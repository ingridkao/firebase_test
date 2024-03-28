# firebase_test

預計透過side-project來使用firebase上面的部分項目

## side project說明

這是一個小型網路應用，用於追蹤股票投資的交易記錄和報酬率。以下是應用的功能摘要：

- 用戶登入: 提供用戶身份驗證機制，將會使用Google Authentication相關服務。
- 記錄交易: 用戶可以記錄每次買入和賣出的股票交易，包括股票代號、股數和交易時間。
- 查看交易歷史: 提供用戶瀏覽交易歷史，以查看所有買入和賣出的記錄。
- 即時股票股價: 整合第三方股票API，提供即時股票股價數據，讓用戶可以查看。
- 持有股票報酬: 根據用戶持有的股票數量和購入價格，計算並顯示每支股票的報酬率。
- 圖表顯示持有股票佔比: 使用圖表庫如Chart.js來顯示用戶持有的不同股票的佔比。

## 預計涵蓋項目

排序為**過去使用過**到**沒有使用過**的項目

1. [Authentication身份驗證](https://www.notion.so/ingridkao/FirebaseSDK-Firebase-Authentication-81c8e462c7934902b7658db33e78e2fe?pvs=4)
2. Hosting: 託管部屬
3. Realtime Database即時資料庫
4. Cloud Storage: 使用NoSQL即時資料庫
5. Cloud Functions: 伺服器端邏輯，在這裡實現特定的業務邏輯，如計算報酬率、整合股票API等。

## 後續想要研究的項目

6. Cloud Firestore
7. Cloud Messaging

## ENV

```sh
VITE_FIREBASE_API_KEY=Firebase API key
VITE_FIREBASE_AUTH_DOMAIN=Firebase authDomain
VITE_FIREBASE_PROJECT_ID=Firebase projectId
VITE_FIREBASE_STORAGE_BUCKET=Firebase storageBucket
VITE_FIREBASE_MESSAGING_SENDER_ID=Firebase messagingSenderId
VITE_FIREBASE_APP_ID=Firebase appId
VITE_FIREBASE_MEASUREMEN_ID=measurementId

```
