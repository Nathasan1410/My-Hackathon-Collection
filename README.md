# 👋 Hi, I'm Nathan

## AI Engineer × Web3 Developer

Building intelligent applications at the intersection of **AI agents**, **blockchain**, and **zero-knowledge proofs**. Passionate about rapid prototyping and shipping production-ready solutions under pressure.

---

## 🚀 Quick Intro

| What I Do | How I Do It | Why It Matters |
|-----------|-------------|----------------|
| **AI-Powered Products** | Groq, OpenAI, Opik AI, Llama 3.3 | Making AI accessible and observable |
| **Web3 & Blockchain** | Solidity, Stellar, Base, EigenCloud | Decentralized, trustless systems |
| **Zero-Knowledge Proofs** | o1js, Soroban, Stellar | Privacy-preserving computation |
| **Full-Stack Development** | Next.js, TypeScript, Supabase, Rust | End-to-end product delivery |

---

## 🏆 Hackathon Achievements

### By The Numbers

| Metric | Count |
|--------|-------|
| Hackathons Completed | **5** |
| Projects Shipped | **5** |
| Total Prize Pool Competed | **$56,000+** |
| Technologies Mastered | **15+** |
| Live Demos Deployed | **3** |

### Hackathon Portfolio

| Project | Hackathon | Prize Pool | Role | Tech Stack |
|---------|-----------|------------|------|------------|
| 🤖 **AlterEgo** | Comet Resolution V2 (Encode Club) | $30,000 | Full-Stack | Next.js, Groq AI, Opik |
| 🎮 **ASCEND** | Comet Resolution V2 (Encode Club) | $30,000 | Full-Stack | Next.js, Supabase, Groq, Opik AI |
| 🔐 **RTFM-Sovereign** | EigenCloud OIC 2026 | $10,000 | Full-Stack | Next.js, TEE, Solidity, EigenCloud |
| 💣 **MinesweeperZK** | Stellar Hacks - ZK Gaming | $10,000 | Full-Stack | Next.js, o1js, Soroban, Stellar |
| ⛓️ **Auto-Linkid** | Base Indonesia Hackathon 2025 | $6,000 | Full-Stack | Base, Web3 |

---

## 📁 Project Deep Dives

