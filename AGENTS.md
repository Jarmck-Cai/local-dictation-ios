# 项目上下文

用中文沟通。开始工作时，若存在本机 `docs/handoff.md`，先读该文件，再读 `docs/project-brief.md`；公开克隆以 `README.md` 为入口。

本仓库是独立的 iPhone 原型，Windows 项目在其他仓库。构建和脚本使用本仓库路径；模型与运行时来源、固定摘要及许可见 `THIRD_PARTY.md`。

# 开发与推送

用户已授权本项目日常开发提交、推送到 `Jarmck-Cai/local-dictation-ios`。完成有意义的阶段后运行相关检查，审阅暂存内容，以 Conventional Commits 提交推送，默认不强制推送。具体命令、版本与验证规则见 `docs/development.md`。

公开内容仅包含源码、合成测试、构建配置、公开说明和许可。密钥、签名配置、录音、模型、个人历史及本机交接留在本地。分别报告编译/模拟器证据与真机结果。用户当前选择先安装普通 Apple ID 可签名的离线版，联网部署留待之后确认。
