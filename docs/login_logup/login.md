---
sidebar_position: 2
---

# Login
API for login

## 登录 `POST`

```
/login/login
```
POST

|Key| Value|Remark|
|-|-|-|
|email|string||
|password|string||

Return

|Key| Value|Remark|
|-|-|-|
|code|int|`1` 为成功|
|message|string|处理成功为 `success` ,否则将有详细的错误解释|

cookie

|Key| Value|Remark|
|-|-|-|
|session_id|string||

## 忘记/修改密码 

### 发送邮箱验证码 `POST`

### 验证邮箱验证码 `POST`

### 修改密码 `POST`

### 发送邮箱验证码 `POST`

### 验证邮箱验证码 `POST`

### 修改密码 `POST`