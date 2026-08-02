# MCP Tool Surface Review

**English** | [中文](README.zh-CN.md)

<p align="center"><strong>One skill. Install in 30 seconds. Use in Claude / Codex / Cursor.</strong></p>
<p align="center"><code>mcp-tool-surface-review</code> · MIT · Agent Skills format</p>

---

## Start here

### Install

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

→ `~/.claude/skills/mcp-tool-surface-review/` · **Restart Claude Code**

### Then say (examples)

- *Use the `mcp-tool-surface-review` skill on my current change.*
- Or any phrase matching the triggers in `SKILL.md` frontmatter (EN + ZH).

---

## What this skill is for

Review an existing MCP server's tool surface for safety and clarity. Use when auditing tools/list output, third-party MCP installs, or Chinese "审查 MCP 工具", "MCP 安全面", "tools/list 审计". Does NOT teach how to scaffold a new MCP server (use official mcp-builder).

Full workflow (steps, exit criteria, report template): **[`SKILL.md`](SKILL.md)**

> Human docs: EN + [中文](README.zh-CN.md).  
> `SKILL.md` body is English so agents execute consistently.

---

## One skill = one project

- This repo: **only** `mcp-tool-surface-review`
- Bulk packs: [ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- All solo skills: https://github.com/Wanbinyu?tab=repositories&q=skill-

### Plugin

```text
/plugin marketplace add Wanbinyu/skill-mcp-tool-surface-review
/plugin install mcp-tool-surface-review@mcp-tool-surface-review
```

## License

MIT · [Wanbinyu](https://github.com/Wanbinyu)
