# busywork

Stressed that your AI agents aren't token-maxxing? BusyWork will give you the illusion of productivity without requiring you to think.

## What It Does

`/five-year-plan-five-minute-increments` is a Claude Code slash command that:

1. Randomly selects one of **ten absurdly specific five-year life plans** (artisanal pencil sharpening, synchronized ant swimming, competitive rock-paper-scissors grandmaster, etc.)
2. Launches **7+ parallel research sub-agents** across five phases to exhaustively research every dimension of the chosen plan (historical context, technical requirements, competitive landscape, risk assessment, stakeholder analysis, resource planning, KPI frameworks)
3. Decomposes the plan from **five years down to five-minute increments** with military precision (annual > quarterly > monthly > weekly > daily > 192 five-minute blocks)
4. Each five-minute block includes: specific task, required materials, expected output, transition notes, motivational micro-affirmation, risk assessment, and contingency plan
5. Produces a **3,000+ line masterplan document** with 21 sections and 4 appendices

## Install

```bash
git clone https://github.com/rickmanelius/busywork.git
cd busywork
claude
```

That's it. The skill auto-loads from `.claude/skills/`. Then run:

```
/five-year-plan-five-minute-increments
```

## What to Expect

- Multiple research phases with parallel sub-agent spawning
- Extensive web searches for historical context and competitive analysis
- A visible task list tracking all phases
- A final `busywork-masterplan.md` file in the repo root
- An estimated reading time report (spoiler: it's long)
- Absolute sincerity throughout. The tone is "McKinsey consultant with unlimited billable hours and zero accountability"

## The Ten Sacred Plans

| # | Plan | Five-Year Goal |
|---|------|---------------|
| 1 | Artisanal Pencil Sharpening | World's foremost expert, 800-page reference guide |
| 2 | Backyard Cloud Cataloging | Proprietary classification system, searchable database |
| 3 | Interpretive Dance Communication | Replace all professional communication with choreography |
| 4 | NYC Subway in Pasta | 1:87 scale, structurally sneeze-resistant |
| 5 | Taxonomy of Beige | 10,000+ named shades with origin stories |
| 6 | Synchronized Ant Swimming | Colony training, miniature aquatic facility |
| 7 | Encyclopedia of Fictional Cheeses | 12 volumes, 3,000+ invented cheeses |
| 8 | Competitive Rock-Paper-Scissors | Grandmaster status, signature psychological routine |
| 9 | Hotel Shampoo Bottle Collection | 195+ countries, museum-quality archival display |
| 10 | Military-Precision Fitted Sheet Folding | Sub-millimeter tolerances, belt-ranking dojo |

## Architecture

```
.claude/
  CLAUDE.md                                          # Project context
  skills/
    five-year-plan-five-minute-increments/
      SKILL.md                                       # The skill (slash command definition)
```

### Execution Flow

```
Phase 0: Random Plan Selection
    |
Phase 1: Domain Deep Dive (3 parallel agents)
    |-- Agent 1: Historical & Cultural Context
    |-- Agent 2: Technical & Skills Requirements
    |-- Agent 3: Competitive Landscape & Market Analysis
    |
Phase 2: Risk Assessment (2 parallel agents)
    |-- Agent 4: Risk & Failure Mode Analysis
    |-- Agent 5: Stakeholder & Social Impact
    |
Phase 3: Strategic Framework (2 parallel agents)
    |-- Agent 6: Resource & Logistics Planning
    |-- Agent 7: Measurement & Accountability Framework
    |
Phase 4: The Great Decomposition
    |-- 4A: 5-Year → Annual
    |-- 4B: Annual → Quarterly (20 quarters)
    |-- 4C: Quarterly → Monthly (60 months)
    |-- 4D: Monthly → Weekly (critical months)
    |-- 4E: Weekly → Daily (the pivotal week)
    |-- 4F: Daily → 192 Five-Minute Increments (the masterpiece)
    |
Phase 5: Synthesis → busywork-masterplan.md (3,000+ lines)
```

## License

MIT - Because even busywork deserves to be free.
