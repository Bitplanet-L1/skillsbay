# Contributing to SkillsChest

Thanks for contributing! This guide will help you add skills that benefit the AI agent community.

## Before You Start

- Ensure your skill solves a **real problem** (not hypothetical)
- Search existing skills to avoid duplicates
- Test your skill with at least one agent (Claude Code, OpenCode, etc.)

## Skill Requirements

All skills must:

1. **Solve a real problem** — Based on actual usage, not theoretical applications
2. **Be well-documented** — Clear instructions, examples, and use cases
3. **Be safe** — Confirm before destructive operations
4. **Be tested** — Verify it works across agents
5. **Be original** — Don't copy skills from other repos without attribution

## Skill Structure

```
skills/
└── my-skill/
    ├── SKILL.md          # Required: Main skill instructions
    ├── scripts/          # Optional: Helper scripts
    ├── references/       # Optional: Reference documentation
    └── assets/           # Optional: Templates, images, etc.
```

## SKILL.md Format

```markdown
---
name: my-skill
description: One-sentence description. Include trigger phrases like "use when X" or "helps with Y".
---

# Skill Name

What this skill does and why it's useful.

## When to Use

- Trigger phrase 1
- Trigger phrase 2
- Use case 1

## How It Works

Step-by-step explanation...

## Examples

### Basic Usage

```
Example prompt
```

### Advanced Usage

```
More complex example
```

## Tips

- Tip 1
- Tip 2
```

## Pull Request Process

### 1. Fork & Clone

```bash
gh repo fork Bitplanet-L1/skillschest --clone
cd skillschest
```

### 2. Create Your Skill

```bash
mkdir -p skills/my-skill
# Create SKILL.md with your content
```

### 3. Add to README

Add your skill to the appropriate category table in README.md:

```markdown
| [my-skill](./skills/my-skill/) | Description of what it does. |
```

### 4. Submit PR

```bash
git checkout -b add-my-skill
git add .
git commit -m "feat: add my-skill"
git push origin add-my-skill
gh pr create
```

## PR Guidelines

Your PR should include:

- **Title:** `feat: add <skill-name>` or `fix: update <skill-name>`
- **Description:**
  - What problem it solves
  - Who benefits from it
  - How you tested it

## Quality Standards

### Good Skills

✅ Solves a specific, real problem  
✅ Clear trigger phrases in description  
✅ Tested with actual agents  
✅ Includes practical examples  
✅ Safe defaults (confirms destructive actions)  

### Avoid

❌ Overly generic instructions  
❌ Hypothetical use cases  
❌ Copy-paste from other repos without attribution  
❌ Skills that require external API keys without clear setup  
❌ Unsafe operations without confirmation  

## Categories

Add your skill to the appropriate category:

| Category | For Skills That... |
|----------|-------------------|
| Agent & Collaboration | Improve agent behavior, human-AI interaction |
| Development | Help with coding, testing, deployment |
| Productivity | Organize, automate, streamline work |
| Creative | Design, content creation, media |
| Data & Analysis | Process, analyze, visualize data |
| Communication | Writing, messaging, documentation |

## License

By contributing, you agree to license your skill under Apache 2.0.

## Questions?

Open an issue if you have questions or need help structuring your skill.

---

Thank you for contributing to SkillsChest! 🎉
