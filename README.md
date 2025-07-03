# GitHub Actions 编译 OpenWrt 固件

本项目使用 GitHub Actions 在线编译 OpenWrt 固件，支持：
- x86_64 架构
- LuCI 界面
- Passwall / OpenClash
- Docker 支持
- Argon 主题

## 使用方法

1. Fork 本仓库
2. 打开 `.github/workflows/build-openwrt.yml`
3. 点击 GitHub 的 [Actions] 页面，选择 `Build OpenWrt`，点击 `Run workflow` 即可开始编译

编译完成后，可在 Actions Artifacts 中下载固件。
