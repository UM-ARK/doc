---
sidebar_position: 1
---
# Registration

API for registration

## 注册 `POST`

```
/register/register
```
POST

|Key| Value|Remark|
|-|-|-|
|email|string||
|password|string||
|info|object|personal information|

还需要传输其他个人资料，后续补充。

Return

|Key| Value|Remark|
|-|-|-|
|code|int|`1` 为成功|
|message|string|处理成功为 `success` ,否则将有详细的错误解释|
|info|object|

cookie

|Key| Value|Remark|
|-|-|-|
|email_verify_id|string|uuid|

返回正常识别码后进入邮箱验证步骤

## 注册验证邮箱 `POST`

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