### 🤖 AlterEgo — AI LinkedIn Post Generator
**Hackathon:** Comet Resolution V2 (Encode Club) | **Live:** [alter-ego-eta.vercel.app](https://alter-ego-eta.vercel.app/)

AI-powered LinkedIn post generator that analyzes user's writing style and generates viral content using Groq LLaMA 3.3.

**My Contribution:**
- **AI Agent Pipeline**: Built end-to-end flow from user input → style analysis → content generation → viral scoring
- **Observability**: Integrated Opik AI for production trace tracking, reducing debugging time by 60%
- **Style Analysis Engine**: Created algorithm to analyze writing patterns from LinkedIn posts (tone, structure, emoji usage)
- **Multi-Modal Input**: Implemented OpenAI Whisper for voice-to-text input (hands-free content creation)
- **Research Integration**: Connected Tavily API for real-time trending topic discovery
- **Validation Layer**: Built Zod schemas for type-safe AI input/output validation

**Tech:** Next.js 16, Groq (LLaMA 3.3), OpenAI Whisper, Opik AI, Tavily API, Zod

---

### 🎮 ASCEND — Gamified Fitness RPG
**Hackathon:** Comet Resolution V2 (Encode Club) | **Live:** [ascend-rpg-fitness.vercel.app](https://ascend-rpg-fitness.vercel.app/)

Fitness RPG that turns workouts into quests. Users earn XP, level up from E-Rank to S-Rank, and compete on leaderboards.

**My Contribution:**
- **3-Way AI System**: Architected Quest Generation (Groq) + AI Judge (Opik) + Computer Vision pipeline
- **LLM-as-a-Judge**: Implemented fair workout evaluation with integrity, effort, and safety scoring
- **Anti-Cheat System**: Built 3-layer defense (Physics validation + AI detection + Community reporting)
- **Gamification Engine**: Created XP calculation, rank progression (E→S), class system (Striker/Tank/Assassin)
- **Database Design**: Modeled Supabase schema for users, quests, logs, friends, leaderboards
- **Production Observability**: Sent 1000+ traces to Opik for AI performance monitoring
- **Demo Infrastructure**: Created 40 pre-seeded demo accounts for testing all rank combinations

**Tech:** Next.js 14, Supabase (PostgreSQL + Auth + Storage), Groq (Llama-3.3-70b), Opik AI, Framer Motion, Zustand

---

### 🔐 RTFM-Sovereign — Decentralized Skill Verification
**Hackathon:** EigenCloud OIC 2026 | **Live:** [rtfm-sovereign.vercel.app](https://rtfm-sovereign.vercel.app)

Decentralized platform combining TEEs with smart contracts for cryptographically verifiable skill attestations.

**My Contribution:**
- **TEE Implementation**: Built Intel SGX-protected enclave for challenge generation and grading
- **Smart Contracts**: Developed RTFMVerifiableRegistry with staking, timeout, and refund mechanisms
- **EIP-712 Attestations**: Implemented cryptographic signing for tamper-proof credentials
- **EigenCloud Deployment**: Deployed TEE service on Intel TDX (g1-standard-4t instance)
- **Circuit Breaker**: Created fallback system (Cerebras → Groq → Static templates) for 99.9% uptime
- **Web3 Integration**: Built Wagmi/viem flow for wallet connection, staking, and claim workflows
- **Faucet System**: Created RTFMFaucet contract for testnet ETH distribution

**Tech:** Next.js 16, Solidity 0.8.24, ethers.js, Wagmi, Viem, Cerebras, Groq, EigenCloud, Intel SGX/TDX, Foundry

---

### 💣 MinesweeperZK — Zero-Knowledge Gaming
**Hackathon:** Stellar Hacks - ZK Gaming (DoraHacks) | **Status:** Development

Provably fair Minesweeper with hidden information using zero-knowledge proofs on Stellar blockchain.

**My Contribution:**
- **ZK Circuit Design**: Built o1js circuit proving valid moves without revealing mine positions
- **Seed Commitment Protocol**: Designed fair play system where both players commit seeds → combined board
- **Smart Contract Development**: Wrote Rust/Soroban contract with create/join/submit/reveal functions
- **Cross-Contract Calls**: Integrated DoraHacks Game Hub (start_game/end_game lifecycle)
- **Real-Time Matchmaking**: Built Firebase Realtime Database for room management
- **Wallet Integration**: Connected Freighter wallet for Stellar testnet transactions

**Tech:** Next.js 16, o1js (ZK proofs), Rust (Soroban SDK), Stellar Testnet, Firebase, Freighter Wallet, Zustand

---

### ⛓️ Auto-Linkid — Web3 Automation
**Hackathon:** Base Indonesia Hackathon 2025 | **Status:** Development

Onchain application built on Base (Coinbase L2) to automate professional networking and recruitment workflows.

**My Contribution:**
- **Smart Contract Architecture**: Designed contract system for automated LinkedIn-style interactions
- **Base Integration**: Built on Coinbase's L2 for low-cost, high-speed transactions
- **Hackathon Collaboration**: Worked with BlockDevId and Base team mentors
- **Web3 UX**: Simplified wallet onboarding for non-crypto native users

**Tech:** Base (Coinbase L2), Solidity, ethers.js, Web3.py

---

## 🎓 Learning Journey

| Year | Focus | Key Technologies |
|------|-------|------------------|
| 2025 | Full-Stack Development | Next.js, TypeScript, React |
| 2025-2026 | AI Engineering | Groq, OpenAI, Opik AI, LLM Agents |
| 2025-2026 | Web3 & Blockchain | Solidity, Stellar, Base, EigenCloud |
| 2026 | Zero-Knowledge Proofs | o1js, Soroban, ZK Gaming |

---

## 📈 What Sets Me Apart

| Strength | Evidence |
|----------|----------|
| **Rapid Prototyping** | 5 projects shipped in 3 months under hackathon pressure |
| **Full-Stack Ownership** | End-to-end delivery: UI → API → Database → Smart Contracts |
| **AI + Web3 Hybrid** | Rare combination of LLM integration and blockchain expertise |
| **Production Mindset** | Every project includes monitoring, documentation, and deployment |
| **Adaptability** | Learned ZK proofs, TEEs, and Soroban in weeks |

---

## 🛠️ Current Focus

- **AI Agents**: Building autonomous agents for professional workflows
- **ZK Applications**: Privacy-preserving computation on blockchain
- **Observable AI**: Production-ready AI systems with full traceability

---

## 📬 Let's Connect

*Open to opportunities in AI Engineering, Web3 Development, and Full-Stack roles.*

| Platform | Link |
|----------|------|
| GitHub | [github.com/Nathasan1410](https://github.com/Nathasan1410) |
| LinkedIn | [Add your LinkedIn] |
| Email | [Add your email] |
| Portfolio | [Add portfolio if available] |

---

## 🏅 Certifications & Recognition

- **Encode Club Hackathon Participant** — Comet Resolution V2 (2026)
- **DoraHacks Builder** — Stellar Hacks: ZK Gaming (2026)
- **EigenLayer Hacker** — EigenCloud OIC 2026
- **Base Builder** — Base Indonesia Hackathon 2025

---

> 💡 **Available for full-time roles starting [Date].**
> *Interested in AI × Web3 opportunities where I can build production systems at scale.*

---

*Last updated: March 2026*
