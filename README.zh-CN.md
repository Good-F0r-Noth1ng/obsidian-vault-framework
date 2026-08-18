# Obsidian 知识库框架

[English](README.md) | [简体中文](README.zh-CN.md)

一个可复用、注重来源追溯的 Obsidian 知识库模板，适用于长期学习、研究与项目知识管理。

## 本仓库提供什么

- 一套分阶段的 `raw/` -> `derived/` -> `wiki/` 知识工作流。
- 一份简洁的知识库治理文件（`AGENTS.md`）。
- 可复用的页面模板和最小化导航结构。
- 四个可选的 Codex skills，用于受控知识库的资料导入、知识沉淀和健康检查。

这是一个**框架仓库**，不是正在使用的个人知识库。仓库有意排除了受版权保护的来源文件、私人笔记、数据、凭据和生成的 OCR 产物。

## 快速开始

1. 在 Obsidian 中将此目录作为一个新知识库打开。
2. 使用 AI Agent 修改知识库前，先阅读 `AGENTS.md`。
3. 将未分类内容暂存在 `inbox/`，把外部原始资料保存在 `raw/`；仅在需要时于 `derived/` 创建可读表示，并将可复用知识整理到 `wiki/`。
4. 可以根据自己的领域调整 `wiki/` 下的分类目录，但不要破坏证据分层边界。

默认 `.gitignore` 会阻止正在使用的知识库内容进入这个公开框架。如果基于本框架创建私人知识库，并希望用 Git 管理个人笔记，请有意识地调整忽略规则。

## 目录结构

| 区域 | 用途 | 默认写入策略 |
| --- | --- | --- |
| `inbox/` | 尚未分类的临时收集内容 | 可修改 |
| `raw/` | 外部原始资料 | 验证导入后保持不可变 |
| `derived/` | 与 `raw/` 对应、可重新生成的可读产物 | 受控写入，需确认 |
| `wiki/` | 经过整理、可追溯来源的知识 | 受控写入，需确认 |
| `templates/` | 可复用的笔记模板 | 由框架维护 |
| `docs/` | 架构与发布说明 | 由框架维护 |
| `skills/` | 可选的 Codex skills | 由框架维护 |

工作流详情见 [docs/architecture.md](docs/architecture.md)，公开发布边界见 [docs/publishing.md](docs/publishing.md)。

## 可选 Skills

`skills/` 目录包含可独立使用的 skills。可以按需复制到 Codex skills 目录，也可以将本仓库保留为项目级参考。

- `obsidian-raw-import`
- `obsidian-derived-import`
- `obsidian-ingest-to-wiki`
- `obsidian-vault-lint`

## 许可证

本框架原创的模板、脚本和 skills 使用 [MIT License](LICENSE) 发布。你自行添加的来源文件和笔记仍由你负责，不包含在本仓库的许可范围内。
