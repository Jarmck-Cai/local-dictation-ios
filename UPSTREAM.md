# 来源与仓库拆分

本项目从 [Jarmck-Cai/local-dictation](https://github.com/Jarmck-Cai/local-dictation) 的 iPhone 原型提取，来源提交 [`5840859`](https://github.com/Jarmck-Cai/local-dictation/commit/5840859b8c8829d2924917df3b57f6cef0cae6c9)。

导入范围为 `ios/`、`services/ios-enhancement/`、原生 CI 和代码许可。原 `ios/` 内容提升为本仓库根目录，安装命令和 CI 路径同步调整；Swift 和后端运行代码保持不变。原仓库保留此前历史，本仓库从可独立构建的源码快照开始管理。

本仓库不包含 Windows 源码、模型、录音、用户数据、密钥或签名材料，也不以另一仓库作为子模块、包或本机目录依赖。两端可以使用相同的上游公开模型，但各自下载、验证与管理，源码和发布互不引用。

代码许可见 `LICENSE`；模型权重和原生运行时分别遵守 `THIRD_PARTY.md` 中的上游许可。
