# JasonAndClaude Skills

A collection of Claude Code skills for designing Claude Code project infrastructure.

---

## Skills

### buildwithclaude-v1

Analyzes a project idea and recommends the right Claude Code infrastructure — agents, subagents, MCP servers, hooks, skills, plugins, git worktrees, or just a CLAUDE.md. Offers to scaffold the folder structure.

**Install:**
```bash
cp -r skills/buildwithclaude-v1 ~/.claude/skills/
```

**Usage:**
```
/buildwithclaude-v1 [describe your project idea]
```

---

### buildwithclaude-v2

An updated version with domain-specific recommendations. Identifies your project domain (web, mobile, ML/AI, DevOps, game dev, blockchain, embedded, etc.) and gives tailored plugin recommendations, subagent patterns, hook strategies, and a folder structure.

**Install:**
```bash
cp -r skills/buildwithclaude-v2 ~/.claude/skills/
```

**Usage:**
```
/buildwithclaude-v2 [describe your project idea]
```

---

## Install all skills

```bash
cp -r skills/* ~/.claude/skills/
```
