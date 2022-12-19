## vegan-day

### <span style="color: red;">**GET**</span> 커뮤니티 조회
```
/community
```
**Response**
```
{
    "statusCode": 200,
    "responseMessage": "커뮤니티 조회 성공",
    "data": [
        {
            "bid": 1661011934047,
            "title": "Y",
            "userId": "test",
            "hit": 12,
            "comment": 0,
            "writeDt": "01:12",
            "filepath": "http://101.101.219.80:8080/image/2022/08/21/1661011934387.jpeg"
        }
    ]
}
```

### <span style="color: red;">POST</span> 커뮤니티 글 작성
```
/community
```
**Body** <span> form-data</span>
|KEY|VALUE|
|:--:|:--:|
|file|\<file>|
|title|테스트입니다.|

**Response**
```
{
    "statusCode": 200,
    "responseMessage": "커뮤니티 작성 성공",
    "data": null
}
```