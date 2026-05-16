# BazaarInsight

BazaarInsight 是 The Bazaar 的本地战斗模拟与 Mod 辅助工具。

这个仓库目前只用于：

- 发布 BazaarInsight 桌面应用安装包。
- 提供自动更新所需的 Release 资源。
- 收集用户反馈和 Issue。

项目源码暂不开源，所以这个仓库不会包含源码、构建脚本或开发历史。请从 [Releases](../../releases) 下载最新版本。

## 下载和更新

GitHub 和 Gitee 都会发布安装包。不同来源下载的安装包内置不同的自动更新优先级：

- 从 GitHub 下载的安装包会优先使用 GitHub 更新源，Gitee 作为兜底。
- 从 Gitee 下载的安装包会优先使用 Gitee 更新源，GitHub 作为兜底。

自动更新不会强制安装，也不会阻塞应用使用；有新版本时会在应用内提示，由用户手动下载并重启安装。

## 反馈问题

如果遇到安装、启动、Mod 注入、模拟结果异常等问题，请在 [Issues](../../issues) 反馈，并尽量附上：

- 操作系统和版本。
- BazaarInsight 版本。
- The Bazaar 版本。
- 问题截图或错误日志。
- 能稳定复现的话，请写一下复现步骤。
