## 关于app语音识别报错问题

App端Speech(语音输入)模块封装了市场上主流的三方语音识别SDK，提供JS API统一调用语音识别功能。
<br>

直接使用会报错：

![image](https://github.com/user-attachments/assets/87b6668d-12ab-423b-999e-ee2396f0c2b9)

这里是因为没有在下图里面配置他的Appid、API Key、Secret Key，配置这些需要去[百度语音开放平台](https://console.bce.baidu.com/ai/?fromai=1#/ai/speech/overview/index)申请AppID、API Key、Secret Key。同时要去开通或领取免费配额，不然没法使用

![image](https://github.com/user-attachments/assets/e58f40c4-442b-4394-bc3d-45479cb26e0e)

![image](https://github.com/user-attachments/assets/956cbeff-22f9-4f25-812c-b311ae36f8a1)

有关介绍：https://uniapp.dcloud.net.cn/tutorial/app-speech.html
