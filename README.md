# JasonAndClaude

A collection of my Claude Skills and Public Skills that I find actually useful.

```bash
git clone https://github.com/jasonzhang443/JasonAndClaude.git
```

---

## Skills

### buildwithclaude

Analyzes a project idea and recommends the right Claude Code infrastructure — agents, subagents, MCP servers, hooks, skills, plugins, git worktrees, or just a CLAUDE.md. Offers to scaffold the folder structure.

**Install:**
```bash
git clone --filter=blob:none --sparse https://github.com/jasonzhang443/JasonAndClaude.git && cd JasonAndClaude && git sparse-checkout set skills/buildwithclaude-v1 && cp -r skills/buildwithclaude-v1 ~/.claude/skills/buildwithclaude
```

**Usage:**
```
/buildwithclaude [describe your project idea]
```

---

### buildwithclaude2

An updated version of buildwithclaude with domain-specific recommendations. Identifies your project domain (web, mobile, ML/AI, DevOps, game dev, blockchain, embedded, etc.) and gives tailored plugin recommendations, subagent patterns, hook strategies, and a folder structure.

**Install:**
```bash
git clone --filter=blob:none --sparse https://github.com/jasonzhang443/JasonAndClaude.git && cd JasonAndClaude && git sparse-checkout set skills/buildwithclaude-v2 && cp -r skills/buildwithclaude-v2 ~/.claude/skills/buildwithclaude2
```

**Usage:**
```
/buildwithclaude2 [describe your project idea]
```
