# Yash Virulkar

**Software Engineer · Open Source Contributor · Co-founder, Mergit**

Bangalore, India · [yash.virulkar@proton.me](mailto:yash.virulkar@proton.me) · [github.com/Viscous106](https://github.com/Viscous106) · [LinkedIn](https://www.linkedin.com/in/yash-virulkar-338418329) · [yash.mergit.site](https://yash.mergit.site) · [PDF](https://yash.mergit.site/Yash_Virulkar_Resume.pdf)

## Summary

CS student (Scaler School of Technology, IIT Madras) who ships real systems. Co-founder of Mergit, a trust
and settlement layer for AI-agent work: 2nd place at ETHGlobal Mumbai, invite-only with ~50 users. Six
merged PRs to CNCF and open-source infrastructure (KCL, Karmada, OpenWISP) in Rust, Go and Python, taken
through maintainer review.

## Experience

**[Mergit](https://mergit.site)** — Co-founder · TypeScript · Python · Rust · Solidity · *Jun 2026 – Present*

- **2nd place, ETHGlobal Mumbai** (Nov 2026). AI-agent workspace where agents complete real development and GitHub tasks and work settles on verified outcomes, not attempts; live and invite-only with ~50 users.
- Own the product end to end as main product manager for a 3-person founding team: roadmap, requirements and priorities, while building most of the system.
- Built the full stack: TypeScript web app, Python and Rust agent runtime and control plane, PostgreSQL; agents run in a Mergit-owned sandbox that emits hash-chained, signed execution receipts.
- Wrote and tested Solidity contracts in Foundry for agent identity, receipt registry, escrow, staking, challenges and reputation, deployed on Base Sepolia with fork tests against live chain state ([mergit-contracts](https://github.com/mergit-io/mergit-contracts)).
- **Sole author** of the Mergit research paper [“Pay for What You Got”](https://research.mergit.site): verifiable execution receipts, cost-adjusted reputation and outcome-contingent settlement for agent markets.

## Open Source · merged PRs

**KCL Programming Language** — CNCF Sandbox · Rust · *Jul 2026*
- Fixed a runtime deadlock by releasing the plugin dispatch lock before invoking the handler, narrowing the critical section without introducing a data race ([#2106](https://github.com/kcl-lang/kcl/pull/2106))
- Guarded a `current_dir()` panic on the wasm32 target, where there is no working directory ([#2105](https://github.com/kcl-lang/kcl/pull/2105))

**Karmada** — CNCF, multi-cluster Kubernetes · Go · *May 2026*
- Added end-to-end tests for overflow cluster affinities in the scheduler ([#7489](https://github.com/karmada-io/karmada/pull/7489))

**OpenWISP** — network and WiFi controller · Python · Lua · OpenWrt · *Jan – Mar 2026*
- Added SIGUSR2 support to force a configuration reload in the OpenWrt agent ([openwisp-config #245](https://github.com/openwisp/openwisp-config/pull/245))
- Fixed SSID boolean coercion in device configuration rendering ([netjsonconfig #381](https://github.com/openwisp/netjsonconfig/pull/381))

## Projects

**[nodeLive](https://github.com/Viscous106/nodeLive)** — production live-classroom LMS · FastAPI · WebSockets · Zoom Meeting SDK
- Production-grade live classroom on the Zoom Meeting SDK with 11 real-time teaching tools: server-timed quizzes, polls, leaderboards and a Claude-powered doubt solver with live-transcript context.

**[omniBox](https://github.com/Viscous106/omniBox)** — multi-agent runner · Python
- Splits a delegated goal across tool-using agents, with orchestrator-enforced budgets and loop guards.

**[Orkflow](https://github.com/shri771/Orkflow)** — YAML-driven multi-agent orchestration engine · Go
- Co-built with a teammate; wrote the Cobra CLI, global and local config scopes, MCP tool integration and ChromaDB memory (17 merged PRs).

## Leadership

**Web3 Lead, Open Source Club** — Scaler School of Technology · *Oct 2026 – Present*
- Lead the Web3 track of a ~200-member club: sessions, events and upcoming hackathons.

**Core Member, Open Source Club** — Scaler School of Technology · *2025 – Present*
- Mentor students to their first merged pull request; maintain the club's learning repository (65 forks).

## Skills

- **Languages:** Python, TypeScript, Go, Rust, Solidity, Java, SQL, Bash
- **Backend & Web:** FastAPI, Django, React, Next.js, WebSockets, REST APIs
- **Web3:** Solidity, Foundry, EVM / Base, ENS (ENSIP-25), on-chain receipts and escrow
- **Infra & DevOps:** Docker, Kubernetes, CI/CD, Caddy, Hetzner, Nix / NixOS, Linux
- **Data:** PostgreSQL, Redis

## Education

- **Scaler School of Technology**, Bangalore — Computer Science · *Aug 2025 – May 2029*
- **Indian Institute of Technology Madras** — BS in Data Science · *Sep 2024 – Sep 2028*
- **Certifications:** CS50 Cybersecurity (Harvard) · DevOps (Boot.dev) · DBMS (Boot.dev)
