# RadioLogger — Roadmap 2025

> Updated: 2025-11-10

## Phase 0 — Organization & Governance (Week 1–2)
- Create **RadioLogger** org (done)
- Create teams & CODEOWNERS (firmware, backend, web, ipfs, data, validator, ai, docs, dao, community)
- Set default community health files in `.github/` (issue/PR templates, SECURITY, CODE_OF_CONDUCT)

## Phase 1 — Foundations (Week 2–6)
- Repo **autologger**: bootstrap folders `backend/`, `firmware/`, `web/`, `ipfs/`, `validator/`, `docs/`
- Define data schemas: QSO log, device identity, validator attestations
- Choose open license (MIT) and contributor guidelines
- CI: lint + build checks per module; basic unit tests

## Phase 2 — MVP (Month 2–3)
- **Firmware**: ESP32-based logger (APRS/GPS/BT), offline queue → IPFS uploader
- **Backend**: API for device registration, signed QSO upload, validation queue
- **IPFS**: pinned content structure, gateway strategy, cluster settings
- **Web**: operator dashboard (login, submit logs, view badges, leaderboard)
- **Validator**: prototype on chosen chain (e.g., BTC L2 / Stacks) for hash anchoring
- Public testnet with seed data, feedback loop

## Phase 3 — Validation & Incentives (Month 4–5)
- Reputation and anti-spam rules (callsign checks, RF heuristics, cross-logs)
- Community verification flows + dispute resolution
- Tokenless incentives (badges/NFT certificates), opt-in sponsor pools

## Phase 4 — Hardening & Scale (Month 6+)
- Observability: metrics, log aggregation, status page
- Edge nodes: more iGate/relay nodes, multi-region IPFS
- Security review: keys, firmware signing, secure OTA, supply-chain checks

## Milestones
- M1: Org + repos ready
- M2: MVP (first on-air logs visible on testnet explorer)
- M3: Community pilot (≥50 operators)
- M4: Hardening + partnerships (ORARI/IARU/universities)

## Communication
- Org About (short): see `org_about_bio.txt`
- Public README: concise mission, architecture diagram, links to modules
