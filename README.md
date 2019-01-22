# 12306全自动抢票Java版
## 项目说明
这个项目的起因是学Java没有合适的练手项目，然后想起之前用Python写的关于12306抢票的程序，所以用Java重写了一遍。<br>
因为这是我写的第一个Java程序，代码质量并不是很好，大家将就着看。
## 使用方法
在 Main 方法里配置，抢票规则，说明很详细。

## 更新说明
+ 20190122 --> 增加短信通知和语音通知
   + 事情的起因是我跑了4天终于抢到了一张回家的票，但是因为当时我在睡觉没看到邮件，所以因为没有及时付款导致票又没了wtf？？？
   + 所以痛定思痛，我尝试找了短信接口和语音通知接口，当然这种接口一般不是免费的。最开始我在注意到了阿里云，但是阿里云的短信接口和一些第三方的短信接口发送需要练习客服设置模板，甚是麻烦，所以我最后选用了Twilio的通知服务，新用户注册送15美元体验金，足够用了。

## 运行效果
查询以及订票<br>
![runImg](/img/1.png)<br>

发送邮件通知<br>
![emailImg](/img/2.jpg)<br>

短信通知<br>
![smsImg-w100](/img/sms.jpg)<br>

语音通知<br>
![phoneImg-w100](/img/phone.jpg)<br>

