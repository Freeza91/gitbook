# 币信消息推送机制

币信平台是通过推送消息来实现对第三方平台进行通知。在币信网站，每次触发一些事件(转账、登录等)都会生成相关的Event类，Event类会保存事件触发时的所有关键信息,币信会实时的在后台监听每个Event事件，一出现新的Event类，就会按照既定的规则对外发送Event事件内容，直到通知第三方成功或者连续间隔几秒内通知4次均失败，则不在进行通知。

## 配置Event Callback 地址
通过设置Webhook来配置Event事件通知的Callback地址，每次触发Event，则会实时向此处配置的Callback地址中发送Event事件的Post请求。

## 配置加密数据
系统会默认为每个Vendor生成aes_key.

![image](https://raw.githubusercontent.com/haobtc/openplatform/master/images/vendor_aes_key.png)

用户可选择关闭或者使用数据加密推送，如果不使用，币信则不会对推送的数据进行加密，除非你有自己的安全策略，否则不建议关闭加密推送。

## Event通知数据构成

```
{
  'vendor_name': 'your-vendor-name',
  'subject': 'event-name',
  'event_id': 'event-id',
  'payload': {}, #vendor-event-detail-info
}

```
vendor_name 是之前创建应用的app name

subject 有两种类型：

```
vendor_qr_login: 用户登录之后，触发

user2vendor.created: 用户发生对vendor的转账后触发

```

event_id 是事件发生的ID号，币信产生的不同事件Event Id均不会重复。

## Event通知尝试机制
当Vendor发生事件触发产生Event事件类的时候，币信会实时向Vendor Webhook地址发送通知，币信的通知最多会尝试三次，直到通知成功。如果上一次通知失败，币信会间隔几秒然后再发送通知, 直到四次通知均失败则结束通知。
