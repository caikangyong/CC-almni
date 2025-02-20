
### 项目介绍


CC校友录结合移动互联网时代，独家引入微信小程序形式，创造全天候的用户体验。 主要面向毕业后在某城市工作的校友，给大家构建一个充分交流的平台，“人脉”积累是本软件的功能特色，通过校友身份这个共同的纽带，为自己的人生道路积累持续的人脉。


### 特点

无广告：本项目希望通过微信小程序，构建一款无广告，真实可靠的毕业校友通讯录。
简约：只做最基础功能，不臃肿，主打内容极简，功能简洁直击痛点
安全：保护校友的信息安全，隐私内容需要申请后可见。
方便：上传自己的个人信息，方便在需要时取得联系。小程序无需下载APP随用随走。


### 技术使用

项目使用微信小程序平台进行开发。
使用腾讯云开发技术，免费资源配额，	无需域名和服务器即可搭建。
小程序本身的即用即走，适合小工具的使用场景，也适合程序的开发。

### 项目效果截图

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060621_49d4c43f_1810934.png "1.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060627_55436a5e_1810934.png "2.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060634_4ff55319_1810934.png "3.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060641_80dacd4d_1810934.png "4.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060648_39c1f771_1810934.png "5.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060655_c5db02ba_1810934.png "6.png")

      

### 部署教程：

#### 1 源码解压
 

#### 2 在微信小程序开发工具中导入 解压后的文件夹
![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060102_2f8d8f02_1810934.png "导入.png")


 

#### 3 开通云开发环境
  参考微信官方文档：https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html

#### 4 数据库操作
建立数据库集合
t_user
t_album
t_info
t_setup

#### 5 云函数及配置
本项目使用到了一个云函数cloud
在云函数cloudfunctions文件夹下选择一个云函数cloud , 右键选择在终端中打开,然后执行 
npm install –product

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060144_cb89de4a_1810934.png "云函数.png")



 

打开cloudfunctions/cloud/comm/config.js文件，配置环境ID

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060154_ea7c36a1_1810934.png "云函数配置.png")


 


#### 6  客户端配置
打开miniprogram/helper/setting.js文件，配置环境ID

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060203_71503106_1810934.png "客户端配置.png")


#### 7  内容安全
  腾讯对小程序有严格的审核机制，每个小程序都要接入内容安全校验，

打开https://developers.weixin.qq.com/community/servicemarket/detail/000a246b6fca70b76a896e6a25ec15 页面，点击购买（实际免费）

![输入图片说明](https://images.gitee.com/uploads/images/2020/1122/060221_e5bc208f_1810934.png "内容安全.png")
 



至此完全配置完毕。

#### 在线演示：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0719/100637_5429f9d1_9240987.jpeg "小程序qr.jpg")

 


#### 如有疑问，可以联系我们： 
#### 作者微信:  cclinux0730 


