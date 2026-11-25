# 淼图（AquaMap）改进版

《逃离塔科夫》离线辅助地图「淼图」2.6.5 的非官方改进版。原版作者 NepPure（MIT 许可）：https://github.com/NepPure/tarkov-offline-map

## 下载

到右边的 **[Releases（发布）](https://github.com/yx-storehouse/aquamap-improved/releases/latest)** 下载最新的 `AquaMap-…-full.zip`：

1. 解压到普通目录（建议 D 盘；别放进 `C:\Program Files` 这种要管理员权限的地方）。
2. 双击「淼图-Aqua Map.exe」。
3. 详细说明见压缩包里的「使用说明.txt」。

## 改进版多了什么

- 界面改版：字更大、对比度更高、地图更大；顶栏「在本图找…」搜索。
- 读游戏日志自动补任务进度（可撤销、可关）。
- 钥匙刷新点图层：精确刷点 + EFT Wiki 的大概位置、中文说明、位置截图（点了才下载）。
- 内置 3D 地图和灵魂出窍（需要另外安装 TarkovLootMap，见下）。
- 手机地图（同一个局域网，用手机浏览器看）。

## 不在包里的东西

- **3D 模型**：从游戏里提取，版权归 Battlestate Games。请从 TarkovLootMap 官网安装：https://tarkovlootmap.com/ （右上角「下载客户端」），装好后先打开一次让它下载地图模型，淼图会自动找到它。
- **导航（路线指引）的路网数据**：从游戏文件提取，不随包发布。
- 本仓库只放发布包，不含源码。

## 版权与来源

- 淼图原版：MIT 许可，Copyright (c) 2026 NepPure（全文见 [LICENSE-AquaMap-original.txt](LICENSE-AquaMap-original.txt)）。本包在原版基础上做了修改。
- 物品与价格数据来自 tarkov.dev；地图点位数据来自 tarkov.dev / the-hideout。
- 钥匙刷点文字来自 EFT Wiki（escapefromtarkov.fandom.com，CC BY-SA 3.0），中文为淼图翻译、改写，同样按 CC BY-SA 3.0 共享；Wiki 截图只在用户点击时从 Wiki 下载，不随包发布。
- 3D 渲染代码改编自 TarkovLootMap（MIT 许可）；three.js（MIT）；NoSleep.js（MIT）。
- 游戏地图、图标等素材的版权归 Battlestate Games 所有。本工具与 Battlestate Games 无关，仅供个人学习交流使用。
