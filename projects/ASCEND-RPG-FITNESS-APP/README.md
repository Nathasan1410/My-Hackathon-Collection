# ASCEND: Fitness RPG

> **Hackathon**: Comet Resolution V2 (Encode Club) - "Commit To Change"
> **Date**: December 2025 - February 2026
> **Status**: Participant
> **Theme**: AI Agents for New Year's Resolutions

## Overview

**ASCEND: Fitness RPG** is a gamified fitness application inspired by Solo Leveling, where everyday workouts become RPG quests that earn you XP, unlock ranks, and build real physical strength. Turn workouts into epic quests, level up your character, and become the strongest hunter.

### Core Gameplay Loop

1. **Generate Quest** - AI creates personalized workout based on your rank, class, equipment, and time
2. **Execute Quest** - Complete exercises with timer, RPE tracking, and optional proof uploads
3. **AI Judge Evaluation** - Opik AI evaluates performance fairly and consistently
4. **Earn XP & Level Up** - Receive XP based on effort, integrity, and completion quality
5. **Rank Up** - Unlock new abilities and harder challenges (E-Rank to S-Rank)

## Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | Next.js 14 (App Router) | React framework with server components |
| Styling | Tailwind CSS + Framer Motion | Utility-first CSS + animations |
| Backend | Next.js Server Actions | API endpoints without separate backend |
| Database | Supabase (PostgreSQL) | User data, quests, logs, social features |
| Storage | Supabase Storage | Workout proof media (photos/videos) |
| Auth | Supabase Auth | OAuth and email/password login |
| Quest Generation | Groq (Llama-3.3-70b) | AI-powered workout generation |
| AI Evaluation | Opik AI | LLM-as-a-Judge for fair workout evaluation |
| Monitoring | Opik AI | Traces, metrics, and observability |

## 3-Way AI System

### 1. Quest Generation AI (Groq - Llama-3.3-70b)
Generates personalized workout quests based on user's rank, class, equipment, and goals.

### 2. AI Judge (Opik AI - LLM-as-a-Judge)
Fair, consistent, and unbiased workout evaluation with anti-cheat detection.

### 3. Computer Vision (Planned)
Analyzes workout proof (photos/videos) for form validation.

## Links

- [GitHub Repository](https://github.com/Nathasan1410/ASCEND-RPG-FITNESS-APP)
- [Live Demo](https://ascend-rpg-fitness.vercel.app/)
- [Demo Video](https://youtu.be/berWi_a0w0s)
- [Gitbook Documentation](https://nathasan1410.gitbook.io/ascend-fitness-rpg/)
- [How We Use Opik AI](https://ascend-rpg-fitness.vercel.app/domain/best-of-OPIK)

## Achievements

- Participant in Comet Resolution V2 Hackathon (Encode Club)
- Built a complete gamification system with E-Rank to S-Rank progression
- Implemented 3-layer anti-cheat system (Physics + AI Judge + Community)
- 40+ demo accounts for testing

## Hunter Ranks

| Rank | Quest XP | Features |
|------|----------|----------|
| E-Rank | 100-200 | 2-3 exercises |
| D-Rank | 200-500 | 3-4 exercises |
| C-Rank | 500-1000 | 4-5 exercises |
| B-Rank | 1000-2000 | 5-6 exercises |
| A-Rank | 2000-4000 | 6+ exercises |
| S-Rank | 4000+ | Elite difficulty |

---

*Last Technical Change: 2026-02-09 | Built at Comet Resolution V2 Hackathon*
