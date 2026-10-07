# Kingdom Two Crowns Trainer and Pixel HUD

《王国：两位君主》独立辅助工具与像素 HUD

![Version](https://img.shields.io/badge/version-2.6.1-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A free standalone Windows trainer for **Kingdom Two Crowns**, with a configurable pixel HUD and optional gameplay assists. The application interface is in Simplified Chinese.

一款免费的 Windows 独立辅助工具，提供可自选显示项目的像素 HUD 和按需开启的游戏辅助功能。软件界面为简体中文。

This repository distributes compiled player packages and release information. Source code is not included.

本仓库用于发布编译后的玩家包和版本信息，不提供源代码。

## Download / 下载

- [Download v2.6.1 / 下载 v2.6.1 玩家包](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/download/v2.6.1/KingdomTrainer_v2.6.1_GitHub.zip)
- [Latest release / 最新发行版](https://github.com/Moolmool114/KingdomTwoCrowns-Trainer/releases/latest)
- [Baidu Netdisk / 百度网盘](https://pan.baidu.com/s/1n6NLje4odhFh29FuWvUnqg?pwd=1976) — Extraction code / 提取码：`1976`
- [Lanzou / 蓝奏盘](https://wwazv.lanzout.com/iVt8f4ayo23i) — Access password / 提取密码：`ew9t`；ZIP password / 解压密码：`kingdom`

The tool is provided free of charge. Use the official release links above.

本工具免费提供，请通过上方官方发行链接下载。

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
- Kingdom Two Crowns, Windows IL2CPP version / 《王国：两位君主》Windows IL2CPP 版本
- No separate Python installation is required / 玩家包无需单独安装 Python
- Application interface: Simplified Chinese / 软件界面语言：简体中文

## Installation / 安装与使用

1. Download the ZIP from Releases and extract all files into one folder.
   在 Releases 下载 ZIP，将全部文件解压到同一个文件夹。
2. Keep `trainer_core.dll` and `update_config.json` beside `KingdomTrainer.exe`.
   将 `trainer_core.dll` 和 `update_config.json` 与主程序 `KingdomTrainer.exe` 放在一起。
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
| F3 | Spending does not reduce coins or gems | 消费不扣金币与宝石 |
| F4 | Treat available funds as sufficient | 永久判定金钱充足 |
| F5 | Keep carried coins at 99 | 随身金币锁定为 99 枚 |
| F6 | Keep carried gems at 50 | 随身宝石锁定为 50 颗 |
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

