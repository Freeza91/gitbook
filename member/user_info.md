## 获取用户信息

获取用户的详细信息，必须携带access_token, 获取access_token[详见](./获取Access_Token.md)

```
GET https://bixin.im/platform/api/v1/user/:user_id?access_token=30e57a621fa2474c914ac7ca6c85cc18

```

返回

```
{
    "username": "freeza",
    "vendor.BTC.hold": "10",
    "vendor.CNY.hold": "0",
    "vendor.CNY.cash": "0",
    "fullname": "freeza91",
    "id": 1,
    "vendor.BTC.cash": "10"
}
```
