# Profiles API

## Updating personal profile

### PATCH /api/profile


### Parameters

| Name |  | Description |
| --- | --- | --- |
| token |  required | token |
| favorite_airport_code |  | airport_code |


### Request

#### Route

```
PATCH /api/profile
```

### Body

```
token=TOKEN_OF_USER_1&favorite_airport_code=TAK
```


### Response

#### Status

```
200 OK
```

#### Body

```json
{
  "id": 2,
  "name": "MyString",
  "department": {
    "id": 1,
    "name": "旅客",
    "code": "KD",
    "icon_filename": "department01.png"
  },
  “airport_code": "TAK",
  “airport_name": "高松空港",
  “favorite_airport_code": "TAK",
  "chat_role": 1,
  "non_airport_org": true,
  "unread_important_messages_count": 1,
  "unread_emergency_messages_count": 0,
  "unread_announcement_count": 1
}
```


