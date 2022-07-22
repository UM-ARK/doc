# Activity

API for Activity

# 获取活动`GET`

```
/info/activity
```

Return


| Key          | Value | Remark                                           |
|--------------|-------|--------------------------------------------------|
| activity_id  | int   |                                                  |
| title        | str   |                                                  |
| type         | str   | ACTIVITY 普通活動, OFFICIAL 澳大官方, WEBSITE 需 web 跳轉類型 |
| link         | str   |                                                  |
| created_by   | str   | id of club                                       |
| coverImgUrl  | str   |                                                  |
| relateImgUrl | array |                                                  |
| timeStamp    | int   |                                                  |
| state        | int   | 0:hide;1:publish;2:deleted;                      |