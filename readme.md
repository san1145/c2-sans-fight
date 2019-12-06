# Bad Time 模拟器 (Sans VS Chara 战)

该仓库clone自 [Jcw87/c2-sans-fight](https://github.com/Jcw87/c2-sans-fight) ，并稍微魔改了一下。

游戏取自知名独立游戏 [Undertale（传说之下）](http://undertale.com/) 中，

屠杀结局（游戏共有中立、和平、屠杀三个结局，强烈安利）的最终 BOSS战

## 玩法

主要玩法为 控制Heart的方向，躲避Sans弹幕式的攻击

PC 端使用十字键控制 Heart 移动，`Z` / ` Enter` - 确定， `X` - 返回

移动端滑动屏幕进行移动，但是操作困难。但可以下载 "游戏键盘" APP，自定义摇杆进行游玩。



## 二次开发

游戏采用 [Construct 2](https://www.scirra.com/construct2) html5游戏开发引擎进行开发，需要付费版（个人版 99刀/年）才能编译输出html文件

已编译好的文件位于 `./Build` 目录，有需要请自取



# 以下是原仓库README.md
------------

# Bad Time Simulator (Sans Fight)
This project is a clone of the sans fight from [Undertale](http://undertale.com/).
It was made with [Construct 2](https://www.scirra.com/construct2).

Known Issues
------------
- Heart hitbox is probably not accurate.
- On the sans_platforms4 and sans_platforms4hard attacks, the platform is supposed to accelerate from 0 to its full speed, but I was lazy and started it at full speed immediately. This is only a problem if you try to dodge the bones without jumping.
- Sans dialog is missing. I may add something at some future date, but I have no intention of putting the original text in, as it really only makes sense in the context of the whole game.
- Missing documentation for custom attacks. I intend to add this at some point, but for now, you can reference the *.csv files in the repository. I may change how this works later, so don't be surprised if your custom attack breaks.

Contact
-------
If you want to contact me for some reason, you can do so through the following:

- [Facepunch](https://facepunch.com/member.php?u=13155)
- [Steam](http://steamcommunity.com/id/Jcw87/)
