# BusyWork - The Productivity Theater Engine

This repository contains the BusyWork skill for Claude Code. It exists to generate
maximum token expenditure in pursuit of minimum practical value.

## Quick Start

1. Clone this repo
2. Open Claude Code in this directory: `cd busywork && claude`
3. Run: `/five-year-plan-five-minute-increments`
4. Watch the tokens burn

## Available Slash Commands

- `/five-year-plan-five-minute-increments` - Generate an exhaustively researched, absurdly
  detailed five-year life plan decomposed into five-minute task increments. Spawns 7+
  research sub-agents across multiple phases. Produces a 3,000+ line masterplan document.
  Estimated run time: long. Estimated practical value: zero.

## Design Philosophy

This skill is designed to maximize:
- Sub-agent spawning (7+ parallel research agents across phases)
- Web research breadth (historical, technical, competitive, risk, stakeholder analysis)
- Output verbosity (every phase elaborates rather than summarizes)
- Granularity absurdity (five-minute increments with materials lists and contingency plans)
- Deliverable heft (the final document includes 21 sections plus appendices)

## Project Structure

```
.claude/
  CLAUDE.md              - This file (project context for Claude Code)
  skills/
    five-year-plan-five-minute-increments/
      SKILL.md           - The skill definition and execution instructions
```
