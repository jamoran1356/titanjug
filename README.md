<div align="center">

```
████████╗██╗████████╗ █████╗ ███╗   ██╗
╚══██╔══╝██║╚══██╔══╝██╔══██╗████╗  ██║
   ██║   ██║   ██║   ███████║██╔██╗ ██║
   ██║   ██║   ██║   ██╔══██║██║╚██╗██║
   ██║   ██║   ██║   ██║  ██║██║ ╚████║
   ╚═╝   ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝
     ██╗██╗   ██╗ ██████╗  ██████╗ ███████╗██████╗ ███╗   ██╗ █████╗ ██╗   ██╗████████╗
     ██║██║   ██║██╔════╝ ██╔════╝ ██╔════╝██╔══██╗████╗  ██║██╔══██╗██║   ██║╚══██╔══╝
     ██║██║   ██║██║  ███╗██║  ███╗█████╗  ██████╔╝██╔██╗ ██║███████║██║   ██║   ██║
██   ██║██║   ██║██║   ██║██║   ██║██╔══╝  ██╔══██╗██║╚██╗██║██╔══██║██║   ██║   ██║
╚█████╔╝╚██████╔╝╚██████╔╝╚██████╔╝███████╗██║  ██║██║ ╚████║██║  ██║╚██████╔╝   ██║
 ╚════╝  ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝ ╚═════╝    ╚═╝
```

### **The Security Layer Web3 Infrastructure Has Been Missing**

