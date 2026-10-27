# iPhone 项目开发

仓库：<https://github.com/Jarmck-Cai/local-dictation-ios>。`main` 保存经相关检查的代码，功能分支采用 `codex/` 前缀。

## 日常检查与推送

开始前检查分支与工作区，保留已有工作。策略变更运行 `swift test --package-path LocalDictationCore`；后端变更在 `services/ios-enhancement` 运行 `npm test`。原生工程或构建路径变更，用 Xcode 生成/编译或 macOS CI 验证。Windows 环境不能替代 Xcode 编译。

每个有意义的阶段在相关检查后审阅差异和暂存内容，使用 Conventional Commits 提交并推送当前分支。只保留当前项目源码和公开文档，遵守根 `.gitignore`；密钥、录音、用户数据、模型、签名和私人交接保持本地。默认不重写远端历史。

## 安装与版本

安装入口见根 `README.md`。普通 Apple ID 使用 `LocalDictationOffline`；跨应用键盘共享使用 App Groups，需相应团队签名。模拟器启动、无签名编译、真实设备安装与识别质量是不同证据，分别记录。

正式 iOS 交付时同步 `project.yml` 的 `MARKETING_VERSION` / `CURRENT_PROJECT_VERSION` 与公开变更说明，检查通过后建立本仓库自己的不可变版本标签。Windows 仓库的版本、标签和发布独立管理。本次拆仓保持原型 `0.1.0` / build `1`，不是 App Store 发布或真机验收。

增强后端当前保持未部署。供应商密钥仅配置在后端；客户端服务设置由开发者内置。模型调用、真人录音验收和后端部署按用户当前确认范围执行。
