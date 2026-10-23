# likehao

我做本地优先的桌面软件。写作、预览、远程连接和数据库都在本机完成，文件不交给账号体系。

I build local-first desktop software. Writing, preview, remote access, and databases run on the machine in front of you.

## 作品

### [InkNote](https://github.com/likehao19/InkNote)

所见即所得的 Markdown 编辑器。排版在书写时呈现，磁盘上始终是标准 Markdown。不需要账号，也不会上传文稿。

[网站](https://likehao19.github.io/InkNote/) · Tauri 2 · React · CodeMirror 6

### [瞬览 SpacePreview](https://github.com/likehao19/SpacePreview)

本地文件预览。在资源管理器或 Finder 里按快捷键即可查看文档、图片、压缩包以及更多格式，不必先打开对应软件。

Tauri 2 · React · Rust

### [Orbiterm](https://github.com/likehao19/Orbiterm)

SSH / SFTP 客户端。终端是真实的交互式会话，文件传输走独立连接，不挡住输入。密码和私钥口令只留在这一次连接里。

Tauri 2 · Rust · xterm.js · libssh2

### [玄枢 XuanCore Studio](https://github.com/likehao19/XuanCore-Studio)

数据库工作台。安装包不含数据库驱动；驱动是独立的签名包，校验通过后才安装。

Tauri 2 · SolidJS · Rust

## 另外

同一方向还有 [ToolHub](https://github.com/likehao19/toolhub)（笔记、日程、密码与本地 AI 助手）和 [DeepSeek Harness Desktop](https://github.com/likehao19/DeepSeek-Harness-Desktop)（DeepSeek Harness 的桌面壳）。

桌面产品用 Tauri 2 和 Rust。界面是 TypeScript，按产品选用 React、Vue 或 Solid。更早的工作是 Spring Boot、Vue 和 Java Web。

产品问题请开到对应仓库的 Issues。
