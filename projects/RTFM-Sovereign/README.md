# RTFM-Sovereign

> **Hackathon**: EigenCloud OIC 2026
> **Date**: February 2026
> **Status**: Participant

## Overview

**RTFM-Sovereign** (Read The F*cking Manual - Sovereign Edition) is a decentralized skill verification platform that combines Trusted Execution Environments (TEEs) with immutable smart contracts to provide cryptographically verifiable attestations of user knowledge.

### How It Works

1. **Connect Wallet**: Link your Web3 wallet (MetaMask, WalletConnect)
2. **Select Topic**: Choose a skill area to verify
3. **Stake Funds**: Deposit 0.001 ETH as economic commitment
4. **Generate Challenge**: AI creates a personalized challenge
5. **Complete Challenge**: Answer questions based on documentation
6. **Receive Attestation**: Get cryptographically verified credential stored on-chain

## Key Features

- **TEE-Powered Verification**: Challenges generated and graded in Intel SGX-protected enclaves
- **Cryptographic Attestations**: EIP-712 signed credentials stored on Ethereum blockchain
- **AI-Generated Challenges**: Deterministic generation using Cerebras Llama 3.3 70B
- **Economic Commitment**: 0.001 ETH stake ensures serious participation
- **Circuit Breaker**: Fallback AI providers (Groq + static templates) ensure 99.9% uptime
- **Modern UI**: Next.js 16 with Tailwind CSS, responsive design, PWA support

## Tech Stack

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| Next.js | 16.1.6 | React framework with App Router |
| React | 19.0.0 | UI library |
| TypeScript | 5.7.3 | Type safety |
| Tailwind CSS | 3.4.17 | Styling |
| Wagmi | 2.14.6 | Web3 integration |
| Viem | 2.21.58 | Ethereum client |

### TEE Service
| Technology | Purpose |
|------------|---------|
| Node.js + Express | TEE container service |
| ethers.js | Blockchain interaction |
| Cerebras SDK | AI inference |
| Groq SDK | Fallback AI provider |

### Smart Contracts
| Technology | Purpose |
|------------|---------|
| Solidity 0.8.24 | Smart contract language |
| Foundry | Development framework |
| OpenZeppelin 5.0.0 | Security libraries |

## Links

- [GitHub Repository](https://github.com/Nathasan1410/RTFM-Sovereign)
- [Live Demo](https://rtfm-sovereign.vercel.app)
- [Smart Contract (Sepolia)](https://sepolia.etherscan.io/address/0x7006e886e56426Fbb942B479AC8eF5C47a7531f1)
- [TEE on EigenCloud](https://verify-sepolia.eigencloud.xyz/app/0xaA7EFAfc5BB58198B6d9c93A342a89dF53Cce702)

## Smart Contracts

| Contract | Address | Network |
|----------|---------|---------|
| RTFMVerifiableRegistry | `0x7006e886e56426Fbb942B479AC8eF5C47a7531f1` | Sepolia |
| RTFMFaucet | `0xA607F8A4E5c35Ca6a81623e4B20601205D1d7790` | Sepolia |

## Achievements

- Participant in EigenCloud OIC 2026
- Deployed TEE service on EigenCloud with Intel TDX
- Full EIP-712 attestation system with replay protection
- Comprehensive documentation with architecture diagrams

---

*Made with ❤️ for EigenCloud OIC 2026*
