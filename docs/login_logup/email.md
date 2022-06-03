---
sidebar_position: 3
---
# Email Verification

API for email verification


### 注册验证邮箱 `POST`

```
/register/email
```

|Key| Value|Remark|
|-|-|-|
|code|string||

Return

|Key| Value|Remark|
|-|-|-|
|code|int|`1` 为成功,即注册账户完成|
|message|string|处理成功为`success`,否则将有详细的错误解释|

后端请检索 `cookie` 中的 `email_verify_id`

### 登陆后修改密码 `POST`
```
/pw/email
```
POST



### 忘记密码 `POST`
```
/forget/email
```

POST

