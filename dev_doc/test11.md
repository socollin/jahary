# TEST API

## test Api 

### PATCH /api/test


### Parameters

| Name |  | Description |
| --- | --- | --- |
| token |  *required* | token |
| test_code |  | airport_code |


### Request

#### Route

```
PATCH /api/test
```

### Body

```
token=TOKEN_OF_USER_1&test_code=THE42R
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
  "testvalue": {
    "id": 1,
    "name": "지훈",
    "code": "jh",
  },
  “name_code": "PJH",
  “name": "지훈",
  "non_airport_org": true,
  "messages_count": 1,
  "count": 0
}
```


