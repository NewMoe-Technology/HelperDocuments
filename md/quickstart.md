# ACT —— 从入门到~~精通~~放弃

> #### 关于ACT
ACT只是一个提供各种插件执行的平台，它的功能不限定于伤害统计、时间轴、技能提醒监控等。
大多插件以DLL形式提供下载，而呆萌整合包已经将常用的插件打包整合，不需要你再做另外的设置，简单易用且方便。
以下列表是目前提供的常用插件说明，更多便捷功能将会在日后逐步增加。


| 原插件名 | 中文名 | 插件说明 |
| :-----| :----- | :----- |
| FFXIV\_ACT\_Plugin.dll | FFXIV解析插件 | FF14的ACT核心，所有插件基于其才能运行。FFXIV Overlay是其自带的血条监视插件。 |
| ACT.OverlayPlugin.dll | 悬浮窗插件 | 伤害统计、时间轴美化等悬浮窗的依赖插件，请保持这个插件在第一加载顺位。 |
| ACT.TriggerNometry.dll | 高级触发器 | 触发器插件,可以监控技能冷却、boss技能提醒等功能。 |
| ACT.FoxTTS.dll | TTS语音插件 | 中文语音播报插件 |
| CactbotOverlay.dll | 仙人掌插件(暂名凯科特爆特) | 伤害统计美化、时间轴、副本监控狩猎监控等功能性插件。插件说明请点击：-> [NGA](https://bbs.nga.cn/read.php?tid=18986135)|
| ACT.多国语言.dll | 语言切换 | 呆萌ACT汉化语言包 |
| ACT.FishersInstinct.cs | 渔人的直感 | 钓鱼提醒，单独功能下载 -> [NGA](http://bbs.nga.cn/read.php?tid=19562122)|


## FFXIV解析插件
<font color= red>此为ACT的核心插件，请不要擅自删除或移动该DLL文件。</font>
* 正常情况下，玩家只需要做解析范围的相关设置。电脑比较好的玩家可以选择团队范围，稍差的则可以选择小队或者只监控自己。
* 在你能正确解析DPS数据的情况下，默认请选择网络模式。若你使用加速器或无法正常使用网络解析，请选择安装[WinCap](https://)并使用该解析模式。而内存模式在任何情况下都不是你的选择，请将它无视。
* 如果网络和wincap两种模式下，都无法解析你的数据，请查阅该帮助。
![](https://i.imgur.com/PeoHsBC.png)


## FFXIV Overlay

解析插件自带的目标血条监控，默认为隐藏。
可自定义血条大小、颜色和字体。如不小心打开可以在图中所示的两个红框点击关闭。
不需要此功能的情况下推荐勾上分标签所有Hide Overlay的复选框，以避免误触开关。

![](https://i.imgur.com/n1NMX8l.png)


## 高级触发器 Triggernometry

ACT真正最具争议的插件，只是黑锅甩给了TTS。用它导入作者为各副本定制的轮椅，你就无须再站起来了。
导入网上发布的后缀为.xml的触发器脚本，勾上复选框便可以启用相应功能。*在导入xml文件之前，请先确认是否为触发器脚本，无关的xml文件会导致报错。
当你不使用某些触发提示时，请将其相应提示禁用。

![](https://i.imgur.com/csGycPG.png)


## 语音插件 FoxTTS

它，只是一个文字转语音播报插件，但是被背上了所有的骂名……ACT插件的黑锅王。
默认百度引擎播报，自带音量调节，人声选择里你可以挑选自己喜欢的语音。

![](https://i.imgur.com/yqCGelL.png)


## 仙人掌 Cactbot

自带各种风格的DPS悬浮窗美化、副本时间轴、Boss技能提醒、钓鱼计时等功能。
FF14客户端以DX11启动方可使用此插件功能，若无法以DX11启动，请查看帮助
*除DPS统计美化外，仙人掌下的悬浮窗口必须锁定。
若你无法确认仙人掌是否正常工作，请前往拉诺西亚的盛夏农庄，对木人输入/行礼便可获得测试结果。


### 仙人掌功能：

* DPS统计美化窗口
* 狩猎雷达
* Buff监控
* 副本时间轴
* 副本触发提示
* 死亡监控
* 钓鱼计时器
* 尤雷卡NM监控(丰水之地因SE开发原因，无法正常使用)


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

以下为支持5.0的美化窗口，只需将连接地址复制进DPS悬浮窗路径栏即可。
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

