#h5 支付

##JS SDK

### 调用币信支付

```
bixin.openPay({
      nonce: '',
      signature: '',
      amount: '1.05',
      recipientAddr: '15Rxxxxx',
      note: 'pay to friend'，
      category: data.category,
      currency: 'BTC',
      arg0: data.arg0,
      arg1: data.arg1,
      arg2: data.arg2,
      arg3: data.arg3,
      arg4: data.arg4,
      arg5: data.arg5,
      arg6: data.arg6,
      arg7: data.arg7,
      arg8: data.arg8,
      arg9: data.arg9,
      success: function(res) {
      },
      error: function(err) {
         // 各种错误，包括用户取消支付
         // TODO: 错误信息
      }
});
```
recipientAddr 是收款方的地址。

args0 ... args9 是转账信息备注

## Schema

对地址转账:

```
bixin://currency_transfer/?target_addr={}&amount={}&currency={}&category={}&args={}
```
amount，category，args均为optional

例如：

```
bixin://currency_transfer/?target_addr=16kUc5B48qnASbxeZTisCqTNx6G3DPXuKn&amount=1&currency=BTC&category=test

```
对币信平台内部地址转账，会走0手续费实时到账的方式，对于外部地址，币信会走链上的转账(建议转账都币信内部转账)。

对Target_Id 转账:

```
bixin://currency_transfer/?target_id={}&conv_type={}&amount=1&currency={}&category={}&args={}
```
conv_type的选项为：private(对个人转账)，bot(对bot转账)。

amount，category，args均为optional

例如：

```
bixin://currency_transfer/?target_id=b620ea4e87b0e5d3f12dd15c97a&conv_type=private&amount=1&currency=BTC&category=test
```
