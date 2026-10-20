[中文说明](#chinese) · [English](#english)

<a id="top"></a>

# KingdomTrainer · 王国：两位君主辅助工具

![Version](https://img.shields.io/badge/version-3.0.0_R49-blue.svg)
![Game](https://img.shields.io/badge/game-2.4.3-yellow.svg)
![Platform](https://img.shields.io/badge/platform-Windows_x64-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

《王国：两位君主》免费独立辅助工具，提供全岛地图、像素 HUD 与按需开启的辅助功能。软件界面为简体中文。

A free standalone Windows trainer with an island map, pixel HUD and optional gameplay assists. The application interface is in Simplified Chinese; this page provides both Chinese and English instructions.

本仓库发布编译后的玩家包与版本信息，不提供源代码。 / This repository distributes compiled player packages and release information; source code is not included.

<a id="chinese"></a>

## 中文说明

[下载](#zh-download) · [运行与安装](#zh-install) · [全岛地图](#zh-map) · [时钟与 HUD](#zh-hud) · [钱袋与国库](#zh-economy) · [开发者工坊](#zh-workshop) · [反馈问题](#zh-feedback) · [快捷键](#zh-hotkeys) · [版本与许可](#zh-version)

[B 站功能演示](https://www.bilibili.com/video/BV1mKn368E4j/) · [小黑盒图文介绍](https://www.xiaoheihe.cn/app/bbs/link/194432311) · [Nexus Mods](https://www.nexusmods.com/kingdomtwocrowns/mods/39)

**玩家包：3.0.0 R49 · 适配游戏：2.4.3 · Windows 64 位**

> **开发者工坊请使用新测试档。** 有些操作会永久改变存档，关闭功能也不一定能恢复，请先备份珍贵进度。

<a id="zh-download"></a>

### 下载

- **[下载 3.0.0 R49 · 游戏 2.4.3 · 无密码 ZIP](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)**
- [R49 发行说明](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/tag/v3.0.0-R49) · [后续最新版](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/latest)
- [GitHub 下载备用入口](https://ghfast.top/https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)
- [蓝奏盘](https://wwazv.lanzout.com/b00v0e9l7e)（密码 `88xj`）
- [123 网盘](https://1822423586.share.123pan.cn/123pan/cDuJjv-nZ9jd?pwd=1k79)（提取码 `1k79`）
- [历史版本](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases) · [2.6.3 最终玩家包](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v2.6.3/KingdomTrainer_v2.6.3_GitHub_20261014.zip)

<details>
<summary>历史网盘入口与密码</summary>

[百度网盘](https://pan.baidu.com/s/1n6NLje4odhFh29FuWvUnqg?pwd=1976)（提取码 `1976`）；[旧蓝奏链接](https://wwazv.lanzout.com/iVt8f4ayo23i)（访问密码 `ew9t`，旧包解压密码 `kingdom`）。这些是历史入口，版本以实际文件名为准。R49 的 GitHub ZIP 无解压密码。

</details>

<a id="zh-install"></a>

### 运行与安装

1. 使用 Windows 10/11 64 位及游戏 **2.4.3（Windows IL2CPP）**，无需另装 Python。
2. 关闭旧修改器，将 ZIP 中的全部文件完整解压到同一个文件夹。
3. 保留 `KingdomTrainer.exe` 同目录的 `trainer_core.dll`、`update_config.json` 和其他配套文件。
4. 运行主程序并启动游戏，启动顺序不限。等待显示已连接，再选择需要的 HUD 和辅助功能。

使用**独立模式**即可，不需要安装 BepInEx。曾尝试开发的插件模式已废弃。

本页以单人独立模式为主。分屏 HUD 的适配不代表所有辅助功能都支持联机；联机效果受主机权限与同步机制影响，国库互通限单人使用。

玩家包不含个人设置、存档记录或日志。同一台电脑已有的软件设置会继续保留。

### 软件界面

功能分成通用辅助、战役、挑战岛、开发者工坊四页。顶部会识别战役、岛屿和君主状态，切换主题战役时，对应的称呼也会跟着变。

![新界面与HUD设置](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326296-719180115.png)

*新界面与HUD设置*

<a id="zh-map"></a>

### 全岛地图

全岛地图放在游戏画面下方，难民营、坐骑、隐士、商铺和建筑都能在上面找到。跑图时可以先确认目的地，再放大看具体位置。

![全岛地图·像素全景](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326278-1268277346.png)

*全岛地图·像素全景*

地图能显示建筑等级，以及左右最前沿城墙的剩余耐久。这两项都有独立开关，嫌信息多可以关掉。

### 地图样式

地图有像素全景、文字地图和定位图谱等样式，选自己看着顺眼的就行。三张图分别是这三种样式的局部。

![地图特写·像素全景](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483827-419936880.png)

*地图特写·像素全景*

![地图特写·文字地图](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483828-1501667125.png)

*地图特写·文字地图*

![地图特写·定位图谱](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483831-1964455493.png)

*地图特写·定位图谱*

五套图标画风和三种文字排布分开设置，可以自由搭配。

地点太多时，可以按分类筛选。比如只想找坐骑，就把其他分类关掉，地图上只留下坐骑的位置。地图背景也有独立开关；实景缩略样式会记录已经过的区域。

### 缩放与传送

地图支持全岛视图和最高八倍放大。放大后默认跟随君主，用逗号、句号可以左右浏览，停下几秒后自动恢复跟随。

双击单个图标可以直接传送。几个地点挤在一起时会合并成一组，单击组合文字展开列表，再点里面的名字，就能传到对应地点。

![组合地点展开列表](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326290-1160719387.png)

*组合地点展开列表*

防剧透开关会让地图只显示探索过的区域，探索进度按存档和岛屿分别记录。打开“静止收起”后，停下八秒，地图会缩成一条细线，跑起来再展开。

### 怪物标记

开启怪物位置后，普通怪显示为红色，Boss显示为金色，扎堆的怪群会标出数量。怪物标记可以单独关闭。

![怪物位置与血条](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326288-1250319795.png)

*怪物位置与血条*

地图底部显示全岛可招募的难民人数，以及弓、锤子、农具和面包库存。招人、买工具时看一眼，省得来回跑商铺确认。

<a id="zh-hud"></a>

### 时钟与HUD

右上角显示游戏天数、当天时间、换季倒计时和血月提醒。准备过冬或者出征时，可以先看看剩余时间。

![时钟与换季倒计时](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326297-229080918.png)

*时钟与换季倒计时*

HUD能显示血条、坐骑耐力、人口统计和Boss雷达。不同职业用不同颜色区分，瘟疫岛变异后的弓手、骑士按敌方显示，城墙被攻破时也有提示。建筑和传送门耐久、国库金币也可以查看，扎堆显示会合并整理，F12 可打开快捷键看板。

HUD各项信息可以单独开关。打开游戏暂停菜单时会自动隐藏，避免挡住按钮。

### HUD刷新率

HUD刷新率上限可以自己选。动态刷新会把静止信息的刷新率降到1Hz，减少持续刷新的开销。游戏后期单位太多造成的卡顿，也会受游戏本身和电脑性能影响。

游戏内可以显示像素鼠标。想一边看游戏一边操作软件，可以置顶窗口；关于页里能把软件透明度调到35%至100%。

<a id="zh-economy"></a>

### 钱袋与国库

钱袋可以选“容量无限”。金币照常赚、消费照常扣，装满也不会掉出来，余额用数字显示。想正常打钱经营，又不想被钱袋容量限制，可以选这个模式。另有免费消费等金钱辅助；相关金钱模式互斥，按界面选择所需模式。

![钱袋与国库辅助](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326301-655236558.png)

*钱袋与国库辅助*

单人模式下，本岛有税官和国库就能开启国库互通。君主消费时，可以接着用居民手上的余币，直接扣居民身上的钱，不用挨个跑过去收。钱袋少于十枚时会从国库补充，拾取装不下的金币会自动回存。

![国库互通·金币流向](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483832-579348503.png)

*国库互通·金币流向*

### 远程招募与购买

远程招募可以选具体营地或居民屋，远程购买可以买弓、锤子、农具和面包。招募与购买按对应地点、库存和所选消费模式执行。

觉得难民来得慢，可以调难民生成加速。弓箭手不排队会缩小墙后弓手的站位间距，让防守火力更集中。

缺一点资源时，可以用快捷键单次领取五枚金币或一颗宝石。这类一次性操作不会在恢复配置时反复触发。

### 免伤与防抢

君主、子民和出征部队有免伤选项，也有坐骑无限体力、城墙保护，可以分别开关。

小狗、狼岛的狼崽、隐士都有独立防抢开关，打开后不会被怪抓走，君主接送隐士不受影响。

坐骑特技免冷却会联动无限体力，骷髅岛沙漏可以锁住剩余天数。战役和挑战岛相关的选项放在对应页面里。

君主和友方单位的移速可以分开调，范围是0.5至20倍，有九档快捷键预设。

<a id="zh-workshop"></a>

### 开发者工坊

开发者工坊可以用来观察游戏机制、控制镜头、调整环境和测试玩法。建议用新开的测试档试，部分操作会直接改变世界和存档。

![开发者工坊·时间与变速](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326302-182634688.png)

*开发者工坊·时间与变速*

### 时间与镜头

游戏可以暂停、快进或慢放。暂停昼夜只会停住昼夜交替，人物还能正常活动。

镜头可以拉远，也能切成自由镜头单独移动。看完远处后一键切回君主，或者把君主传送到镜头位置。

### 照明与地标传送

照明与规则页有森林照明、驱散云雾、投币高亮，也能停止怪物刷新、开启自动撒币。

地标瞬移整理了营地、科技、隐士屋、左右前线等位置。同类地点有多个时可以轮流切换，人物卡住也能一键回到主基地。

### 时代与环境

木器、石器、铁器时代可以直接切换，也能一键点亮全部神像。

环境页可以跳过一小时或一天、清树、融雪，让帆船全员就位，或者手动触发血月和永夜。跳过天数会实际推进游戏事件和刷怪进程。

传送门和山洞魔窟有对应的操作，包括摧毁传送门，以及瞬移到山洞口生成炸弹。停止后续刷怪需要配合“停止刷新”功能。

### 建造与离岛衰败

建造可以选快速建造，或是不需要工匠跑腿的自动建造。左右弓手可以平均分配，空闲工匠也能重新分工。

![建造与防线人员分配](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326307-1668199279.png)

*建造与防线人员分配*

离岛衰败可以关闭，也能增减衰败天数并执行模拟。模拟结果会实际应用到存档。

### 存档提醒

工坊里有些功能会永久改变存档，关闭后也不一定能恢复。强烈建议新开测试档体验，不要直接拿珍贵的旧档尝试，重要进度先备份。

### 配置保存与切档

右上角“记忆”可以保存常用开关，支持全局共用一套，或按不同存档分别记。招募、购买这类一次性操作不会被反复触发。

切档时默认先关闭修改功能，避免把上一个存档的配置直接带过去；弹窗里可以恢复配置。按钮会读取游戏内状态，条件没满足时显示等待。

<a id="zh-feedback"></a>

### 故障排查与反馈

功能没反应，可以先看“关于”里的故障排查，检查连接情况和版本是否匹配，也能复制诊断报告。

[GitHub Issues](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/issues)（需要 GitHub 账号）也可用于反馈。网页入口不需要 GitHub 账号。

提交问题或建议时，先选类型和具体分类，再写清楚哪张地图、做了什么、出现什么问题。最多可以加四张截图，设备编号、运行日志和兼容性报告按需勾选。

![反馈教程·入口与分类](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483836-1117929241.png)

*反馈教程·入口与分类*

![反馈教程·描述与附件](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483837-769799249.png)

*反馈教程·描述与附件*

点下一步后，会同时打开反馈网页和反馈包文件夹，标题、描述自动填好。找到文件夹里的ZIP，拖进网页上传区。

![反馈教程·上传与提交](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483841-2011313950.png)

*反馈教程·上传与提交*

等压缩包上传完成，再点网页上的提交，看到完成提示就好了。网页不需要注册GitHub账号；想收到回复可以留邮箱，站内联系排查时也可以附上匿名设备编号。网络不通时，可以先保存离线包。

<a id="zh-hotkeys"></a>

### 主要快捷键（独立模式）

| 按键 | 功能 |
| --- | --- |
| `F1 / F2` | 君主保护 / 无限体力 |
| `F3 / F4` | 免费消费 / 子民与出征部队免伤 |
| `F5 / Shift+F5` | 营地招募 / 居民屋招募 |
| `Ctrl+F5` | 难民生成加速 |
| `F6 / Shift+F6 / Alt+F6` | 买弓 / 买锤 / 买农具 |
| `Ctrl+Shift+F6 / Ctrl+F6` | 买面包 / 弓箭手不排队 |
| `F7 / F8` | 城墙保护 / 快速建造与砍树 |
| `Ctrl+F7 / Ctrl+F8` | 加 5 枚金币 / 加 1 颗宝石 |
| `F9` | 暂停或恢复昼夜交替 |
| `F10 / Ctrl+F10` | 国库互通 / 钱袋容量无限 |
| `F11 / F12` | HUD / 快捷键看板 |
| `Alt+1～9 / Ctrl+1～9` | 君主 / NPC 移动速度预设 |
| `+ / -` | 地图放大 / 缩小 |
| `, / .` | 放大地图时左右浏览 |
| `Alt+F9` | 智能自检与故障排查 |


实际快捷键与可用条件请以软件界面为准。

<a id="zh-version"></a>

### 版本信息与许可

#### R49 更新说明

- 切档保护弹窗支持滚动和调整大小，底部操作按钮固定显示。
- 简化弹窗文字，“关闭此功能”与右上角“记忆”页开关联动。
- 旧版“不再提醒”设置不会跳过首次 3.0 引导；确认后按所选设置执行。
- 调整首次引导的文字排版与窗口适配。

R49 保留 R48 的游戏功能，主要调整引导与弹窗。游戏后续更新后，请检查辅助工具是否已适配。

关于页可以检查软件更新。

- [version.json](https://raw.githubusercontent.com/Moolmool114/KingdomTwoCrowns-Trainer/main/version.json)
- [jsDelivr 备用入口](https://cdn.jsdelivr.net/gh/Moolmool114/KingdomTwoCrowns-Trainer@main/version.json)

R49 ZIP SHA-256: `40afe2e5755387f48a09b27e98b86de4c57b4d07c385ce13fed614a120189c24`.

许可条款见 [LICENSE](LICENSE)。

[返回顶部 / Back to top](#top) · [中文说明](#chinese) · [English](#english)

<a id="english"></a>

## English

[Download](#en-download) · [Installation](#en-install) · [Island map](#en-map) · [Clock and HUD](#en-hud) · [Purse and treasury](#en-economy) · [Developer Workshop](#en-workshop) · [Bug reports](#en-feedback) · [Hotkeys](#en-hotkeys) · [Version and licence](#en-version)

[Feature video — Chinese narration and subtitles](https://www.bilibili.com/video/BV1mKn368E4j/) · [Heybox illustrated article — Chinese](https://www.xiaoheihe.cn/app/bbs/link/194432311) · [Nexus Mods](https://www.nexusmods.com/kingdomtwocrowns/mods/39)

**Player build: 3.0.0 R49 · Target game: 2.4.3 · Windows x64**

> **Try the Developer Workshop in a separate test save.** Some actions permanently change a save, and disabling a feature may not undo them. Back up valuable progress first.

<a id="en-download"></a>

### Download

- **[Download 3.0.0 R49 · game 2.4.3 · ZIP without a password](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)**
- [R49 release notes](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/tag/v3.0.0-R49) · [Latest release](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/latest)
- [Alternative GitHub download route](https://ghfast.top/https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)
- [Lanzou](https://wwazv.lanzout.com/b00v0e9l7e) — access password: `88xj`
- [123 cloud storage](https://1822423586.share.123pan.cn/123pan/cDuJjv-nZ9jd?pwd=1k79) — access code: `1k79`
- [Release history](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases) · [Final 2.6.3 player package](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v2.6.3/KingdomTrainer_v2.6.3_GitHub_20261014.zip)

<details>
<summary>Historical cloud links and passwords</summary>

[Baidu Netdisk](https://pan.baidu.com/s/1n6NLje4odhFh29FuWvUnqg?pwd=1976) — access code `1976`; [older Lanzou link](https://wwazv.lanzout.com/iVt8f4ayo23i) — access password `ew9t`, old ZIP password `kingdom`. These are historical links; check the actual filename for its version. The R49 ZIP on GitHub has no archive password.

</details>

<a id="en-install"></a>

### Requirements and installation

1. Use Windows 10/11 x64 and **Kingdom Two Crowns 2.4.3 (Windows IL2CPP)**. No separate Python installation is needed.
2. Close the old trainer and extract **all** ZIP contents into one folder.
3. Keep `trainer_core.dll`, `update_config.json` and all other accompanying files beside `KingdomTrainer.exe`.
4. Start the trainer and the game in either order. Wait for the connected status, then choose the HUD displays and assists you want.

Use **standalone mode**; it does not require BepInEx. An experimental plugin mode was attempted and has been discontinued.

This guide focuses on single-player standalone use. Split-screen HUD support does not mean every assist works in multiplayer. Multiplayer effects depend on host authority and synchronisation; treasury sharing is single-player only.

The distributed package excludes personal settings, save records and logs. Existing trainer settings on the same computer are retained.

### Interface

Features are organised into four pages: General Assists, Campaigns, Challenge Islands and the Developer Workshop. The top bar identifies the campaign, island and monarch status. Labels adapt to the selected campaign theme.

![3.0 Trainer interface and HUD options](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326296-719180115.png)

*3.0 Trainer interface and HUD options*

<a id="en-map"></a>

### Island map

The island map sits along the bottom of the game screen. It marks vagrant camps, mounts, hermits, shops and buildings, so you can find a destination before zooming in for a closer look.

![3.0 Island map - Pixel panorama](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326278-1268277346.png)

*3.0 Island map - Pixel panorama*

Building levels and the remaining durability of the outermost wall on each side can be displayed. Both have separate switches if you prefer a less crowded map.

### Map styles

Three representative map styles are Pixel Panorama, Text Map and Location Atlas. They present the same island information in different layouts.

![Map close-up - Pixel panorama](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483827-419936880.png)

*Map close-up - Pixel panorama*

![Map close-up - Text map](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483828-1501667125.png)

*Map close-up - Text map*

![Map close-up - Location atlas](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483831-1964455493.png)

*Map close-up - Location atlas*

Five icon styles and three text layouts are configured separately, so you can mix them to suit your preference.

Category filters let you hide locations you are not looking for. To find a mount, for example, leave only the mount category enabled. The map background has its own switch. The scenery-thumbnail style records areas you have travelled through.

### Zoom and teleport

The map ranges from a whole-island view to 8× zoom. Zoomed views follow the monarch by default. Use the comma and period keys to browse left or right; automatic following resumes after a few seconds without panning.

Double-click an individual icon to teleport there. Nearby locations are grouped together: click the group label once to open a list, then select a location name to teleport to it.

![3.0 Grouped location list](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326290-1160719387.png)

*3.0 Grouped location list*

Spoiler protection limits the map to explored areas, with exploration recorded separately for each save and island. With idle collapse enabled, standing still for eight seconds reduces the map to a thin line; moving expands it again.

### Enemy markers

Enemy markers show regular enemies in red and Bosses in gold. Clustered groups show their numbers. Enemy markers have their own switch.

![3.0 Enemy markers and health bars](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326288-1250319795.png)

*3.0 Enemy markers and health bars*

The bottom of the map lists recruitable vagrants across the island and available bows, hammers, farming tools and bread. You can check these without travelling between shops.

<a id="en-hud"></a>

### Clock and HUD

The clock in the upper-right corner shows the day, time, days until the next season and Blood Moon reminders. It helps with planning a winter or an expedition.

![3.0 Clock and season countdown](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326297-229080918.png)

*3.0 Clock and season countdown*

The HUD can show health bars, mount stamina, population counts and an off-screen Boss radar with direction and distance. Professions have distinct colours; mutated archers and knights on Plague Island are treated as enemies. Wall breaches also trigger alerts. Building and portal durability and treasury gold can also be displayed. Crowded displays can be grouped, and F12 toggles the hotkey panel.

Each HUD category can be switched on or off. The overlay hides automatically when the game pause menu is open so it does not cover menu buttons.

### HUD refresh rate

Choose a maximum HUD refresh rate. Dynamic refresh reduces static information to 1 Hz to lower continuous refresh overhead. Crowded late-game scenes can still be limited by the game itself and your hardware.

An in-game pixel cursor is available. Pin the trainer window if you want to operate it over the game, and adjust its opacity from 35% to 100% on the About page.

<a id="en-economy"></a>

### Purse and treasury

Unlimited purse capacity keeps normal earning and spending: coins are still deducted when you buy something, but a full purse no longer spills coins. The balance is displayed as a number. Free spending and other money assists are also available. Incompatible money modes are mutually exclusive; select the mode you want in the interface.

![3.0 Purse and treasury assists](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326301-655236558.png)

*3.0 Purse and treasury assists*

In single-player, treasury sharing becomes available once the island has a banker and treasury. When the monarch spends, spare coins still held by citizens can be used directly, without visiting each citizen to collect them. These coins are not first transferred into the treasury. A purse below ten coins is topped up from the treasury, and collected coins that exceed purse capacity are stored back.

![Treasury sharing - Coin flow](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483832-579348503.png)

*Treasury sharing - Coin flow*

### Remote recruitment and purchases

Remote recruitment lets you select a camp or citizen house. Remote purchasing covers bows, hammers, farming tools and bread. Actions depend on the selected location, stock and spending mode.

Vagrant generation can be accelerated. The archer-spacing option brings archers closer together behind the walls to concentrate defensive fire.

Hotkeys can grant five coins or one gem at a time. One-off actions are not repeated when a saved configuration is restored.

### Protection and movement

Damage protection is available for the monarch, citizens and expedition troops. Mount stamina and wall protection also have separate switches.

The dog, the pups on Dire Island and hermits have independent protection against being carried away. Carrying and dropping off a hermit with the monarch still works normally.

Removing mount-ability cooldowns also enables unlimited stamina. The Skull Island hourglass can have its remaining days locked. Campaign and challenge-specific controls are grouped on their respective pages.

Monarch speed and friendly-unit speed can be adjusted independently from 0.5× to 20×, with nine hotkey presets.

<a id="en-workshop"></a>

### Developer Workshop

The Developer Workshop offers tools for observing game systems, controlling the camera, changing the environment and trying different setups. Use a separate test save: some actions directly alter the world and its save data.

![3.0 Workshop - Time and speed](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326302-182634688.png)

*3.0 Workshop - Time and speed*

### Time and camera

Pause the game, speed it up or use slow motion. Pausing the day/night cycle only stops the passage of day and night; characters can still move.

Zoom the camera out or move it independently in free-camera mode. Afterwards, return the camera to the monarch in one action, or teleport the monarch to the camera location.

### Lighting and landmark teleport

The Lighting and Rules page includes forest lighting, cloud and fog removal, and highlighting for coin interactions. It also offers enemy-spawn suppression and automatic coin dropping.

Landmark teleport groups camps, technology locations, hermit homes and the two front lines. Cycle through multiple locations of the same type, or return to the main base if the monarch is stuck.

### Era and environment

Switch directly between the wood, stone and iron eras, or activate all statues in one action.

The Environment page can advance one hour or a full day, clear trees, melt snow, ready everyone aboard the boat, or trigger a Blood Moon or endless night. Advancing days also advances game events and enemy spawning.

Portal and cliff-cave actions include destroying portals or teleporting to a cave entrance and spawning a bomb. Use enemy-spawn suppression separately if you want to prevent subsequent spawning.

### Construction and island decay

Choose fast construction or automatic construction without waiting for builders to travel. Archers can be split evenly between the two sides, and idle builders can be reassigned.

![Construction and defence tools](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792326307-1668199279.png)

*Construction and defence tools*

Island decay can be disabled. You can also add or subtract decay days and run a simulation. The simulation result is actually applied to the save.

### Save warning

Some Workshop actions permanently alter your save, and switching a feature off may not undo its effects. Strongly recommended: try these tools in a new test save, keep backups, and do not experiment on a valued campaign.

### Configuration memory and save switching

The Memory control in the upper-right corner saves commonly used settings globally or separately for each save. One-off recruitment and purchasing actions are not repeatedly triggered.

When you switch saves, modifying features are disabled by default to prevent settings carrying over accidentally. The dialog offers to restore the previous configuration. Controls read the actual game state and show a waiting state when their conditions are not met.

<a id="en-feedback"></a>

### Troubleshooting and feedback

If a feature does not respond, open Troubleshooting under About to check the connection and game-version match. You can also copy a diagnostic report.

You can also report issues through [GitHub Issues](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/issues), which requires a GitHub account. The in-app web feedback route does not.

For a bug report or suggestion, select a type and specific category, then explain the map, what you did and what went wrong. Attach up to four screenshots. Device ID, runtime logs and compatibility reports can be included as needed.

![Bug report guide 1 - Entry and category](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483836-1117929241.png)

*Bug report guide 1 - Entry and category*

![Bug report guide 2 - Description and attachments](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483837-769799249.png)

*Bug report guide 2 - Description and attachments*

The next step opens both a prefilled feedback web form and the feedback-package folder. Find the generated ZIP in that folder and drag it into the form’s upload area.

![Bug report guide 3 - Upload ZIP and submit](https://staticdelivery.nexusmods.com/mods/2695/images/39/39-1792483841-2011313950.png)

*Bug report guide 3 - Upload ZIP and submit*

Wait for the ZIP upload to finish, then submit the web form and look for the completion message. No GitHub account is required. Leave a reply email if you want a response; when contacting the author on Bilibili, include the anonymous device ID to help locate the report. An offline package can be saved if the network is unavailable.

<a id="en-hotkeys"></a>

### Main hotkeys — standalone mode

| Key | Action |
| --- | --- |
| `F1 / F2` | Monarch protection / unlimited mount stamina |
| `F3 / F4` | Free spending / citizen and expedition damage protection |
| `F5 / Shift+F5` | Recruit from a camp / citizen house |
| `Ctrl+F5` | Accelerated vagrant generation |
| `F6 / Shift+F6 / Alt+F6` | Buy a bow / hammer / farming tool |
| `Ctrl+Shift+F6 / Ctrl+F6` | Buy bread / closer archer spacing |
| `F7 / F8` | Wall protection / fast construction and tree chopping |
| `Ctrl+F7 / Ctrl+F8` | Grant five coins / one gem |
| `F9` | Pause or resume the day/night cycle |
| `F10 / Ctrl+F10` | Treasury sharing / unlimited purse capacity |
| `F11 / F12` | HUD / hotkey panel |
| `Alt+1～9 / Ctrl+1～9` | Monarch / NPC movement-speed presets |
| `+ / -` | Zoom the map in / out |
| `, / .` | Pan a zoomed map left / right |
| `Alt+F9` | Self-check and troubleshooting |


Check the trainer interface for the active hotkey mappings and feature requirements.

<a id="en-version"></a>

### Version information and licence

#### R49 notes

- The save-switch protection dialog supports scrolling and resizing, with fixed action buttons at the bottom.
- Dialog text is shorter; “disable this feature” is linked to the switch in the Memory page.
- Older “do not remind me again” settings do not bypass the first 3.0 introduction. Confirming it applies the selected settings.
- First-run text layout and window sizing have been adjusted.

R49 retains the R48 game features and mainly revises onboarding and dialogs. A later game update may require a newer trainer build.

The About page includes an update check.

- [version.json](https://raw.githubusercontent.com/Moolmool114/KingdomTwoCrowns-Trainer/main/version.json)
- [jsDelivr mirror](https://cdn.jsdelivr.net/gh/Moolmool114/KingdomTwoCrowns-Trainer@main/version.json)

R49 ZIP SHA-256: `40afe2e5755387f48a09b27e98b86de4c57b4d07c385ce13fed614a120189c24`.

See [LICENSE](LICENSE) for the supplied MIT licence.

[返回顶部 / Back to top](#top) · [中文说明](#chinese) · [English](#english)
