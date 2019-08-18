> MessAPI

## 新版特性

1. 相对更加稳定,服务器不再过滤参数内容,用户自行解析参数,减少参数解析出错几率
2. 支持平台：网易云音乐,QQ 音乐,酷狗音乐,酷我音乐,咪咕音乐，百度音乐，具体音乐音质支持往下看
3. 接口更加丰富,增加部分接口和平台
4. 参数控制数据是否格式化,数据更加简洁(format 字段)
5. 降低门槛,参数简单统一,支持 GET,POST 等请求,支持跨域调用
6. 支持输出格式化后的数据

!> 由于空闲时间较少，文档中的可能有错误的信息，请直接在项目中提[issue](https://github.com/messoer/mess-api-doc/issues)

## 使用要求

必须注明 API 版权来源于 [https://github.com/messoer](https://github.com/messoer),如果你的项目开源，你可以把项目捐赠到`messoer`组织中，项目拥有者还是你本人，需要请联系 QQ347784533

## 鸣谢

<a href="https://www.tirr.com.cn/" target="_blank"><img height="60px" src="https://www.tirr.com.cn/files/templates/frontend/CPx5fiBW/images/logo.png"></a>

## 当前版本

`V1.1.1`

-   修复网易云搜索时分页错误
-   修复网易云搜索视频时显示类型不存在
-   更新酷狗获取播放地址
-   更新文档错误信息

更多更新日志，请前往 [更新日志](changeLog.md) 查看

## 联系方式

-   QQ 群 1⃣️：579621905（技术探讨）💰
-   QQ 群 2⃣️：261097396（群友交流）🆓🈵️
-   QQ 群 3⃣️：553632885（群友交流）🆓
-   邮箱： mrdong916@163.com
-   Github： http://github.com/mrdong916
-   Telegram: https://t.me/joinchat/L0YKYkTRL-EGMpC7rTshgg

## 请求说明

以下所有接口请求域名为 `v1.itooi.cn`,为了降低使用门槛，所有请求为`GET`请求,你也可以试用其他请求方式

注意: 请求头中 `Content-type` 为 `application/x-www-form-urlencoded`

请求地址 = 域名 + 接口地址 + 参数

域名：`https://v1.itooi.cn`

接口地址：`https://v1.itooi.cn/netease/song`

参数：`id=37239038`

示例： `https://v1.itooi.cn/netease/song?id=37239038`

## 支持平台

-   网易云音乐 http://music.163.com
-   QQ 音乐 http://y.qq.com
-   酷狗音乐 http://www.kugou.com
-   酷我音乐 http://www.kuwo.cn
-   咪咕音乐 http://www.migu.cn
-   百度音乐 http://music.taihe.com/

> 音乐平台音质： 未注明则为官方不支持或未找到该音质资源,`免费版不支持无损音乐`,如果使用`无损音质`版本请加群了解

| 支持平台 | 普通(48) | 普通(64) | 标准(96) | 标准（128） | 较高（192） | 极高（320） | 无损（ape） | 无损（flac） | Hi-Res(flac) | DSD(dff) |
| -------- | -------- | -------- | -------- | ----------- | ----------- | ----------- | ----------- | ------------ | ------------ | -------- |
| 网易     |          |          |          | mp3         | mp3         | mp3         |             | flac         |              |          |
| Q Q      | m4a      |          | m4a      | mp3         | m4a         | mp3         | ape         | flac         |              |          |
| 酷狗     |          |          |          | mp3         |             | mp3         |             | flac         | flac         | dff      |
| 酷我     | aac      |          |          | mp3         | mp3         | mp3         | mp3         | flac         |              |          |
| 咪咕     |          | mp3      |          | mp3         |             | mp3         |             | flac         |              |          |
| 百度     | aac(64)  |          |          | mp3         |             | mp3         |             |              |              |          |

## 捐赠

!> 关于捐赠，请耐心看完

免费的东西不长久，毕竟家里没矿，生活在三次元的我总要考虑一下恰饭问题，所以有了这个赞助。你的赞助不仅会被用来支付一些开发成本：服务器、域名、付费软件等，还将帮助我奉献更多的时间到项目中。如果你正在使用我的 API，可以用赞助来表示你的谢意，并让项目保持健康和得到更积极的维护

我不会忘记支持我的人，也不会把你的支持当作理所当然，它对我意义重大。

周期性赞助请联系我，你将会得到我的帮助；如果你不喜欢周期性赞助，也可以选择一次性赞助方式：

[支付宝、微信、QQ 钱包](https://i.loli.net/2019/04/26/5cc2a151aebe2.png)

[paypal](https://www.paypal.me/mrdong916)

## 关于项目

目前没有打算开源的想法，不过有个旧版的开源项目，右上角项目地址可以访问到旧版 API [MessMusic](http://github.com/MessMusic)，如果真的想要源码，带着你的诚意来找群主！

## 免责声明

1. 以上开发接口仅限于技术研究和项目开发练习使用，禁止商业用途，如有发现直接禁 IP 和域名
2. 音乐版权归各音乐平台所有，若有侵犯版权，请联系我删除
