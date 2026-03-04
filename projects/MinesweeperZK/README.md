# MinesweeperZK

> **Hackathon**: Stellar Hacks - ZK Gaming (DoraHacks)
> **Date**: February 2026
> **Status**: Participant
> **Prize Pool**: $10,000 USD

## Overview

**MinesweeperZK** is a provably fair, competitive Minesweeper game with zero-knowledge proofs on Stellar. Built for the Stellar Hacks: ZK Gaming Hackathon by DoraHacks.

### The Problem

Minesweeper is a game built on **hidden information** — but blockchains are **transparent by design**. If you store a Minesweeper board on-chain, anyone can see exactly where every mine is. **The game is broken before it starts.**

### The Solution

MinesweeperZK solves this with **zero-knowledge proofs**:

1. Both players commit a random seed → combined into a **shared deterministic seed**
2. The board is generated **locally in each player's browser** from that seed (never stored on-chain)
3. Players play the game entirely client-side
4. When finished, the **o1js ZK circuit** generates a cryptographic proof that the player's moves are valid
5. Only the **proof** (not the board) is submitted to the Soroban smart contract
6. The contract verifies the proof mathematically and releases the XLM prize to the winner

**Result:** Provably fair gameplay with hidden information on a fully transparent blockchain.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 16, React 19, TypeScript, Tailwind CSS v4 |
| ZK Proofs | o1js (client-side proof generation) |
| Wallet | Freighter Browser Extension |
| Smart Contract | Rust + Soroban SDK |
| Blockchain | Stellar Testnet |
| Matchmaking | Firebase Realtime Database |
| Deployment | Vercel (frontend), Stellar CLI (contract) |
| State Management | Zustand |

## Game Flow

```
1. Player 1 creates room → stakes 10 XLM
2. Player 2 joins → matches 10 XLM → Hub.start_game() called
3. Both commit random seeds → combined for board generation
4. Players play Minesweeper locally in browser
5. Game ends → o1js generates ZK proof
6. submit_score() on-chain → contract verifies proof
7. reveal_winner() → transfers 20 XLM to winner → Hub.end_game() called
```

## Scoring System

| Parameter | Value |
|-----------|-------|
| Grid Size | 8 × 8 (64 cells) |
| Total Mines | 10 |
| Safe Cells | 54 |
| Max Score | 1,000 |

| Action | Formula | Max Points |
|--------|---------|-----------|
| Revealing safe cells | `(revealed / 54) × 100 × 5` | 500 |
| Correctly flagging mines | `(correct flags / 10) × 100 × 5` | 500 |
| Wrong flag penalty | `-50 per wrong flag` | — |

## Links

- [GitHub Repository](https://github.com/Nathasan1410/MinesweeperZK)
- [Live Demo](TBD - Not working yet)
- [Demo Video](https://youtu.be/bkgbru7fe5Q)
- [Smart Contract](https://stellar.expert/explorer/testnet/contract/CAYB7VTINJMINQVZZIUAOLESAGUWJTRD24VBTY5YHNKONC5ZP5CH2BHT)
- [Game Hub Contract](https://stellar.expert/explorer/testnet/contract/CB4VZAT2U3UC6XFK3N23SKRF2NDCMP3QHJYMCHHFMZO7MRQO6DQ2EMYG)

## Achievements

- Participant in Stellar Hacks: ZK Gaming (DoraHacks)
- Successfully integrated o1js ZK circuits with Soroban smart contracts
- Cross-contract calls to DoraHacks Game Hub
- Complete seed commitment protocol for fair play

---

*Built for Stellar Hacks: ZK Gaming Hackathon 2026*
