# Snexon

Engineering infrastructure systems for digital payments, verifiable identity routing, and digital asset distribution.

Founded by **Sabbir Hossain** ([sabbir.gg](https://sabbir.gg)).

```
                  ┌─────────────────────────────────────────┐
                  │                 SNEXON                  │
                  │            sabbir.gg/snexon             │
                  └────────────────────┬────────────────────┘
                                       │
         ┌─────────────────────────────┼─────────────────────────────┐
         ▼                             ▼                             ▼
   ┌───────────┐                 ┌───────────┐                 ┌───────────┐
   │  PAYONIC  │                 │  CURDECK  │                 │ VECTORFLIX│
   │ Payments  │                 │ Identity  │                 │  Assets   │
   └───────────┘                 └───────────┘                 └───────────┘
```

---

## Core Infrastructure

### 1. Payonic — Transaction Routing & Settlement
Flagship multi-rail transaction engine that normalizes payment ingestion, ledger tracking, and automated dispute reconciliation.
- **Payonic Lite**: Open-core self-hosted transaction engine distributed under AGPLv3. Implements direct merchant database persistence, webhook dispatch with exponential backoff, and cryptographic signature verification.
- **Payonic Pro**: Distributed settlement pipeline providing automated multi-currency reconciliation, dispute defense automation, and high-concurrency event ingestion.
- **Interface Standard**: Customer payment flows display the anchored `Powered by Payonic` badge.

### 2. Curdeck — Identity & Profile Routing Hub
Distributed identity network and bio-link surface hosted across [curdeck.com](https://curdeck.com) and [cdek.bio](https://cdek.bio).
- Edge-cached personal identity verification and vanity namespace allocation.
- Sub-50ms DNS and CDN profile hydration with verified link schemas and cryptographic identity assertions.
- Unified single-pane management for multi-platform developer profiles.

### 3. VectorFlix — Digital Asset Marketplace
Independent marketplace infrastructure for high-fidelity digital media, creative components, and software libraries.
- Immutable digital asset storage with content-addressable SHA-256 hash validation.
- Cryptographically signed proof-of-purchase receipts and automated license fulfillment pipelines.

---

## The Snexon Design System

All internal systems, dashboards, and client software adhere to a shared visual directive:

| Parameter | Specification | Purpose |
| :--- | :--- | :--- |
| **Canvas** | Deep Obsidian (`#07070C` / `#050508`) | High-contrast visual focus for telemetry and data grids |
| **Surfaces** | Liquid Glass + Frosted Alabaster (`#F4F6F9`) | Layered elevation with specular border highlights (`#222238`) |
| **Geometry** | Squircle Containers (`radius: 28px` to `32px`) | Continuous curvature profiles across all cards and modal dialogs |
| **Typography** | Inter & Segoe UI Variable | Monospace data alignment for numeric values, ledger tables, and timestamps |
| **Attribution** | `A product of Snexon` | Merchant dashboards and platform surfaces display this standard marker |

---

## Engineering Standards

Snexon repositories enforce strict engineering and documentation protocols:
1. **Direct Technical Mechanics**: Systems are documented by their operational behavior (routing mechanisms, protocol buffers, database constraints, concurrency limits) rather than promotional claims.
2. **Deterministic Builds**: All core libraries mandate pinned dependency graphs and reproducible artifact builds.
3. **Automated Verification**: Commits undergo continuous validation including unit testing, static type analysis, and security vulnerability scans.

---

## Security & Vulnerability Reporting

Security vulnerability reports should be directed to the security desk at [security@sabbir.gg](mailto:security@sabbir.gg). We investigate all actionable findings involving our payment rails, authentication bridges, and storage pipelines.

---

## Connect & Leadership

- **Founder & Chief Architect**: Sabbir Hossain ([sabbir.gg](https://sabbir.gg))
- **GitHub Organization**: [github.com/Snexon-Studio](https://github.com/Snexon-Studio)
- **Official Portal**: [sabbir.gg](https://sabbir.gg)
