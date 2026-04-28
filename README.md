<div align="center">

# 🚀 North9

**A venture studio building the infrastructure for a more private, more verifiable, post-classical internet.**

Post-Quantum · Privacy-First · Frontier Science · Auditable Code

[![Web](https://img.shields.io/badge/web-north9.org-blue)](https://north9.org)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)
[![Open Source](https://img.shields.io/badge/open%20source-by%20default-brightgreen)](#)

</div>

---

## What we build

We build companies, not wrappers. When a product needs new cryptography, new transport stacks, new operating systems, or new ways to simulate physics — we *build that*. Not an API on top of it. We start with a hard problem the existing toolchain can't solve, develop the toolchain, ship the product, and spin it out as an independent company.

Our work spans **four research threads**: post-quantum infrastructure, provable media authenticity, frontier quantum simulation, and privacy-first consumer software. AI shows up across all of them — as a tool, as a threat model, and as a deployment target.

---

## Projects by thread

### 🔐 Post-Quantum Infrastructure

Cryptography and transport for the quantum-era Internet.

| Project | Language | Status | Headline |
|---|---|---|---|
| **[Apex Protocol](https://github.com/North9LLC/Apex)** | Rust | ✅ Prod | **568 MiB/s** encrypted throughput + ML-KEM768 + 247 µs handshake. Multi-stream, priority-scheduled, built-in FEC. |
| **[Ape](https://github.com/North9LLC/Ape)** | Rust | ✅ Prod | Post-quantum encrypted reverse tunnels. Hybrid X25519 + ML-KEM768 with adaptive congestion control and forward error correction. |

### 📸 Media Authenticity

Cryptographic proof that digital media is real.

| Project | Language | Status | Headline |
|---|---|---|---|
| **[Signet](https://github.com/North9LLC/Signet)** | iOS/Kotlin + C | ✅ Released | Photo watermarking SDK. Unforgeable shutter-time proof from drand beacon. Binary verification, public, non-interactive. |

### 🌐 Privacy-First Consumer

Zero-tracking, zero-log, zero-cloud consumer products.

| Project | Language | Status | Headline |
|---|---|---|---|
| **[Relay](https://github.com/North9LLC/Relay)** | Next.js + TS | ✅ Prod | End-to-end encrypted messenger for high-trust networks. Per-message ephemeral keys, 20-min TTL, encrypted-only storage, no social graph. |
| **[North9 Search](https://github.com/North9LLC/Search)** | Next.js 16 | ✅ Prod | Privacy-first metasearch. Zero tracking, zero logs, zero cookies. Aggregates Brave, Mojeek, DDG, Wikipedia with instant answers. |
| **[NorthUSB](https://github.com/North9LLC/NorthUSB)** | JS/Rust CLI | ✅ Prod | Encrypted vault on USB. Passwords, TOTP, SSH keys, notes — all client-side AES-256-GCM. No server, no network. |
| **[North9 Black](https://github.com/North9LLC/North9Black)** | Next.js + TS | ✅ Prod | Premium security membership. Post-quantum infrastructure, member provisioning, threat intelligence for founders under real threat. |
| **[NorthOS](https://github.com/North9LLC/NorthOS)** | Kotlin | 🚀 Alpha | GrapheneOS fork for high-threat environments. Three configurable security tiers, 27+ defensive apps, IMSI-catcher detection, zero Google. |

### 🧮 Frontier Quantum

Quantum simulation and quantum-native applications.

| Project | Language | Status | Headline |
|---|---|---|---|
| **[qRoute](https://github.com/North9LLC/qRoute)** | Python 3.11+ | ✅ v0.1.0 | Hybrid quantum simulator. Exact expectation values on **200–1000+ qubit** circuits without approximation or GPU. Auto-routes to optimal backend. On PyPI. |

### 🤖 AI Infrastructure

Self-hosted agents and intelligence platforms.

| Project | Language | Status | Headline |
|---|---|---|---|
| **[Agent](https://github.com/North9LLC/Agent)** (Loop) | Next.js + Fastify | 🚀 Phase 2 | Self-hosted AI agent. Chat UI, WebSocket streaming, tool execution, session history via Redis. Phase 1 done; Phase 2 adds Docker sandboxing. |
| **[Lantern](https://github.com/North9LLC/lantern)** | Next.js + TS | ✅ Prod | Ad intelligence platform. Monthly competitor analysis + 4 ready-to-launch creative recommendations for invite-only brands. |

---

## Why North9?

| Principle | What it means |
|---|---|
| **Build the hard part first** | New crypto? New transport? New kernel patches? We build it — not a wrapper. |
| **Open source by default** | Most work ships under MIT. Trust comes from auditable code, not marketing. |
| **Cross-validated, never homegrown** | Quantum backends checked against Qiskit to 1e-10. Crypto built on `@noble/*`, `ring`, drand, standards — zero custom crypto. |
| **Real threat models** | Products are built for people and organizations under actual threat, not hypothetical risk. |
| **No nonsense** | Docs say what something *is*, what it *isn't*, and what its *limits* are. Same applies to how we talk about the company. |

---

## Tech stack by thread

```
Post-Quantum Infrastructure
  └─ Rust (Apex, Ape) + Noise_XX + ML-KEM768 + ChaCha20-Poly1305
  
Media Authenticity
  └─ iOS/Kotlin + C/C++ (Signet) + drand beacon + BLS signatures
  
Privacy-First
  ├─ Next.js + TypeScript (Relay, Search, North9Black)
  ├─ Browser + Rust CLI (NorthUSB)
  └─ Android/Kotlin (NorthOS)
  
Frontier Quantum
  └─ Python 3.11+ + NumPy (qRoute)
  
AI Infrastructure
  └─ Next.js + TypeScript + Fastify + PostgreSQL (Agent, Lantern)
```

---

## Get in touch

- **Web** — [north9.org](https://north9.org)
- **Membership** — [north9.org/become-member](https://north9.org/become-member)
- **Contact** — [north9.org/contact](https://north9.org/contact)

Building at the frontier? Privacy infrastructure, post-quantum systems, applied quantum, AI-native products? Let's talk.

---

## Contributing

All repositories are **open source under MIT**. Issues and PRs are welcome.

**Before contributing:**
- Review the project's README for contribution guidelines
- Check existing issues to avoid duplicate work
- For security/crypto: discuss large changes in issues first (audit-first approach)

Code audits and security reports are welcome.

---

<div align="center">

**Built with care · North9 LLC**

[GitHub](https://github.com/North9LLC) · [Web](https://north9.org)

</div>

<!--
This file lives at `README.md` in the `North9LLC/.github` repo
and renders as the public landing page at github.com/North9LLC.
Last updated: April 2026
-->
