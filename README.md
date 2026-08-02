# MCP Tool Surface Review

**English** | [中文](README.zh-CN.md)

<p align="center">
  <strong>Standalone Agent Skill</strong> · <code>mcp-tool-surface-review</code>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT" /></a>
  <a href="https://github.com/agentskills/agentskills"><img src="https://img.shields.io/badge/format-Agent%20Skills-111827" alt="Agent Skills" /></a>
</p>

Review an existing MCP server's tool surface for safety and clarity. Use when auditing tools/list output, third-party MCP installs, or Chinese "审查 MCP 工具", "MCP 安全面", "tools/list 审计". Does NOT teach how to scaffold a new MCP server (use official mcp-builder).

---

## Install (Claude Code)

```powershell
git clone https://github.com/Wanbinyu/skill-mcp-tool-surface-review.git
cd skill-mcp-tool-surface-review
.\scripts\install.ps1 -Claude
```

```bash
git clone https://github.com/Wanbinyu/skill-mcp-tool-surface-review.git
cd skill-mcp-tool-surface-review
chmod +x scripts/install.sh
./scripts/install.sh --claude
```

Claude skill id remains **`mcp-tool-surface-review`** (no `skill-` prefix):

`~/.claude/skills/mcp-tool-surface-review/`

Restart Claude Code after install.

### Plugin

```text
/plugin marketplace add Wanbinyu/skill-mcp-tool-surface-review
/plugin install mcp-tool-surface-review@mcp-tool-surface-review
/reload-plugins
```

---

## What this skill does

See [`SKILL.md`](SKILL.md) (same as `skills/mcp-tool-surface-review/SKILL.md`).

The YAML `description` at the top of `SKILL.md` holds triggers (often EN + ZH).

> **Note:** `SKILL.md` body is English so agents follow instructions reliably.  
> Human docs are bilingual: this file + [`README.zh-CN.md`](README.zh-CN.md).

---

## One skill = one project

This repo ships **only this skill**.  
Bulk install of related skills:

- Collection: [ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- Catalog: [`CATALOG.md`](../CATALOG.md) / [`CATALOG.zh-CN.md`](../CATALOG.zh-CN.md) (local `G:\\skill\\solo`)

---

## Layout

```text
skill-mcp-tool-surface-review/   (GitHub)  or  solo/mcp-tool-surface-review/  (local)
  README.md              # English
  README.zh-CN.md        # Chinese
  SKILL.md
  skills/mcp-tool-surface-review/SKILL.md
  scripts/install.ps1
  .claude-plugin/
```

## License

MIT · [Wanbinyu](https://github.com/Wanbinyu)
