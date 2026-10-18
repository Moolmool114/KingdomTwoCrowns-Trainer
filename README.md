# KingdomTrainer · 王国：两位君主辅助工具

![Version](https://img.shields.io/badge/version-3.0.0_R49-blue.svg)
![Game](https://img.shields.io/badge/game-2.4.3-yellow.svg)
![Platform](https://img.shields.io/badge/platform-Windows_x64-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

为《王国：两位君主》提供像素 HUD、岛屿小地图与可选辅助功能。界面为简体中文，免费提供。

A free Windows trainer for Kingdom Two Crowns with a pixel HUD, island minimap and optional gameplay assists. The interface is in Simplified Chinese. This repository distributes compiled player packages and release information; source code is not included.

## 下载

- **[下载 3.0.0 R49 · 游戏 2.4.3 · 无密码 ZIP](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)**
- [R49 更新说明](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/tag/v3.0.0-R49)
- [GitHub 下载备用入口](https://ghfast.top/https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v3.0.0-R49/KingdomTrainer_v3.0.0_R49_Game2.4.3_20261018.zip)
- [历史版本](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases) · [2.6.3 最终玩家包](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v2.6.3/KingdomTrainer_v2.6.3_GitHub_20261014.zip)

历史网盘入口：[百度网盘](https://pan.baidu.com/s/1n6NLje4odhFh29FuWvUnqg?pwd=1976)（提取码 `1976`）；[蓝奏盘](https://wwazv.lanzout.com/iVt8f4ayo23i)（访问密码 `ew9t`，旧包解压密码 `kingdom`）。网盘中的文件版本以实际文件名为准，R49 的 GitHub 玩家包无解压密码。

## R49 更新

- 切档保护弹窗支持滚动和调整大小，底部操作按钮固定显示。
- 简化弹窗文字，“关闭此功能”与右上角“记忆”页开关联动。
- 旧版“不再提醒”设置不会跳过首次 3.0 引导；确认后按所选设置执行。
- 调整首次引导的文字排版与窗口适配。

R49 保留 R48 的游戏功能，本次修改集中在引导与弹窗。

## 主要功能

| 区域 | 功能 |
| --- | --- |
| 像素 HUD | 子民与敌人血条、Boss 血条、建筑耐久、坐骑耐力、职业人数与国库看板、突袭方向及距离、破墙提醒；支持分项开关、上下分屏和暂停菜单避让 |
| 岛屿小地图 | 多种样式、五套图标画风、分类筛选、设施等级、前沿城墙耐久、怪物位置、工具和可招募人数统计；缩放、左右浏览、地点组合列表与传送 |
| 地图显示 | 背景开关、防剧透探索范围、静止后收起与移动展开；实景缩略样式记录已经过的区域 |
| 时间 | 当天时钟、季节、下个季节倒计时、血月提示 |
| 基础辅助 | 君主与子民保护、无限体力、城墙保护、快速建造与砍树、暂停昼夜、移动速度调整、伙伴与隐士保护 |
| 资源与国库 | 免费消费、钱袋容量无限、居民自动存钱与钱袋国库互通、单次加金币或宝石；容量无限按实际收入和消费记账，相关金钱功能互斥 |
| 招募与商店 | 难民生成加速、营地和居民屋远程招募、远程购买弓/锤/农具/面包、弓箭手不排队；遵守店铺、库存及当前消费模式 |
| 开发者工坊 | 分类操作、全图地点瞬移、时间与时代调整、环境与战斗工具、功能实际状态显示 |
| 记忆 | 默认开启切档保护；可选全局或分存档记忆，逐存档控制是否保留功能状态 |
| 诊断与反馈 | 游戏指纹及兼容性查看、复制报告、运行诊断与日志、问题分类、截图、日志和离线反馈包 |
| 窗口操作 | 游戏鼠标指针、窗口置顶、透明度、快捷键与游戏内状态提示 |
| 可选插件模式 | 插件无限耐力与简要状态条；与独立模式分别显示界面，切换需关闭功能并重启游戏 |

## 运行与安装

1. 使用 Windows 10/11 64 位及游戏 **2.4.3（Windows IL2CPP）**。无需另装 Python。
2. 关闭旧修改器，将 ZIP 中全部文件完整解压到同一文件夹。
3. 运行 `KingdomTrainer.exe`，启动游戏，等待连接后选择需要的功能。
4. 保留同目录的 `trainer_core.dll`、`update_config.json` 和其他配套文件。独立模式不需要安装 BepInEx；插件模式通过软件内入口安装组件并重启游戏。

分屏 HUD 支持上下两位玩家的视口。联机修改效果取决于主机权限及同步机制；国库互通限单人使用。开发者工坊建议使用新测试存档。

玩家包不含个人设置、存档记录或日志。同一台电脑已有的软件设置会继续保留。

## 主要快捷键（独立模式）

| 按键 | 功能 |
| --- | --- |
| F1 / F2 | 君主保护 / 无限体力 |
| F3 / F4 | 免费消费 / 子民与出征部队免伤 |
| F5 / Shift+F5 | 营地招募 / 居民屋招募 |
| Ctrl+F5 | 难民生成加速 |
| F6 / Shift+F6 / Alt+F6 | 买弓 / 买锤 / 买农具 |
| Ctrl+Shift+F6 / Ctrl+F6 | 买面包 / 弓箭手不排队 |
| F7 / F8 | 城墙保护 / 快速建造与砍树 |
| Ctrl+F7 / Ctrl+F8 | 加 5 枚金币 / 加 1 颗宝石 |
| F9 | 暂停/恢复昼夜交替 |
| F10 / Ctrl+F10 | 国库互通 / 钱袋容量无限 |
| F11 / F12 | HUD / 快捷键看板 |
| Alt+1～9 / Ctrl+1～9 | 君主 / NPC 移动速度预设 |
| + / - | 地图放大 / 缩小 |
| , / . | 放大地图时左右浏览 |
| Alt+F9 | 智能自检与故障排查 |

## 反馈与版本信息

软件“关于”页提供免 GitHub 账号的网页反馈入口及离线反馈包；也可以使用本仓库 [Issues](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/issues)（需要 GitHub 账号）。

- [更新检测文件](https://raw.githubusercontent.com/Moolmool114/KingdomTwoCrowns-Trainer/main/version.json)
- [jsDelivr 备用入口](https://cdn.jsdelivr.net/gh/Moolmool114/KingdomTwoCrowns-Trainer@main/version.json)

R49 ZIP 的 SHA-256：`40afe2e5755387f48a09b27e98b86de4c57b4d07c385ce13fed614a120189c24`。

许可条款见 [LICENSE](LICENSE)。
