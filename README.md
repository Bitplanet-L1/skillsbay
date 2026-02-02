# SkillsChest 🧰

A curated collection of AI agent skills for Claude, OpenCode, Codex, and other AI coding agents.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Bitplanet-L1/skillschest/pulls)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

## What Are Skills?

Skills are packaged instructions, scripts, and resources that extend AI agent capabilities. They teach agents how to perform specific tasks in a repeatable, standardized way.

Think of skills as "onboarding guides" for agents — they transform a general-purpose AI into a specialized assistant equipped with domain knowledge.

## Quick Install

```bash
# Install a skill
npx skills add Bitplanet-L1/skillschest@<skill-name>

# List available skills
npx skills add Bitplanet-L1/skillschest --list
```

## Available Skills

### Agent & Collaboration

| Skill | Description |
|-------|-------------|
| [agent-learnings](./skills/agent-learnings/) | Extract self-improvement insights from session history. Creates changelogs of mistakes and corrections. |
| [human-agent-collaboration](./skills/human-agent-collaboration/) | Guides for humans on working effectively with AI agents. What works, what doesn't. |

### Development

*Coming soon — [contribute yours!](CONTRIBUTING.md)*

### Productivity

*Coming soon — [contribute yours!](CONTRIBUTING.md)*

### Creative

*Coming soon — [contribute yours!](CONTRIBUTING.md)*

## Contributing

We welcome skill contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Quick steps:**
1. Fork this repo
2. Create a skill folder with `SKILL.md`
3. Add your skill to the README table
4. Submit a PR

## Skill Format

Every skill needs a `SKILL.md` file with YAML frontmatter:

```markdown
---
name: my-skill
description: One-sentence description of what this skill does.
---

# My Skill

Instructions for the agent...
```

See [SKILL-TEMPLATE.md](SKILL-TEMPLATE.md) for a complete template.

## Why SkillsChest?

- **Open & Community-Driven** — Anyone can contribute skills
- **Cross-Platform** — Works with Claude Code, OpenCode, Codex, Cursor, and more
- **Quality Curated** — PRs reviewed for usefulness and safety
- **Apache 2.0** — Free to use, modify, and distribute

## Resources

- [Agent Skills Spec](https://agentskills.io/)
- [Creating Custom Skills](https://support.claude.com/en/articles/12512198-creating-custom-skills)
- [Understanding Agents](https://github.com/Bitplanet-L1/genie-architecture/tree/main/understanding-agents)

## License

Apache 2.0 — See [LICENSE](LICENSE)

---

Built by [Bitplanet](https://bitplanet.ai) · Powering [Deva](https://deva.me)
