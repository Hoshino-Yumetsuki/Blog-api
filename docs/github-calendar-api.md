# Github Calendar API

## 使用示例

```
https://gcapi.anjiurine.top/api/?<user_id>
```

例如：

```
https://gcapi.anjiurine.top/api/?Anjiurine
```

### 响应

#### 正确返回值

```
{
    "total": 13,
    "contributions": [
        [
            {
                "date": "2022-12-04",
                "count": 0
            },
            {
                "date": "2022-12-05",
                "count": 0
            },
            {
                "date": "2022-12-06",
                "count": 0
            },
            {
                "date": "2022-12-07",
                "count": 0
            },
            {
                "date": "2022-12-08",
                "count": 0
            },
            {
                "date": "2022-12-09",
                "count": 0
            },
            {
                "date": "2022-12-10",
                "count": 0
            }
        ]
    ]
}
```

#### 错误返回值

```
{
    "code": 201,
    "msg": "无法获取到用户名"
}
```