# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **showcase/portfolio repository** for hackathon projects. It does not contain runnable code - instead, it documents and links to actual hackathon project repositories.

## Projects

Current projects in this collection:

| Project | Hackathon | Tech Focus | Live Demo |
|---------|-----------|------------|-----------|
| AlterEgo | Comet Resolution V2 (Encode Club) | AI Agents, LinkedIn Content | [alter-ego-eta.vercel.app](https://alter-ego-eta.vercel.app/) |
| ASCEND-RPG-FITNESS-APP | Comet Resolution V2 (Encode Club) | AI + Fitness Gamification | [ascend-rpg-fitness.vercel.app](https://ascend-rpg-fitness.vercel.app/) |
| RTFM-Sovereign | EigenCloud OIC 2026 | TEE, Smart Contracts, EigenCloud | [rtfm-sovereign.vercel.app](https://rtfm-sovereign.vercel.app) |
| MinesweeperZK | Stellar Hacks - ZK Gaming | Zero Knowledge, Soroban, Stellar | TBD |
| Auto-Linkid | Base Indonesia Hackathon 2025 | Web3, Base L2 | TBD |

## Structure

```
My-Hackathon-Collection/
├── projects/
│   ├── _template/              # Template for new projects
│   ├── AlterEgo/               # AI LinkedIn post generator
│   ├── ASCEND-RPG-FITNESS-APP/ # Gamified fitness RPG
│   ├── RTFM-Sovereign/         # Decentralized skill verification
│   ├── MinesweeperZK/          # ZK-powered Minesweeper on Stellar
│   └── Auto-Linkid/            # Base blockchain app
├── assets/                     # Shared images (screenshots, badges, logos)
├── README.md                   # Main page with project table
└── CLAUDE.md                   # This file
```

## Adding a New Project

1. Create folder: `projects/[project-name]/`
2. Create README.md using template from `projects/_template/README.md`
3. Update main README.md table with new entry
4. Add any screenshots to `assets/` or project folder

## Project README Format

Each project README should contain:
- Overview and problem statement
- Solution description
- Tech stack (languages, frameworks, APIs)
- Achievements (prizes, recognition)
- Links (GitHub repo, live demo, Devpost)
- Team members (optional)
- Key learnings

## Commands

No build/test commands - this is a documentation repository. Use standard git workflow:
- `git add .`
- `git commit -m "feat: add [project-name]"`
- `git push`

## Updating Stats

When adding projects, update the stats section in main README.md:
- Total hackathons count
- Projects completed
- Prize pools
