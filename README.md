# pal-plugins

English | [简体中文](README.zh-CN.md)

A plugin catalog for Claude Code and Codex. It only lists plugins; each plugin is developed in its own repository, and installing downloads just the plugin itself.

| Plugin | What it does |
|---|---|
| [coding-pal](https://github.com/KeelingYU/coding-pal) | Development workflow for people who don't write code: requirements, UI, plan, build and acceptance |

## Install

Claude Code:

```bash
claude plugin marketplace add KeelingYU/pal-plugins && claude plugin install coding-pal@pal-plugins
```

Codex:

```bash
codex plugin marketplace add KeelingYU/pal-plugins && codex plugin add coding-pal@pal-plugins
```

Or send this repository's link to Claude Code or Codex and say "install coding-pal from this". Installing never writes into your projects.

## Update

Only released versions reach you; work in progress never does.

Claude Code updates only when you ask. Tell the agent "update coding-pal", or run (then restart Claude Code):

```bash
claude plugin marketplace update pal-plugins && claude plugin update coding-pal@pal-plugins
```

Codex updates to the latest release automatically each time you start a new session. To update right away, run:

```bash
codex plugin marketplace upgrade pal-plugins
```
