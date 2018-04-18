## 第三方应用用户认证&&授权

1、当用户打开App应用区域的未授权第三方应用时，App将会打开一个征求用户授权页面, 如下图：

![image](https://raw.githubusercontent.com/haobtc/openplatform/master/images/auth.jpg)

用户点击授权，则完成授权。

2、当用户授权完成或者已授权用户打开第三方应用时，会直接打开之前在Vendor创建的网站网址, 并携带用AES加密的用户id信息的bot_token。 具体打开的链接地址是:

```
https://your-vendor.im?bot_token=encrypt-bot-token
```

3、通过在创建vendor页面的Bot AES Key对encrypt-bot-token解密，即可获取用户的id，以完成后续的操作。[python解密代码demo](https://github.com/haobtc/openplatform/tree/master/prpcrypt)


经过解密bot_token可以获取用户的user_id, 解密后的信息结构如下：

```json
{
   'user_id': '',
   'nonce': '',
   'timestamp':''
}

```

通过此user_id进一步获取用户的其他相关信息

