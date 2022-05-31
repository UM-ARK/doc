---
sidebar_position: 2
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
|username|string||
|password|string||

还需要传输其他个人资料，后续补充。

Return

|Key| Value|Remark|
|-|-|-|
|code|int|`1`为成功|
|message|string|处理成功为`success`,否则将有详细的错误解释|
|info|object|

info

|Key| Value|Remark|
|-|-|-|
|email_verfy_id|string|uuid,验证邮箱验证码时需要提供|

返回正常识别码后进入邮箱验证步骤



