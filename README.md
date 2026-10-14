# Kingdom Two Crowns Trainer and Pixel HUD

《王国：两位君主》独立辅助工具与像素 HUD

![Version](https://img.shields.io/badge/version-2.6.3-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A free standalone Windows trainer for **Kingdom Two Crowns**, with a configurable pixel HUD and optional gameplay assists. The application interface is in Simplified Chinese.

一款免费的 Windows 独立辅助工具，提供可自选显示项目的像素 HUD 和按需开启的游戏辅助功能。软件界面为简体中文。

This repository distributes compiled player packages and release information. Source code is not included.

本仓库用于发布编译后的玩家包和版本信息，不提供源代码。

## Download / 下载

- [Download v2.6.3 / 下载 v2.6.3 玩家包](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v2.6.3/KingdomTrainer_v2.6.3_GitHub.zip)
- [Latest release / 最新发行版](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/latest)
- [Baidu Netdisk / 百度网盘](https://pan.baidu.com/s/1n6NLje4odhFh29FuWvUnqg?pwd=1976) — Extraction code / 提取码：`1976`
- [Lanzou / 蓝奏盘](https://wwazv.lanzout.com/iVt8f4ayo23i) — Access password / 提取密码：`ew9t`；ZIP password / 解压密码：`kingdom`

The tool is provided free of charge. Use the official release links above.

本工具免费提供，请通过上方官方发行链接下载。

## 2.6.3 update / 本次更新

- Backports R35 stamina, coin and wall protection into the existing 2.6.1 interface / 向原 2.6.1 界面下放新版耐力、金币免扣和城墙保护
- Click once for 5 coins or 1 gem; no continuous refill / 单次点击加 5 金币或 1 钻石，不持续补充
- Native wall repair supports Norselands without direct HP locking / 使用游戏自身城墙修复流程，覆盖北欧城墙，避免直接锁血干扰攻击
- Coordinates F3/F4 shared wallet entries and clears stale wallet identities during loading / 处理 F3/F4 共用入口恢复，载入地图时清除旧钱袋地址
- Update checks offer 2.6.3 only to older clients / 仅低于 2.6.3 的客户端会收到本次更新提示

These backported features act on the running game. One-shot grants do not belong to permanent file patches.

本次下放功能作用于运行中的游戏；单次领取资源不属于永久文件补丁。2.6.3 本次发布在 GitHub。

## Features / 功能

- Citizen professions and health bars, Boss and Greed health bars / 子民职业与血量、Boss 与贪婪小怪血条
- Wall and portal durability, mount stamina / 城墙与传送门耐久、坐骑耐力
- Population counts by profession and treasury gold / 各职业人数与国库金币
- Off-screen Boss direction and distance, wall breach alerts / 屏幕外 Boss 的方向与距离、破墙提醒
- Individual HUD switches, crowded-display grouping and a hotkey panel / HUD 分项开关、扎堆合并与快捷键看板
- Optional invulnerability, resource, construction, daylight and movement assists / 按需开启无敌、资源、建造、白昼与移动辅助
- An update check in the About window / 关于页面中的更新检查

## Requirements / 运行环境

- Windows 10/11, 64-bit / Windows 10/11 64 位
- Kingdom Two Crowns 2.4.3, revision 23537, Windows IL2CPP / 《王国：两位君主》2.4.3（23537）Windows IL2CPP 版本
- No separate Python installation is required / 玩家包无需单独安装 Python
- Application interface: Simplified Chinese / 软件界面语言：简体中文

## Installation / 安装与使用

1. Download the ZIP from Releases and extract all files into one folder.
   在 Releases 下载 ZIP，将全部文件解压到同一个文件夹。
2. Keep `trainer_core.dll`, `trainer_features.dll` and `update_config.json` beside `KingdomTrainer.exe`.
   将两个 DLL 和 `update_config.json` 与主程序 `KingdomTrainer.exe` 放在一起，并先关闭旧修改器。
3. Run `KingdomTrainer.exe` and launch the game. Either can start first.
   运行主程序并启动游戏，启动顺序不限。
4. Wait for the trainer to connect, then choose the HUD displays and assists you need.
   等待工具显示已连接游戏，再选择需要的 HUD 项目和辅助功能。

Regular trainer switches apply changes to the running game process. The separate permanent-patch option writes selected changes to `GameAssembly.dll`.

常规辅助开关作用于运行中的游戏进程。另有独立的永久补丁选项，会把所选修改写入 `GameAssembly.dll`。

## Hotkeys / 快捷键

| Key / 按键 | English | 中文 |
| --- | --- | --- |
| F1 | Monarch invulnerability / prevent crown loss | 君主无敌 / 皇冠不落 |
| F2 | Infinite mount stamina | 坐骑无限体力 |
| F3 | Coin spending and manual drops do not reduce coins | 消费与撒币不扣金币；宝石按实际余额扣除 |
| F4 | Treat available funds as sufficient | 永久判定金钱充足 |
| F5 / F6 | Unassigned | 已空出；加金币和钻石改为单次按钮 |
| F7 | Wall protection | 城墙保护 |
| F8 | Fast construction, upgrades, repairs and tree chopping | 快速建造、升级、修复和砍树 |
| F9 | Daylight lock | 锁定白天 |
| F10 | Enable the game's built-in developer menu | 开启游戏内置开发者菜单 |
| F11 | Show or hide the HUD | 显示或隐藏 HUD |
| F12 | Show or hide the hotkey panel | 显示或隐藏快捷键看板 |
| Alt + 1–4 | Monarch speed: 1.0x / 1.5x / 2.0x / 3.0x | 君主移动速度：1.0 / 1.5 / 2.0 / 3.0 倍 |
| Ctrl + 1–4 | NPC speed: 1.0x / 1.5x / 2.0x / 3.0x | NPC 移动速度：1.0 / 1.5 / 2.0 / 3.0 倍 |

## Version information / 版本信息

- [version.json](https://raw.githubusercontent.com/Moolmool114/KingdomTwoCrowns-Trainer/main/version.json)
- [jsDelivr mirror / jsDelivr 镜像](https://cdn.jsdelivr.net/gh/Moolmool114/KingdomTwoCrowns-Trainer@main/version.json)

## License / 许可

See [LICENSE](LICENSE) for the supplied MIT License.

许可条款见随包提供的 [LICENSE](LICENSE)。