[![Next.js](https://img.shields.io/badge/Next.js-16.2-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Solidity](https://img.shields.io/badge/Solidity-0.8-363636?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com)
[![Arbitrum](https://img.shields.io/badge/Arbitrum-One-28A0F0?style=for-the-badge&logo=arbitrum&logoColor=white)](https://arbitrum.io)

[![Status](https://img.shields.io/badge/Status-Active%20Development-22c55e?style=flat-square)](https://www.titanjug.com)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://www.titanjug.com)
[![Website](https://img.shields.io/badge/Website-titanjug.com-6366f1?style=flat-square)](https://www.titanjug.com)

</div>

---

## ⚡ What Is TITAN?

**TITAN Juggernaut** is a production-grade SaaS security platform designed to protect DeFi bridges, cross-chain protocols, and on-chain infrastructure from real-time exploits.

DeFi bridges have lost **over $2.5 billion** to exploits in the last 3 years. Reentrancy attacks, oracle manipulation, flash loan cascades, anomalous withdrawal patterns — all detectable with the right behavioral intelligence layer.

TITAN is that layer.

> _"Web3 does not fail because of lack of innovation. It fails when infrastructure cannot be trusted."_

---

## 🔥 Core Capabilities

| Capability | Details |
|---|---|
| ⚡ **Real-Time Detection** | 40ms average detection latency across the monitoring cluster |
| 🧠 **Behavioral Oracle** | 4-layer anomaly engine: Behavioral → Risk → Response → War Mode |
| 🔥 **Risk Firewall** | Graduated response system — alert, throttle, pause, emergency stop |
| 🔍 **Smart Contract Auditor** | Static analysis engine with 21 vulnerability detection rules |
| 🐙 **GitHub Audit** | Scans entire Solidity repositories via GitHub API in seconds |
| 🛡️ **Shield Simulator** | Transaction-level simulation with threat probability scoring |
| 💳 **Crypto Payments** | Native ETH/USDC payments via TitanPayments.sol on Arbitrum |
| 📊 **Admin Dashboard** | Full SaaS control panel: users, billing, subscriptions, threats |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────────────┐
│                        TITAN JUGGERNAUT                             │
│                    Production SaaS Platform                         │
└──────────────────────────┬──────────────────────────────────────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
   ┌─────────────┐  ┌─────────────┐  ┌──────────────┐
   │  Next.js 16 │  │  REST API   │  │  Smart       │
   │  App Router │  │  (45 routes)│  │  Contracts   │
   │  React 19   │  │  JWT Auth   │  │  Arbitrum    │
   └──────┬──────┘  └──────┬──────┘  └──────┬───────┘
          │                │                │
          └────────────────┼────────────────┘
                           ▼
              ┌────────────────────────┐
              │   PostgreSQL 16        │
              │   Prisma ORM           │
              │   (Users · Plans ·     │
              │    Invoices · Bridges  │
              │    Subscriptions ·     │
              │    Threats · Alerts)   │
              └────────────────────────┘
```

### Detection Engine Layers

```
Layer 1 — BEHAVIORAL ORACLE
  └─ Transaction pattern analysis, baseline deviation scoring

Layer 2 — RISK FIREWALL
  └─ Graduated risk scoring (0–100), configurable thresholds

Layer 3 — GRADUATED RESPONSE
  └─ Alert → Throttle → Pause → Emergency Stop

Layer 4 — WAR MODE
  └─ Full lockdown, fund isolation, incident response pipeline
```

---

## 🛠️ Tech Stack

### Frontend & Framework
- **Next.js 16.2** — App Router, Server Components, API Routes
- **React 19** — Latest concurrent features
- **TypeScript 5** — Strict mode throughout
- **Tailwind CSS 4** — Utility-first styling
- **Framer Motion** — Smooth UI animations
- **Recharts** — Real-time dashboard charts

### Backend & Database
- **PostgreSQL 16** — Primary datastore
- **Prisma 7** — Type-safe ORM with migrations
- **Jose** — JWT authentication (RS256)
- **Zod 4** — Runtime schema validation
- **bcryptjs** — Password hashing

### Blockchain
- **Solidity 0.8** — 6 production smart contracts
- **Hardhat 3** — Development, testing, deployment
- **Ethers.js 6** — On-chain interaction
- **Arbitrum One** — Primary deployment network
- **Arbiscan API** — Transaction verification

### Infrastructure
- **Docker + Docker Compose** — Containerized stack
- **Nginx** — Reverse proxy
- **Cloudflare** — CDN + DDoS protection
- **pnpm** — Fast, disk-efficient package manager

---

## 📦 Smart Contracts

| Contract | Purpose |
|---|---|
| `TitanPayments.sol` | ETH/USDC invoice payments on Arbitrum |
| `TitanSubscriptions.sol` | On-chain subscription management |
| `TitanObserver.sol` | Bridge state monitoring & anomaly hooks |
| `TitanBunker.sol` | Emergency fund isolation vault |
| `RiskFirewall.sol` | Graduated response enforcement |
| `GraduatedResponse.sol` | Multi-stage incident response pipeline |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 20+
- pnpm 9+
- PostgreSQL 16
- Docker (optional)


## 💰 Pricing Tiers

| Plan | Price | TVL Coverage | Nodes | SLA |
|---|---|---|---|---|
| **Starter** | $10,000/mo | Up to $100M | 6 | 99.9% |
| **Professional** | $25,000/mo | Up to $500M | 15 | 99.95% |
| **Enterprise** | Custom | Unlimited | 30 | 99.99% |

> If TITAN prevents **one** attack — the ROI is infinite.

---

## 🔐 API Overview

### Public Auth
```
POST /api/auth/register        Register a new client
POST /api/auth/login           Authenticate & receive JWT
POST /api/auth/logout          Invalidate session
```

### Client API (JWT Required)
```
GET  /api/client/bridges       List monitored bridges
GET  /api/client/alerts        Active threat alerts
GET  /api/client/anomalies     Detected anomalies
GET  /api/client/subscription  Current subscription status
POST /api/shield/scan          Scan a smart contract address
POST /api/shield/simulate      Simulate a transaction for threats
POST /api/audit/contract       Audit Solidity source code (21 rules)
POST /api/audit/github         Audit a GitHub repository
```

### Payments
```
POST /api/payments/crypto/create-invoice   Create ETH/USDC invoice
POST /api/payments/crypto/verify           Verify on-chain payment
POST /api/payments/paypal/create-order     Create PayPal order
POST /api/payments/paypal/capture          Capture PayPal payment
```

### Admin API (Admin JWT Required)
```
GET|POST         /api/admin/users
GET|PATCH|DELETE /api/admin/users/[id]
GET|POST         /api/admin/plans
GET|PATCH|DELETE /api/admin/plans/[id]
GET|POST         /api/admin/clients
GET|POST         /api/admin/bridges
GET|PATCH|DELETE /api/admin/bridges/[id]
GET              /api/admin/threats
GET|PATCH|DELETE /api/admin/threats/[id]
GET|PATCH        /api/admin/billing
GET|PATCH|DELETE /api/admin/billing/[id]
GET|POST         /api/admin/subscriptions
GET              /api/admin/stats
GET              /api/admin/activities
PATCH            /api/admin/payments/config
GET|PATCH        /api/admin/settings
```

---

## 📊 Detection Rules (Contract Auditor)

The static analysis engine checks Solidity code against **21 vulnerability rules**:

| ID | Rule |
|---|---|
| TJ-001 | Reentrancy — state update after external call |
| TJ-002 | Unchecked return value (call, transfer, send) |
| TJ-003 | tx.origin used for authorization |
| TJ-004 | Integer overflow/underflow risk |
| TJ-005 | Timestamp dependence (block.timestamp) |
| TJ-006 | Unprotected selfdestruct |
| TJ-007 | Delegatecall to untrusted contracts |
| TJ-008 | Default visibility on functions/state |
| TJ-009 | Uninitialized storage pointer |
| TJ-010 | Flash loan attack surface |
| TJ-011 | Oracle price manipulation |
| TJ-012 | Front-running vulnerability |
| TJ-013 | Access control missing |
| TJ-014 | Unprotected ETH withdrawal |
| TJ-015 | Gas limit DoS pattern |
| TJ-016 | Signature replay attack |
| TJ-017 | Centralization risk |
| TJ-018 | Unsafe ERC20 interaction |
| TJ-019 | Cross-chain replay attack |
| TJ-020 | Bridge-specific vulnerabilities |
| TJ-021 | Solidity version risk |

---

## 🌐 Case Studies Covered

The detection models were trained against real-world exploits:

- **Kelp DAO** — $293M TVL, oracle manipulation vector
- **Drift Protocol** — $400M+ exposure, behavioral anomaly pattern
- **Uniswap V3** — TWAP oracle vulnerability window
- **Nexus Bridge** — Cross-chain replay attack surface

---

## 🗺️ Roadmap

- [x] Core SaaS platform (auth, billing, admin panel)
- [x] Smart contract static auditor (21 rules)
- [x] GitHub repository auditor
- [x] Shield scan & simulation engine
- [x] Crypto payment processing (ETH + USDC on Arbitrum)
- [x] On-chain TitanPayments.sol contract
- [ ] Behavioral Oracle v2 — distributed 30-node cluster
- [ ] War Mode — full automated lockdown pipeline
- [ ] Solana network support
- [ ] Telegram / Slack alert webhooks
- [ ] Public API with API key authentication
- [ ] Prediction market protection module
- [ ] SDK for direct DeFi protocol integration

---

## 👤 Founder

<div align="center">

**Jesus Moran**
Technical Founder & Builder

*Venezuela*

[![Website](https://img.shields.io/badge/titanjug.com-6366f1?style=for-the-badge)](https://www.titanjug.com)

</div>

---

<div align="center">

**TITAN Juggernaut** — Built for survivability, not presentation.

*The infrastructure layer that must continue functioning after launch.*

---

© 2026 TITAN Juggernaut. All rights reserved.

</div>
