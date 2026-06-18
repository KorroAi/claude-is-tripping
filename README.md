# 🔮 Claude Is Tripping v6

**Universal Breakthrough Engine** — 3 agents collide in a structured dialectic. Always presents an idea menu BEFORE iterating. Internal verification. No fluff in the output.

## Architecture

```
Pre-Flight (Trip Guide)
  ├── Domain detection (8 domains)
  ├── Web research (2-3 searches)
  └── Strategic analogy selection

Idea Menu ⭐ NEW v6
  └── 3-4 concept seeds → user picks one

Round 1
  ├── 🔬 Visionary: invents the breakthrough
  ├── 🔍 Destroyer: audits the core assumption
  └── 🏗️ Synthesizer: builds the third way

Checkpoint: any flaw > 7/10?
  ├── No  → Verification → Present
  └── Yes → Round 2

Round 2
  ├── 🔬 Visionary: 10x scale via new domain lens
  ├── 🔍 Destroyer: triple-threat (adoption, incumbent, macro)
  └── 🏗️ Synthesizer: final build

Verification (INTERNAL — never shown)
  ├── Claim audit
  ├── Hidden assumptions
  ├── Counter-evidence
  ├── Bias check
  └── Day-3 blocker

Self-Healing Loop (INTERNAL)
  ├── SHIP_IT → present
  ├── PROCEED_WITH_CAUTION → fix once → present
  └── NEEDS_REWORK → rebuild → re-verify (max 2 loops)
```

## Agent Budget

| Path | Agents |
|------|--------|
| Menu only | 1 |
| Menu + R1 clean | 5 |
| Menu + R1 + R2 | 8 |
| + Self-healing | +2 per heal (max 4) |

## Key Changes in v6

- **Idea Menu** — user picks a seed BEFORE any iteration starts. No more 8-agent trips on unvalidated ideas.
- **Verification 100% internal** — never shown to user. Feeds self-healing loop.
- **Self-healing loop** — NEEDS_REWORK → auto-rebuild → re-verify. User only sees final passing result.
- **No 48h plans or "first step tonight"** — breakthrough only. Pure idea + execution + unfair advantage.
- **51% token reduction** — 596 → 289 lines. Compressed schemas, shortened prompts, merged sections.

## Usage

```
/claude-is-tripping
```

Then describe what you want. Any domain: products, articles, bots, strategies, code, research, tweets, creative.

## Installation

```bash
git clone https://github.com/KorroAi/claude-is-tripping.git ~/.claude/skills/claude-is-tripping
```

## File Structure

```
claude-is-tripping/
├── SKILL.md   # The skill
├── README.md  # This file
└── .gitignore
```

No dependencies. No API keys. Self-contained.
