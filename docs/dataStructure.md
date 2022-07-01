# 數據結構

## 社團信息

| Key       | Value  | Remark                                                                                         |
| --------- | ------ | ---------------------------------------------------------------------------------------------- |
| clubID    | Num    | 組織進駐 UMALL 給的 ID，先到先得                                                               |
| avatarUrl | String | HTTPS 鏈接                                                                                     |
| name      | String | 社團/組織名                                                                                    |
| tag       | String | sa 學生會, club 學會, society 社團, college 書院, official 澳大官方, media 媒體, business 商業 |
| introText | String | 簡介文字                                                                                       |
| contact   | Array  | 聯繫方式，子元素為 Obj                                                                         |

contact 子元素 Obj ↓

| Key  | Value  | Remark                                                |
| ---- | ------ | ----------------------------------------------------- |
| type | String | 聯繫類型，Wechat，Email，Phone，IG，Facebook，Website |
| num  | Num    | 相關聯絡號碼，String                                  |

## 活動信息

| Key          | Value  | Remark                                                        |
| ------------ | ------ | ------------------------------------------------------------- |
| eventID      | Num    | 活動/事件 ID，服務器定                                        |
| title        | String | 活動/事件標題                                                 |
| type         | String | activity 普通活動, official 澳大官方, website 需 web 跳轉類型 |
| link         | String | 當 type 為 website 時需要 HTTPS 鏈接                          |
| coverImgUrl  | String | HTTPS 鏈接                                                    |
| relateImgUrl | Array  | 該活動相關的圖片，最多 4 張。包含 String 的圖片 URL           |
| timeStamp    | Num    | 13 位時間戳                                                   |

## 新聞信息

| Key | Value | Remark |
| --- | ----- | ------ |
| -   | -     | -      |

## 通知信息 - 未確定

| Key       | Value  | Remark                                 |
| --------- | ------ | -------------------------------------- |
| messageID | Num    | 通知信息的 ID 服務器定                 |
| type      | String | text 文本通知，website 網址鏈接，image |
| title     | String | 標題                                   |
| content   | String | 內容                                   |
| eventID   | Num    | 該通知對應的跳轉活動                   |
