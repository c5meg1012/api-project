## GET /users
Index.

### Example

#### Request
```
GET /users HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 225
Content-Type: application/json; charset=utf-8
ETag: W/"59157fd5925a7aeae18572f4aba0e749"
X-Request-Id: 0f0de172-03e1-4bb5-b2bb-1c6aa82be748
X-Runtime: 0.014620

[
  {
    "id": 1,
    "created_at": "2017-12-16T05:09:17.980Z",
    "updated_at": "2017-12-16T05:09:17.980Z",
    "name": "ユーザー1"
  },
  {
    "id": 2,
    "created_at": "2017-12-16T05:09:17.983Z",
    "updated_at": "2017-12-16T05:09:17.983Z",
    "name": "ユーザー2"
  }
]
```
