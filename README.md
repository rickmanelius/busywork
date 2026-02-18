# busywork

Stressed that your AI agents aren't token-maxxing? BusyWork will give you the illusion of productivity without requiring you to think.

## What It Does

BusyWork provides multiple Claude Code slash commands, each designed to consume maximum tokens while producing zero actionable value:

### `/five-year-plan-five-minute-increments`

A Claude Code slash command that:

1. Randomly selects one of **ten absurdly specific five-year life plans** (artisanal pencil sharpening, synchronized ant swimming, competitive rock-paper-scissors grandmaster, etc.)
2. Launches **7+ parallel research sub-agents** across five phases to exhaustively research every dimension of the chosen plan (historical context, technical requirements, competitive landscape, risk assessment, stakeholder analysis, resource planning, KPI frameworks)
3. Decomposes the plan from **five years down to five-minute increments** with military precision (annual > quarterly > monthly > weekly > daily > 192 five-minute blocks)
4. Each five-minute block includes: specific task, required materials, expected output, transition notes, motivational micro-affirmation, risk assessment, and contingency plan
5. Produces a **3,000+ line masterplan document** with 21 sections and 4 appendices

### `/emergency-response-plan`

Generates a FEMA-level emergency response plan for a randomly selected mundane household crisis:

1. Randomly selects one of **twelve household emergencies** (running out of coffee, WiFi down 5 minutes, spider in bathroom, TV remote missing, phone at 2% battery, etc.)
2. Launches **5+ parallel sub-agents** across four phases to produce incident command structures, threat assessments, evacuation routes, supply chain analyses, and communications plans
3. Produces a formal **Incident Command System (ICS)** organizational chart with assigned roles for household members, pets, and inanimate objects
4. Generates press releases, social media guidance, and stakeholder talking points for explaining the crisis to coworkers
5. Delivers a comprehensive **After-Action Report** with 90-day improvement plan
6. Final deliverable: `emergency-response-plan.md` (2,000+ lines)

### `/corporate-rebrand`

Produces a Fortune 500 corporate rebrand package for a randomly selected mundane object:

1. Randomly selects one of **fifteen mundane objects** (paperclip, doorstop, rubber duck, toilet plunger, sponge, etc.)
2. Launches **6+ parallel sub-agents** to deliver brand strategy, competitive intelligence, consumer personas, visual identity, and launch campaigns
3. Creates **50+ pages of brand guidelines** including color systems, typography, photography style, sonic identity, and brand scent profiles
4. Designs an **org chart for the 200-person rebrand team** with 40+ unique job titles
5. Produces investor pitch decks, press releases, and a 90-day social media launch campaign
6. Final deliverable: `corporate-rebrand.md` (2,500+ lines)

### `/peer-review`

Generates a rigorous academic peer review of a randomly selected absurd research paper:

1. Randomly selects one of **fifteen absurd paper topics** (Aerodynamic Properties of a Thrown Burrito, Quantum Entanglement Between Matching Socks, Statistical Analysis of Toast Landing Butter-Side Down, etc.)
2. Launches **4+ parallel sub-agents** to reconstruct the manuscript and produce 3 independent reviewer reports
3. Full **Reviewer #2 energy** — demands more experiments, questions every methodology choice, suggests 47 citations (mostly their own)
4. Includes statistical methods review, ethical concerns, and an editorial decision letter
5. Provides an author response template and revision checklist estimating person-hours to address all comments
6. Final deliverable: `peer-review.md` (1,500+ lines)

## Install

```bash
git clone https://github.com/rickmanelius/busywork.git
cd busywork
claude
```

That's it. The skill auto-loads from `.claude/skills/`. Then run any of:

```
/five-year-plan-five-minute-increments
/emergency-response-plan
/corporate-rebrand
/peer-review
```

## What to Expect

- Multiple research phases with parallel sub-agent spawning
- Extensive web searches for historical context and competitive analysis
- A visible task list tracking all phases
- A final `busywork-masterplan.md` file in the repo root
- An estimated reading time report (spoiler: it's long)
- Absolute sincerity throughout. The tone is "McKinsey consultant with unlimited billable hours and zero accountability"

## The Skills

| Skill | What It Does | Sub-Agents | Output Lines |
|-------|-------------|------------|-------------|
| `/five-year-plan-five-minute-increments` | Decomposes an absurd 5-year life plan into 5-minute increments | 7+ | 3,000+ |
| `/emergency-response-plan` | FEMA-level response plan for a mundane household crisis | 5+ | 2,000+ |
| `/corporate-rebrand` | Fortune 500 rebrand package for a mundane object | 6+ | 2,500+ |
| `/peer-review` | Academic peer review of an absurd research paper | 4+ | 1,500+ |

## The Ten Sacred Plans (five-year-plan)

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
      SKILL.md                                       # 5-year plan slash command
    emergency-response-plan/
      SKILL.md                                       # Emergency response slash command
    corporate-rebrand/
      SKILL.md                                       # Corporate rebrand slash command
    peer-review/
      SKILL.md                                       # Peer review slash command
```

### Execution Flows

#### `/five-year-plan-five-minute-increments`

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

#### `/emergency-response-plan`

```
Phase 0: Crisis Selection (12 household emergencies)
    |
Phase 1: Initial Assessment (3 parallel agents)
    |-- Agent 1: Threat Level Assessment & SITREP
    |-- Agent 2: Incident Command Structure
    |-- Agent 3: Historical Precedent Research
    |
Phase 2: Operational Planning (2 parallel agents)
    |-- Agent 4: Evacuation Routes & Resource Deployment
    |-- Agent 5: Supply Chain Analysis & Logistics
    |
Phase 3: Communications (2 parallel agents)
    |-- Agent 6: Communications Plan & Press Releases
    |-- Agent 7: After-Action Report & Recovery Plan
    |
Phase 4: Synthesis → emergency-response-plan.md (2,000+ lines)
```

#### `/corporate-rebrand`

```
Phase 0: Object Selection (15 mundane objects)
    |
Phase 1: Brand Discovery (3 parallel agents)
    |-- Agent 1: Brand Archaeology & Cultural Anthropology
    |-- Agent 2: Competitive Landscape & Market Analysis
    |-- Agent 3: Consumer Insights & Persona Development
    |
Phase 2: Brand Architecture (2 parallel agents)
    |-- Agent 4: Brand Strategy & Positioning
    |-- Agent 5: Visual & Verbal Identity System (50+ pages)
    |
Phase 3: Communications & Launch (3 parallel agents)
    |-- Agent 6: Press & Investor Relations
    |-- Agent 7: Org Design (200-person team, 40+ job titles)
    |-- Agent 8: Social Media Launch Campaign
    |
Phase 4: Synthesis → corporate-rebrand.md (2,500+ lines)
```

#### `/peer-review`

```
Phase 0: Manuscript Selection (15 absurd paper topics)
    |
Phase 1: Manuscript & Editorial (2 parallel agents)
    |-- Agent 1: Manuscript Reconstruction (Abstract → References)
    |-- Agent 2: Editorial Assessment & Statistical Review
    |
Phase 2: Peer Review (3 parallel agents)
    |-- Agent 3: Reviewer #1 — The Methodologist
    |-- Agent 4: Reviewer #2 — The Territorial Expert
    |-- Agent 5: Reviewer #3 — The Interdisciplinary Dreamer
    |
Phase 3: Editorial Synthesis (1 agent)
    |-- Agent 6: Decision Letter & Author Response Template
    |
Phase 4: Synthesis → peer-review.md (1,500+ lines)
```

## License

MIT - Because even busywork deserves to be free.
