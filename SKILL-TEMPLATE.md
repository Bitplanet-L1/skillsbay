# Skill Template

Copy this template when creating a new skill.

---

```markdown
---
name: skill-name
description: One-sentence description. Include when to use it, e.g., "Use when doing X" or "Helps with Y".
---

# Skill Name

Brief description of what this skill does and the problem it solves.

## When to Use This Skill

- "Trigger phrase 1"
- "Trigger phrase 2"
- When you need to [use case]
- After [context]

## What This Skill Does

1. **Capability 1** — Description
2. **Capability 2** — Description
3. **Capability 3** — Description

## How to Use

### Basic Usage

Explain the simplest way to use this skill.

```
Example prompt or command
```

### Advanced Usage

More complex scenarios or options.

```
Advanced example with options
```

## Output Format

Describe what the skill produces:

```markdown
# Example Output

Your skill's output format...
```

## Examples

### Example 1: [Scenario]

**Input:** "User prompt"

**Output:**
```
What the skill produces
```

### Example 2: [Scenario]

**Input:** "Another prompt"

**Output:**
```
Another output
```

## Tips

- Tip for better results
- Common pitfall to avoid
- Best practice

## Limitations

- What this skill doesn't do
- Edge cases to be aware of

## Related Skills

- [Related Skill 1](link) — How it relates
- [Related Skill 2](link) — How it relates
```

---

## Frontmatter Guidelines

The YAML frontmatter is **critical** for skill discovery:

```yaml
---
name: lowercase-with-hyphens
description: Must include WHAT it does AND WHEN to use it. This is the primary trigger.
---
```

**Good descriptions:**
- "Extract insights from session history. Use when reflecting on agent failures or improving behavior."
- "Generate changelogs from git commits. Use when releasing or documenting changes."

**Bad descriptions:**
- "A useful skill" (too vague)
- "Helps with things" (no trigger)
- "Advanced AI tool" (marketing speak)
