# Config

本仓库用于存储个人的 Mac 开发环境配置文件与配置清单，便于在新机器或重装系统时快速恢复常用设置，个人配置，仅供参考。

## 系统配置

## 浏览器配置

在浏览器设置中，将默认搜索引擎改为熟悉且可靠的选项（例如 Bing、Google），以减少劣质搜索引擎带来的广告或不良体验。

推荐检查并配置的项：

- 默认搜索引擎
- 隐私设置（阻止第三方 Cookie、发送 Do Not Track）
- 必要的扩展（Adblock、HTTPS Everywhere、密码管理器等）

## 安装梯子（代理）

作为开发者可能需要频繁访问境外文档、仓库和下载资源。在国内网络环境下，使用合规的代理工具可以提高访问稳定性与下载速度。

参考项目：clash-verge-rev

- 项目地址： https://github.com/clash-verge-rev/clash-verge-rev

安装后注意：

- 需要配置你的订阅地址（机场提供的 URL）或手动导入配置
- 保持规则与订阅更新以获得最佳效果

安全与合规提示：请遵守当地法律法规，使用合规服务与订阅。

## 安装 Homebrew（macOS）

Homebrew 是 macOS 上常用的包管理器（在苹果 M1/ARM 平台下通常安装到 `/opt/homebrew`）。Linux 用户大多数情况下可以使用系统自带包管理器（apt、dnf、pacman 等）。

在 macOS 终端中运行下面命令来安装 Homebrew：

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

安装完成后常用命令示例：

- 安装软件：

```bash
brew install git wget node
```

- 列出已安装的软件：

```bash
brew list
```

- 更新并清理缓存/旧包：

```bash
brew update && brew upgrade && brew cleanup -s && brew autoremove
```
