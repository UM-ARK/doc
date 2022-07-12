# edit_club_info
## Description:
 To updata the club info by id.

## Request URL:
`http://XXX.XXX/edit_club_info/`

method: POST

### POST parameters：
|name|required|type|illustrate|
|---------|--------|----|----------|
|id       |yes     |str |to query info for the specified ID|
|intro    |yes     |str |the update introText data|
|contact  |yes     |array|the update contact data|

 * contact array example:
 `[{"type":"Email","num":"umsu.umsuacs@umac.mo"},{"type":"Facebook","num":"澳門大學動漫研究會(umacs)"}]`



## Return example
```go
```json
{
   "code":"1",
   "message":"success"
}
```