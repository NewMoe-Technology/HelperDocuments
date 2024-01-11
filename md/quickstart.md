# ACT —— 从入门到~~精通~~放弃

> #### 关于ACT
ACT只是一个提供各种插件执行的平台，它的功能不限定于伤害统计、时间轴、技能提醒监控等。
大多插件以DLL形式提供下载，而呆萌整合包已经将常用的插件打包整合，不需要你再做另外的设置，简单易用且方便。
以下列表是目前提供的常用插件说明，更多便捷功能将会在日后逐步增加。


| 原插件名 | 中文名 | 插件说明 |
| :-----| :----- | :----- |
| FFXIV\_ACT\_Plugin.dll | FFXIV解析插件 | FF14的ACT核心，所有插件基于其才能运行。 |
| ACT.OverlayPlugin.dll | 悬浮窗插件 | 伤害统计、时间轴美化等悬浮窗的依赖插件，请保持这个插件在第一加载顺位。 OverlayPlugin WSServer是其附带的ws功能插件|
| ACT.TriggerNometry.dll | 高级触发器 | 触发器插件,可以自行制作/导入他人制作的触发器来实现许多功能。 |
| Cafe.Matcha.dll | 抹茶Matcha | Cafe出品，多功能合集插件 |
| ACT.TTS_CN.dll | TTS中文引擎 | 呆萌出品，中文语音合成插件，但是由于token被盗问题已经失效，正在长期施工中，如需要tts相关帮助请查阅帮助中心文档[tts出现不播报或播报不全等问题？](md/qa/TTS_error.md) |
| CactbotOverlay.dll | 仙人掌插件(暂名凯科特爆特) | 伤害统计美化、时间轴、副本监控狩猎监控等功能性插件。插件说明请点击：-> [NGA](https://bbs.nga.cn/read.php?tid=18986135)|
| ACT.Ping.dll | 延迟监控 | 检测你本地到ffxiv服务器的延迟|
| StarlightBreaker.dll | 星光回路遮断器 | 屏蔽词解除工具 |
| SilverDasher.dll | 银山雀儿 | 公开透明的共享狩猎平台 |

## FFXIV解析插件
<font color= red>此为ACT的核心插件，请不要擅自删除或移动该DLL文件。</font>

* 详细设置相关请查看下图说明
* 正常情况下，玩家只需要做解析范围的相关设置。电脑比较好的玩家可以选择团队范围，稍差的则可以选择小队或者只监控自己。

![](/ACT_Helper/img/Analysis.png "解析插件设置相关说明")



## 高级触发器 Triggernometry

ACT真正最具争议的插件，只是黑锅甩给了TTS。用它导入作者为各副本定制的轮椅，你就无须再站起来了。
导入网上发布的后缀为.xml的触发器脚本，勾上复选框便可以启用相应功能。***在导入xml文件之前，请先确认是否为触发器脚本，无关的xml文件会导致报错。***
当你不使用某些触发提示时，请将其相应提示禁用。

![](https://i.imgur.com/csGycPG.png)

## 语音插件 
它，只是一个文字转语音播报插件，用语音合成引擎为其他插件的语音播报提供TTS功能，但是被背上了所有的骂名……ACT插件的黑锅王。
 #### TTS_CN（diemoe出品）
简单易用的TTS插件，自带音量调节、语速调节、同音词发音替换等功能，多种语言、人声可选
——但是很可惜，暂时无法正常使用，起码现在不行，在不远的将来也许可能可以继续使用

## 抹茶 Matcha

FFCafe出品，提供诸多功能，可按需求启用

播报功能（可选tts播报或/和消息中心通知播报）
- 过图播报：播报你即将到达哪张地图（可选只副本或全部地图）  
- 排本播报：排到副本后播报通知（随机副本无法透视）  
- 咬钩提示：钓鱼时播报咬钩（可选开启咬钩力度）  
- 挖宝播报：播报挖宝开门/转盘结果（发光门、雷神等特殊情况无法播报）  
- F.A.T.E播报：监控播报本地图刷新的已勾选的fate、NM(优雷卡)、SM(博兹雅)（可选名称、等级），可加载模板，默认模板为古武的9本小黄书  
- 博兹雅播报：监控播报本地图刷新的紧急遭遇战（Critical Engagement, CE）  

悬浮窗功能（与悬浮窗插件联合使用）

- 物价记录：记录当前市场交易板的物品最低价格（打开universalis集成后，可上传物价并查询其他服务器的物价）（可选hq过滤）  
- 配装比较：记录自身配装与目标配装（需打开一次目标装备界面）  
- 仙人微彩：刮刮乐计算器，根据期望计算，提供金碟刮刮乐建议  
- 地图事件：
  - 快速查看已开启的藏宝图对应点位  
  - 订阅指定大区的在F.A.T.E播报里勾选的临危受命（未勾选任意F.A.T.E.时默认订阅小电视和大象）

Webhook（需要一定的使用技巧）

- [优雷卡自动史记](https://bbs.nga.cn/read.php?tid=28547954)
- ...

## 网络延迟显示

~~*显示你的网有多差*~~  显示你的客户端到服务器的网络延迟，可用来判断滑步。

## OverlayPlugin悬浮窗插件

提供基于网页的悬浮窗显示功能。可基于此插件设置各种各样的悬浮窗。
注：无法在**全屏游戏**下显示悬浮窗，可切换至**窗口全屏**. ~~或将悬浮窗推流至局域网下其他设备~~


## 仙人掌 Cactbot


是一个提供基于OverlayPlugin悬浮窗插件的高级悬浮窗模板的插件。  
自带各种风格的DPS悬浮窗美化、副本时间轴、Boss技能提醒、钓鱼计时等功能。
**FF14客户端以`DX11`启动方可使用此插件功能，若无法以`DX11`启动，请查看帮助**
**除DPS统计美化外，仙人掌下的悬浮窗口必须锁定。**
若你无法确认仙人掌是否正常工作，请前往拉诺西亚的盛夏农庄，选中木人，输入`/行礼`便可获得测试结果。


### 仙人掌功能：

* DPS统计美化窗口
* 狩猎雷达（Cactbot Radar）：可监控并播报自身周围S A B狩猎怪的具体位置及相对方位
* 职业监控（Cactbot Jobs）：可监控自身职业量谱，重要buff，及长CD技能
* 副本时间轴（Cactbot Timeline）：提供参考用副本时间轴
* 副本触发提示（Cactbot Alerts）：提供参考用副本触发器
* 犯错监控（Cactbot OopsyRaidy）：监控自身及队友的犯错，如副本死亡，食物效果过期，吃到不应该的伤害等（注：不包括操作手法）
* 钓鱼计时器（Cactbot Fisher）：提供渔场数据，钓鱼计时等功能
* 优雷卡监控（Cactbot Eureka）：可监控并提供**当前**优雷卡岛内NM刷新&天气，和**当前**博兹雅岛内SM、CE刷新&天气


##  DPS统计美化窗口

将伤害统计以直观的方式展现，可选择个人所喜欢的风格。除了少数的简约美化悬浮窗，大多在右上或者右下都带有设置，方便玩家进行个性化选择。

1. 伤害统计标签。
2. 悬浮窗口路径，可输入浏览选择本地html文件或者美化窗口网络地址。此步骤为二选一。
3. 每次更换新的美化窗口地址后，请重新加载以应用新的美化。
4. 部分伤害美化需要WS支持，如果出现美化窗口空白或无统计的情况，请选中ACTWS标签。
5. 勾上WS支持。

![](https://i.imgur.com/LKmsB5q.png)
![](https://i.imgur.com/Rq6J1Re.png)


### DPS统计美化窗口模版地址列表

以下为支持6.x的美化窗口，只需将连接地址复制进DPS悬浮窗路径栏即可。
展示图右上带WS图标表明该美化需ACTWS支持，使用时请勾选ACT兼容。
优先选择国服地址，若你的网络支持，可选择通用地址。
如美化窗口内出现网络无法连接的状况，则请更换其他的美化窗口地址。

---

#### Kagerou

![](https://i.imgur.com/zmnwihg.png)
![](https://i.imgur.com/Yy1BDM3.png)

国服适配地址：

```
https://act.diemoe.net/kagerou/overlay/
https://ffxiv.yorushika.moe/kagerou/overlay/
```

通用地址：

```
https://hibiyasleep.github.io/kagerou/overlay/
```

---

#### Canisminor

![](https://i.imgur.com/sreeMq8.png)

通用地址：

```
http://ffxiv.canisminor.cc/
```

---

#### Goldenchrysus

![](https://i.imgur.com/6sdVzQr.png)
![](https://i.imgur.com/WdnX7CB.png)

通用地址：

```
https://goldenchrysus.github.io/ffxiv/ember-overlay/
```

---

#### Mopi1

![](https://i.imgur.com/gV48rcb.png)
![](https://i.imgur.com/CRDEa9e.png)

国服适配地址：

```
https://ffxiv.yorushika.moe/mopimopi/
```

---

#### Mopi2

![](https://i.imgur.com/d9A76T9.png)

国服适配地址：

```
https://ffxiv.yorushika.moe/mopimopi2/
```

通用地址：

```
https://haeruhaeru.github.io/mopimopi/
```

---

#### Horizoverlay

![](https://i.imgur.com/cxWEf5h.png) 

国服适配地址：

```
https://ffxiv.yorushika.co/horizoverlay
```

通用地址：

```
https://bsides.github.io/horizoverlay
```

---

#### Ikegami 池上线
![](https://i.imgur.com/JEeq0PS.png)

国服适配地址：

```
https://act.diemoe.net/overlays/ikegami/
```

通用地址：

```
http://kagerou.hibiya.moe/ikegami-test/
```

---

#### Crumsy 简易模板 - 标准

![](https://i.imgur.com/WdkC71x.png)

```
通用地址：    http://xiv.crumsy.net/act/standard.html
```

---

#### Crumsy 简易模板 - 详细

![](https://i.imgur.com/NGpgwnr.png)

```
通用地址：    http://xiv.crumsy.net/act/detailed.html
```

---

#### Amethyst 紫水晶的幻想

![](https://i.imgur.com/QZrM65T.png)
![](https://i.imgur.com/FN6HYuz.png)

国服适配地址：

```
https://act.diemoe.net/overlays/amethyst/
```

通用地址：
```
https://amethyst.ffxiv.io/
```

---

#### enmity 仇恨距离 - 本地美化

![](https://i.imgur.com/bl9111F.png)
![](https://i.imgur.com/RmqZEtH.png)
![](https://i.imgur.com/mzgQ1Rq.png)

```
路径为ACT安装文件夹Plugins\OverlayPlugin\resources\enmity下三个文件,
可选择自己喜欢的一个，分别是:
enmity_relative.html
enmity_absolute.html
aggrolist.html
```

