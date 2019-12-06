# 最新微信ipad_7.04_V5协议，功能完善、稳定不易掉线。可以测试demo或api接口。请联系qq：1919670042
可实现微信80%功能；支持62数据登录、扫码登录、收发朋友圈、查看朋友圈、微信建群、微信拉人进群、微信公众号阅读、微信消息收发、微信附近的人定位、微信添加好友、分享小程序、微信加粉、微信收藏、微信标签等<br/>
协议源码使用c#进行开发，开发环境为VS2017 .net framework 4.6.1 <br/>
附送一套6.7版本的ipad协议源码，现在已经不可以异地登陆了，但是拿来学习还是可以的<br/>
# 更新日志
1、新增62数据提取、A16登录、安全设备查询、安全设备删除<br/>
2、新增发送xml格式消息、一键修改密码、绑定解绑手机号码<br/>
3、新增无痕查询僵尸粉、批量删除好友<br/>
4、新增自动抢红包、设置好友备注、0305算法、MMPro<br/>
5、新增发送CDN图片、发送CDN视频、获取大图片、下载视频<br/>
6、新增PC设备辅助登录、新手机辅助登录、应用辅助登录<br/>
# 使用说明
1.通过/api/Login/GetQrCode接口获取二维码，可以设置代理IP，如没有，可前三个参数都设置为""<br/>
2.去http://imgbase64.duoshitong.com/ 进行base64转码，生成二维码图片<br/>
3.扫码登陆，之后调用/api/Login/CheckLogin/{uuid}，传入上个接口生成的Uuid，会返回wxId和用户信息<br/>
4.后续通过wxId进行其他接口的调用<br/>
# 接口文档
![demo1](https://github.com/weixinbao/WeChatXY/blob/master/API.png) 
![demo1](https://github.com/weixinbao/WeChatXY/blob/master/API2.jpg) <br/>
# 声明
仅供自己学习研究使用，引起任何法律纠纷概不负责
# QQ交流群
<a target="_blank" href="https://jq.qq.com/?_wv=1027&k=5yB7iRV">微信协议交流QQ群</a><br/>
![demo2](https://github.com/weixinbao/WeChatXY/blob/master/QQ.png) <br/>

