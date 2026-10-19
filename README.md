# 桌面应用 — 本地小工具 / GUI

**定位**：桌面小工具、托盘程序、本地管理面板

**本机状态**：✅ 可直接开发（打包需补装）

**工具链**：Node（可运行 Electron）；无 Electron 打包器

**建议技术栈**：Electron / Tauri（Rust 需补装）/ 纯 HTML 单页

**注意**：纯网页版可零依赖；打包成 .exe 需装 electron-builder 等

## 子方向索引

本方向再细分为 **7** 个应用子方向，每个子方向一个子目录（均含 README + 6 份文档）：

| 子目录 | 子方向 | 本机状态 |
|---|---|---|
| [`electron-app`](./electron-app/) | Electron 桌面应用 | ✅ |
| [`tauri-app`](./tauri-app/) | Tauri 轻量桌面应用 | ⚠️ |
| [`tray-utility`](./tray-utility/) | 托盘小工具与效率助手 | ✅ |
| [`local-dashboard`](./local-dashboard/) | 本地看板 / 仪表盘 | ✅ |
| [`file-clip-tool`](./file-clip-tool/) | 文件管理与剪贴板工具 | ✅ |
| [`note-tool`](./note-tool/) | 笔记 / 知识管理桌面端 | ✅ |
| [`cli-gui-hybrid`](./cli-gui-hybrid/) | CLI + GUI 混合工具 | ✅ |

---

**放什么**：本方向的具体项目放在对应子方向目录下（每个项目再建一个子目录）。
