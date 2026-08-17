# 小说工坊更新通道

本仓库只承载小说工坊 Windows 安装版的自动更新文件：

- Windows x64 安装程序
- 增量更新 `.blockmap`
- Electron 更新清单 `latest.yml`

应用源码、作品数据、模型配置和本机密钥不存放在这里。

正式版本由私有源码仓库的 GitHub Actions 构建并发布。安装版中的“软件更新”页面会读取本仓库最新 Release，完成检查、下载和重启安装。
