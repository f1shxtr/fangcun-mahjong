# 方寸麻将

一个可在浏览器中直接游玩的国标麻将单机版。你与三个启发式人机对战，支持传统麻将牌面、语音播报、完整玩法说明和图解番表。

## 在线试玩

GitHub Pages 部署完成后，可在这里直接游玩：

https://f1shxtr.github.io/fangcun-mahjong/

## 特点

- 纯浏览器运行，游戏逻辑在 Web Worker 中执行，无需游戏后端或账号。
- 与三个启发式人机进行国标麻将单机对局。
- 包含出牌、吃碰杠胡的语音播报，以及 81 种番种的示例与说明。
- 支持现代桌面和移动浏览器中的 WebAssembly 与 Web Worker。

首次打开需下载约 14 MB 的游戏资源；加载完成后，对局不需要连接游戏服务器。浏览器语音音色由设备和系统提供。

## 部署

GitHub Actions 会在 `main` 分支更新后自动解压 `site.zip` 并发布到 GitHub Pages。部署状态可在仓库的 Actions 页面查看。

## 许可证

站点运行包内附 `LICENSE.txt` 和 `THIRD_PARTY.md`，请查看其中的项目及第三方组件许可信息。
