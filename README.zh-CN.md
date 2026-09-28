# pal-plugins

[English](README.md) | 简体中文

Claude Code 与 Codex 的插件目录。这里只登记插件，每个插件在自己的仓库里开发；安装时只下载插件本身。

| 插件 | 用途 |
|---|---|
| [coding-pal](https://github.com/KeelingYU/coding-pal) | 让不写代码的人按「需求 → 界面 → 方案 → 实现 → 验收」把项目做出来的开发流程 |

## 安装

Claude Code：

```bash
claude plugin marketplace add KeelingYU/pal-plugins && claude plugin install coding-pal@pal-plugins
```

Codex：

```bash
codex plugin marketplace add KeelingYU/pal-plugins && codex plugin add coding-pal@pal-plugins
```

也可以把本仓库的链接发给 Claude Code 或 Codex，说「用这个安装 coding-pal」。安装不会往你的任何项目里写文件。

## 更新

你只会拿到已发布的版本，开发中的改动不会到你这里。

Claude Code 只在你要求时更新。对 Agent 说「更新 coding-pal」，或者运行（运行后重启 Claude Code）：

```bash
claude plugin marketplace update pal-plugins && claude plugin update coding-pal@pal-plugins
```

Codex 每次开新会话时会自动更新到最新发布版。想立即更新，运行：

```bash
codex plugin marketplace upgrade pal-plugins
```
