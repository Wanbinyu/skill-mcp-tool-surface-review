# MCP Tool Surface Review

[English](README.md) | **中文**

<p align="center"><strong>一个 skill · 30 秒安装 · 用于 Claude / Codex / Cursor</strong></p>
<p align="center"><code>mcp-tool-surface-review</code> · MIT · Agent Skills 格式</p>

---

## 先从这里开始

### 安装

```powershell
git clone https://github.com/Wanbinyu/skill-mcp-tool-surface-review.git
cd skill-mcp-tool-surface-review
.\scripts\install.ps1 -Claude
```

```bash
git clone https://github.com/Wanbinyu/skill-mcp-tool-surface-review.git
cd skill-mcp-tool-surface-review
chmod +x scripts/install.sh && ./scripts/install.sh --claude
```

→ `~/.claude/skills/mcp-tool-surface-review/` · **请重启 Claude Code**

### 然后可以直接说

- 「用 `mcp-tool-surface-review` skill 处理我当前的改动」
- 或匹配 `SKILL.md` 顶部 `description` 里的中英文触发词

---

## 这个 skill 解决什么

Review an existing MCP server's tool surface for safety and clarity. Use when auditing tools/list output, third-party MCP installs, or Chinese "审查 MCP 工具", "MCP 安全面", "tools/list 审计". Does NOT teach how to scaffold a new MCP server (use official mcp-builder).

完整流程（步骤、完成标准、报告模板）见：**[`SKILL.md`](SKILL.md)**

> 给人看的文档：本页中文 + [English](README.md)。  
> `SKILL.md` 正文以英文为主，方便 agent 稳定执行。

---

## 一个 skill = 一个项目

- 本仓库：**仅** `mcp-tool-surface-review`
- 整包装：[ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- 全部独立 skill：https://github.com/Wanbinyu?tab=repositories&q=skill-

### 插件

```text
/plugin marketplace add Wanbinyu/skill-mcp-tool-surface-review
/plugin install mcp-tool-surface-review@mcp-tool-surface-review
```

## 许可证

MIT · [Wanbinyu](https://github.com/Wanbinyu)
