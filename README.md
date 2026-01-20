# Claude Skills

Open-source skills that extend Claude's capabilities with specialized knowledge and workflows. These are skills I have made for myself and use in my workflow to make my habits and routines exceptional.

## What Are Skills?

Skills are modular packages that give Claude procedural knowledge for specific tasks. Instead of figuring things out from scratch, Claude follows proven frameworks and workflows.

Each skill contains:
- **SKILL.md** - Instructions and workflows Claude follows
- **README.md** - Human-readable documentation

## Available Skills

| Skill | Description |
|-------|-------------|
| [dan-koe](./skills/dan-koe) | Channel Dan Koe's philosophy and frameworks. Main orchestrator with 10 sub-skills for one-person business, content creation, focus, and more. |
| [articulation](./skills/articulation) | Framework for articulating ideas intelligently in writing and speaking. Based on Dan Koe's methods. |

## Installation

### Claude Code
```bash
# Clone the repo
git clone https://github.com/kluless13/claude-skills.git

# Copy skills to your skills directory
cp -r claude-skills/skills/* ~/.claude/skills/
```

### Cowork Mode / Claude Desktop

1. Download the skill folder you want
2. Place it in your workspace's `.skills/skills/` directory
3. The skill triggers automatically based on context

## Usage

Once installed, skills trigger automatically. For example, the articulation skill activates when you:
- Ask Claude to write a post or thread
- Prepare for a podcast or presentation
- Need to explain a complex idea clearly

## Skill Structure
```
skills/
└── skill-name/
    ├── SKILL.md      # Required - metadata + instructions
    └── README.md     # Optional - documentation
```

## Contributing

Want to add a skill? 

1. Fork this repo
2. Create your skill folder in `skills/`
3. Add `SKILL.md` with proper frontmatter
4. Add a `README.md` for documentation
5. Submit a PR

### SKILL.md Template
```yaml
---
name: your-skill-name
description: |
  What the skill does.

  TRIGGERS:
  - When this skill should activate
  - Specific phrases or contexts

  CAPABILITIES:
  - What it can do
---

# Your Skill Name

Instructions for Claude to follow...
```

## License

MIT

## Author

[@kluless13](https://github.com/kluless13)
