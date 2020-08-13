# Sans 模拟器 - Bad Time Simulator (Sans Fight)

该仓库clone自原作者 [Jcw87/c2-sans-fight](https://github.com/Jcw87/c2-sans-fight) ，并稍微做了一些魔改。

对战桥段取自于 知名独立游戏 [Undertale（传说之下）](http://undertale.com/) 中，

屠杀结局（共中立、和平、屠杀三个结局）的最终BOSS战，

此游戏为该情节的 Web端移植版。

## 玩法

主要玩法为 控制 ❤Heart 方向，躲避 Sans 的弹幕式攻击

PC 端使用 上下左右方向键 控制 ❤Heart 移动，`Z` / ` Enter` - 确定， `X` - 返回

移动端滑动屏幕进行移动，但是操作较为困难。

建议下载 "游戏键盘" APP，自定义摇杆映射后进行游玩。



## 二次开发

游戏采用 [Construct 2](https://www.scirra.com/construct2) html5游戏开发引擎进行开发，

并且需要付费（个人版 99刀/年）才能编译输出html文件。

我已经编译好了 html 文件放在仓库里，

文件在 `./Build` 目录，需要请自取。



# 以下是原仓库README.md
------------

# Bad Time Simulator (Sans Fight)
This project is a clone of the sans fight from [Undertale](http://undertale.com/).
It was made with [Construct 2](https://www.scirra.com/construct2).

NOW AVAILABLE! [Custom attacks guide](Documentation/README.MD)
-----------------------------------------------------

Known Issues
------------
- Heart hitbox is probably not accurate.
- On the sans_platforms4 and sans_platforms4hard attacks, the platform is supposed to accelerate from 0 to its full speed, but I was lazy and started it at full speed immediately. This is only a problem if you try to dodge the bones without jumping.
- Sans dialog is missing. I may add something at some future date, but I have no intention of putting the original text in, as it really only makes sense in the context of the whole game.

Contact
-------
If you want to contact me for some reason, you can do so through the following:

- ~~[Facepunch](https://facepunch.com/member.php?u=13155)~~ R.I.P. Facepunch
- [Steam](http://steamcommunity.com/id/Jcw87/)
