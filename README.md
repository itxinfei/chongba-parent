## 冲吧

### 交流方式：

QQ技术交流群：863662849<a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=9yLlyD1dRBL97xmBKw43zRt0-6xg8ohb&jump_from=webapi">
<img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="Java项目交流+求职面试" title="Java项目交流+求职面试"></a><a target="_blank" href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=f0hLSE9OTkdHTT8ODlEcEBI" style="text-decoration:none;"><img src="http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_02.png"/></a>

### 演示地址
http://virtual-e-commerce-java.research.itcast.cn/

充吧项目只深挖虚拟交易自身业务和技术特点，对于前置的页面，订单，支付等业务不作为重点学习，因此这些模块我们直接导入使用即可。虚拟业务最大技术特点和对接过程中由于网络，双方系统各种问题，会有延迟，重试，及最后订单同步成功失败等一些列问题，所以充吧项目在话费充值业务这块主要实现了

1：接收充值成功的消息然后去和供应商对接

2：对接失败进行重试，并且限制了重试次数

3：平台余额不足进行供应商的轮转

4：网络异常进行重试

5：对接成功后修改订单状态

### 页面
![输入图片说明](https://images.gitee.com/uploads/images/2020/0811/160024_0d3fb9f8_800553.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0811/160035_2c6497d3_800553.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0811/160056_1fc3fe42_800553.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0811/160106_463249cb_800553.png "屏幕截图.png")
