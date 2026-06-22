# Komari-Float
[![Xun-X](https://img.shields.io/static/v1?label=作者&message=Xun-X&color=F36CB0)](https://github.com/Xun-X)
[![Xun-X](https://img.shields.io/static/v1?label=特别感谢&message=komari-monitor&color=97C40F)](https://github.com/komari-monitor)
[![Xun-X](https://img.shields.io/static/v1?label=特别感谢&message=Doornail&color=1081C2)](https://www.nodeseek.com/space/16791#/general)
[![Xun-X](https://img.shields.io/static/v1?label=软件特点&message=便携、简易&color=48C21A)](https://github.com/Xun-X/ServerStatusFloat)
[![Xun-X](https://img.shields.io/static/v1?label=获取方式&message=点击下载&color=F48041)](https://github.com/Xun-X/Komari-Float/raw/refs/heads/main/download/Komari-Float.7z)
[![Xun-X](https://img.shields.io/static/v1?label=兼容版本&message=v1.2.3&color=F7F720)](https://github.com/komari-monitor/komari/releases/tag/1.2.3)

探针悬浮窗，Windows显示服务器监视悬浮窗，实时监看服务器状态 (基于 Komari Monitor 探针)

关键词：`Komari Monitor 探针` `Komari Monitor 悬浮窗` `Komari Monitor 漂浮窗`

##### 让我们一起共建庞大的监控室大爷团队，时刻掌握小鸡状态！

##### 注意：因为人懒，本项目不跟随官方最新版本更新，监控悬浮窗基于 Komari Monitor v1.2.3 版本开发

## 效果展示：
#### 详细主题 全显示
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_01.png)

#### 详细主题 单个显示
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_02.png)

#### 简略小窗
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_03.png)

#### 简略大窗
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_04.png)



## 程序说明：
本程序是拉取已搭建好的[Komari Monitor 探针主控]，数据经过处理后用于飘浮窗显示服务器状态，所以需要先在

服务器需要搭建好 [Komari Monitor] 探针主控服务端

程序运行方式简单说明：

主程序启动后会在所在的目录下创建2个可执行程序、1个配置文件

1、第1个执行程序是从探针主控获取nodes(探针客户端列表信息)数据并处理成主程序可用数据格式

2、第2个执行程序是实时从探针主控获取所有探针客户端的详细数据并缓存到系统默认缓存目录

3、主程序(浮窗本体)会根据配置的间隔时间循环读取缓存的详细数据并显示出来

##### 设置简单说明：
例：[探针主控WEB] 访问地址是：```http://tz.dommain.com```

如图：
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_05.png)

##### 参考如下设置即可：
![](https://raw.githubusercontent.com/Xun-X/Komari-Float/refs/heads/main/image/Screenshot_06.png)

特别说明：
```
1、 [设备名称配置] 填入的 [内容] 与WEB上对应的 [服务器名称] 相同即可
2、 服务器WEB地址可以用套了CDN的https或直接访问http+端口，地址结尾不加"/"即可 (如上图)
```


#### 特别说明
因为人比较懒，本项目不跟随原作者版本进行更新，目前版本基于Komari Monitor v1.2.3制作，需要实现监看效果首

先需有一台服务器搭建主控端再把需要被监控的服务器装上探针agent，通过本程序配置好对应的服务器主控端的WEB，

以及配置好需要显示的服务器信息即可方便地监看服务器状态


#### 更新历史
更新版本(v1.01)：
```
1、基于之前基于哪吒探针制作的改版而来
```

.

#### Komari-Float 探针悬浮窗 下载地址：[点击下载](https://github.com/Xun-X/Komari-Float/raw/refs/heads/main/download/Komari-Float.7z "GITHUB下载")

.

Komari-Float 探针悬浮窗 是编译好的发布版本，就不公开源码了(小白也看不懂)非主流语言编写的。再加上做得

很粗糙，就不放出来显摆(丟人現眼)了，程序无后门，无上传数据功能，启动会检查是否有新版本升级，以及从主

控拉取信息此外无任何其他联网功能，可放心使用！

### 关于 [ 被害妄想症 ] 的完美解决方案
方案1：`关闭这个页面(不开源的都是病毒见不得人，即使开源也看不懂`

方案2：`找其他人帮你试 “毒”`

方案3：`求助其他大神帮您反编译及分析`

方案4：`上传到 http://habo.qq.com 进行分析`

方案5：`上传到 http://www.virscan.org 在线病毒扫描（有报毒就别用了，有人想害你）`
