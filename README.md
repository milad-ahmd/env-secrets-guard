<div align="center">

# 🔐 env-secrets-guard

**Find leaked API keys and secrets before they hit GitHub. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/env-secrets-guard)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/env-secrets-guard?style=social)](https://github.com/milad-ahmd/env-secrets-guard)
![Category](https://img.shields.io/badge/category-Security%20&%20Maintenance-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/env-secrets-guard/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

<img src="assets/demo.gif" alt="env-secrets-guard demo (real output)" width="760"/>

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- env-secrets-guard
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/env-secrets-guard /tmp/env-secrets-guard
mkdir -p ~/.claude/skills && cp -r /tmp/env-secrets-guard/skills/env-secrets-guard ~/.claude/skills/
```

**Per project:** copy `skills/env-secrets-guard` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/env-secrets-guard/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Scan this repo for leaked secrets before I push
I'm open-sourcing this repo, is it safe?
```

The full workflow, rules and output format are in [`SKILL.md`](skills/env-secrets-guard/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
