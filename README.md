# Autoer

大二暑期大作业，汽车助手App

## 主页面截图
![image](http://o9oomuync.bkt.clouddn.com/autoer%E5%9B%BE%E7%89%871.png)
![image](http://o9oomuync.bkt.clouddn.com/autoer%E5%9B%BE%E7%89%872.png)
## 基础功能

#### 注册，登陆，个人信息

#### 预约加油：

(1)	绑定一个汽车信息（个人可有多辆汽车）

(2)	含有姓名，时间，加油站，加油类型，加油数量（升或金额）等信息。

(3)	把数据发送给服务器并存储，生成二维码。此预约订单在APP显示二维码，以便去加油站扫码加油。

(4)	APP可查看提交后的预约订单详情

#### 地图实时显示当前汽车位置，并显示周围的加油站

(1)	以手机为载体作为汽车，实时更新当先位置

(2)	并显示周围的加油站和显示加油站相关信息

#### 维护车辆信息

(1)	可维护多辆个人汽车。

(2)	假设汽车屏幕可提供此车辆当前信息的二维码,可供用户扫码，APP可扫码并把个人汽车信息维护到手机里面。（因此要求学生自己生成一个二维码，然后通过手机扫码完成此功能。）

(3)	信息包含但不限于：汽车品牌、标志、型号、车牌号码、发动机号、车身级别（几门几座）、里程数、汽油量（%）、发动机性能（好、异常）、变速器性能（好、异常），车灯（好、坏）。

(4)	汽车信息也需要维护到服务器端的数据库里。

(5)	要求把以下通知及时推送到手机端
* 当服务器端的数据库里记录的汽油量少于20%时，给手机发送通知告诉汽车车主该去加油
* 当服务器端的数据库里记录的里程数每超过15000公里倍数时，给手机发送通知告诉汽车车主需要进行维护
* 当服务器端的数据库里记录的发动机出现异常、变速器出现异常或车灯有坏的时候，给手机发送通知告诉汽车车主需要进行维修
* 因无车载设备把汽车数据传给服务器，因此功能需求(5)可手动更改数据库的值进行功能测试。

#### 进阶功能
(1)	可播放音乐
* 进入APP的时候，音乐自动播放
* 出APP的时候，音乐结束
* 音乐轮播
* 请选项合适的音乐
(2)	交通违章信息
* 通过之前被绑定的车牌号和发动机号，调用（http://www.cheshouye.com/api.html（参考））提供的接口，获得违章信息并显示。
(3)	根据路况选择最优线路
* 起始点为：可输入地址或当前位置
*	目的地：可输入地址
*	起始和目的地可互换
*	给予最优线路，并可实时告知当前位置

### 声明
 使用了一些第三方开源库， 等有空的时候补上列出， 向这些第三方开源库的作者表达感谢

License
-------

    Copyright 2015 Jude

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.




