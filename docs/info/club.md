# Club Info
API of Club

获取社团信息 `GET`
```
/info/club
```
Return

|Key| Value|Remark|
|-|-|-|
|code|int|`1` 为成功|
|message|string|处理成功为 `success` ,否则将有详细的错误解释|
|content|array|

item in `content`

| Key| Value  | Remark|
| --------- | ------ | ---------------------------------------------------------------------------------------------- |
| clubID    | int    |                                                                  |
| name      | str | 社團/組織名                                                                                    |
| tag       | str | sa 學生會, club 學會, society 社團, college 書院, official 澳大官方, media 媒體, business 商業 |
| introText | str |                                                                                       |
| contact   | obj  |                                                                       |

`contact`

| Key  | Value  | Remark|
| ---- | ------ | ----------------------------------------------------- |
| type | str | 聯繫類型，Wechat，Email，Phone，IG，Facebook，Website |
| num  | str    ||
