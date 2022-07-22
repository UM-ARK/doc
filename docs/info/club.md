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

| Key              | Value    | Remark                                                                        |
|------------------|----------|-------------------------------------------------------------------------------|
| club_id          | str      |                                                                               |
| club_num         | int      | 自動增加                                                                          |
|club_account| str      ||
|club_password|str||
| logo_url         | int      | url                                                                           |
| name             | str      | 社團/組織名                                                                        |
| tag              | str      | SA 學生會, CLUB 學會, SOCIETY 社團, COLLEGE 書院, OFFICIAL 澳大官方, MEDIA 媒體, BUSINESS 商業 |
| introText        | str      |                                                                               |
| contact          | obj list |                                                                               |  
| club_photos_list | str list | 相片的url list                                                                   |

`contact`

| Key  | Value  | Remark|
| ---- | ------ | ----------------------------------------------------- |
| type | str | 聯繫類型，Wechat，Email，Phone，IG，Facebook，Website |
| num  | str    ||
