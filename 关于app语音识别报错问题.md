## 关于app语音识别报错问题

App端Speech(语音输入)模块封装了市场上主流的三方语音识别SDK，提供JS API统一调用语音识别功能。

直接使用会报错：

![image-20240711195129756](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20240711195129756.png)

这里是因为没有在下图里面配置他的Appid、API Key、Secret Key，配置这些需要去[百度语音开放平台](https://console.bce.baidu.com/ai/?fromai=1#/ai/speech/overview/index)申请AppID、API Key、Secret Key。同时要去开通或领取免费配额，不然没法使用

![image-20240711195553973](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20240711195553973.png)

![image-20240711185042954](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20240711185042954.png)

有关介绍：https://uniapp.dcloud.net.cn/tutorial/app-speech.html