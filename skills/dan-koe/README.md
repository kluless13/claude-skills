# Dan Koe Advisor

Channel Dan Koe's philosophy, frameworks, and advice style. The "Dan Koe brain" for creators, solopreneurs, and those building a one-person business.

## Installation

### Claude Code CLI

1. **Locate your Claude skills directory**
   ```bash
   # Create the skills directory if it doesn't exist
   mkdir -p ~/.claude/skills
   ```

2. **Copy the dan-koe skill and all sub-skills**
   ```bash
   # From the claude-skills repo root
   cp -r skills/dan-koe ~/.claude/skills/

   # Also copy all the sub-skills to the root skills folder
   # (Claude Code needs them at the top level)
   cp -r skills/dan-koe/skills/* ~/.claude/skills/
   ```

3. **Verify installation**
   ```bash
   ls ~/.claude/skills/
   # Should show: dan-koe, 3-levels-of-money, articulation, dead-internet, etc.
   ```

### Alternative: Symlink (keeps skills synced with repo)

```bash
# Symlink the main skill
ln -s /path/to/claude-skills/skills/dan-koe ~/.claude/skills/dan-koe

# Symlink each sub-skill
for skill in human-3 3-levels-of-money articulation dead-internet ai-usage advertising dopamine-detox deep-focus 24-months-skills one-person-business multiple-interests; do
  ln -s /path/to/claude-skills/skills/dan-koe/skills/$skill ~/.claude/skills/$skill
done
```

### Claude Desktop / Cowork Mode

1. Create a `.skills/skills/` directory in your workspace
2. Copy `dan-koe/` and all its sub-skills into that directory
3. Skills trigger automatically based on conversation context

## Verifying It Works

After installation, start Claude Code and run:
```
/dan-koe
```

Or just ask a question that triggers it:
- "How do I start a one-person business?"
- "I have too many interests, how do I pick a niche?"
- "How should I think about money?"

## Overview

This is a modular skill system that captures Dan Koe's thinking across his major articles and frameworks. The main skill acts as an orchestrator that routes to specialized sub-skills based on the user's question.

## Structure

```
dan-koe/
├── SKILL.md              # Main orchestrator
├── README.md             # This file
└── skills/
    ├── human-3/              # HUMAN 3.0 - Comprehensive life framework (4 quadrants)
    ├── 3-levels-of-money/    # Money mindset, escaping wage slavery
    ├── dead-internet/        # Standing out, value vs slop, taste
    ├── articulation/         # Writing & speaking frameworks
    ├── ai-usage/             # Using AI effectively
    ├── advertising/          # Marketing & persuasion
    ├── dopamine-detox/       # 30-day reset protocol
    ├── deep-focus/           # Focus & flow states
    ├── 24-months-skills/     # Skills for the AI age
    ├── one-person-business/  # Building solo business
    └── multiple-interests/   # Generalist advantage
```

## When to Use

Invoke the main `dan-koe` skill when user:
- Wants advice on one-person business or creator economy
- Asks about content creation, writing, or building an audience
- Needs help with positioning, niche, or personal branding
- Wants guidance on escaping the 9-5
- Asks about AI for creators
- Is struggling with multiple interests or feeling stuck
- Asks about focus, productivity, or dopamine detox
- Needs help with advertising or persuasion

## Sub-Skills

| Skill | Based On | Use When |
|-------|----------|----------|
| `human-3` | "HUMAN 3.0 - A Map To Reach The Top 1%" | Comprehensive life development, feeling stuck despite success |
| `3-levels-of-money` | "The 3 Levels Of Money" | Money mindset, wage slavery escape |
| `dead-internet` | "How to stand out in the dead internet" | Standing out online, content saturation |
| `articulation` | "How to articulate yourself intelligently" | Writing, explaining ideas, speaking |
| `ai-usage` | "How to use AI better than 99%" | AI workflows, prompting, tool usage |
| `advertising` | "Every ambitious person must learn this skill" | Marketing, persuasion, selling |
| `dopamine-detox` | "A dopamine detox to reset your life" | Feeling stuck, need to reset |
| `deep-focus` | "How to become so focused it feels illegal" | Focus, productivity, flow states |
| `24-months-skills` | "You have about 24 months to learn these skills" | Future-proofing, AI adaptation |
| `one-person-business` | "How I'd build a one-person business" | Starting solo business |
| `multiple-interests` | "If you have multiple interests" | Can't pick niche, too many interests |

## Core Philosophy

Dan Koe's worldview in brief:
- The individual has more power than ever (digital leverage + AI)
- Multiple interests are an advantage, not a weakness
- Development > Skills (solve problems at your level to see next level)
- Work should feel like play when aligned with life's work
- The goal is Sacred money (energy), not Survival or Success money

## Voice & Style

When using these skills, channel Dan Koe's voice:
- **Tone**: Direct, philosophical but practical, anti-conformist
- **Structure**: Deep dives, interconnected ideas
- **Perspective**: Fellow traveler, not guru
- **Energy**: Challenge conventional wisdom, remain warm

## Source Articles

All frameworks extracted from Dan Koe's newsletter "future/proof" at [letters.thedankoe.com](https://letters.thedankoe.com)

## Credits

Based on the writing and thinking of [Dan Koe](https://thedankoe.com).
