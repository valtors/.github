<div align="center">

# valtors

local-first infrastructure for agents you can inspect, constrain, reproduce, and trust.

modular tools. one trust model. no required cloud.

[![GitHub Org](https://img.shields.io/badge/GitHub-Valtors-181717?style=flat&logo=github)](https://github.com/valtors)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Local First](https://img.shields.io/badge/Architecture-local--first-0f766e.svg)](#principles)

</div>

---

## the platform

| tool | what it does | lang | stars |
|------|-------------|------|-------|
| [forge](https://github.com/valtors/forge) | **incubator** — local agent runtime and emerging umbrella for Valtors components. | Go | ![stars](https://img.shields.io/github/stars/valtors/forge?style=flat) |
| [relay](https://github.com/valtors/relay) | **active** — local MCP data plane for files, images, PDFs, web, and workflows. Some tools make explicitly requested network/API calls. | Go | ![stars](https://img.shields.io/github/stars/valtors/relay?style=flat) |
| [observer](https://github.com/valtors/observer) | **incubator** — local MCP tracing proxy and SQLite event store. | Go | ![stars](https://img.shields.io/github/stars/valtors/observer?style=flat) |
| [cairn](https://github.com/valtors/cairn) | **incubator** — embedded temporal memory for local agents in one SQLite file. | Rust | ![stars](https://img.shields.io/github/stars/valtors/cairn?style=flat) |
| [smith](https://github.com/valtors/smith) | **incubator** — MCP package resolution and composition; planned to become Forge supply-chain infrastructure. | Rust | ![stars](https://img.shields.io/github/stars/valtors/smith?style=flat) |
| [vault](https://github.com/valtors/vault) | **experimental** — policy and audit utilities; not currently an OS isolation boundary. | Go | ![stars](https://img.shields.io/github/stars/valtors/vault?style=flat) |
| [pulse](https://github.com/valtors/pulse) | **experimental** — local notification triage agent. | Go | ![stars](https://img.shields.io/github/stars/valtors/pulse?style=flat) |
| [reflow](https://github.com/valtors/reflow) | **maintained separately** — SSR-safe responsive toolkit for multi-framework TypeScript design systems. | TS | ![stars](https://img.shields.io/github/stars/valtors/reflow?style=flat) |
| [mcprobe](https://github.com/tamish560/mcprobe) | security scanner for MCP servers. detect injection patterns, find tool shadowing, baseline for drift. | Go | ![stars](https://img.shields.io/github/stars/tamish560/mcprobe?style=flat) |

## packages

- **userelay** (npm) - [![npm](https://img.shields.io/npm/dm/userelay?label=downloads)](https://www.npmjs.com/package/userelay)
- **usereflow** (npm) - [![npm](https://img.shields.io/npm/dm/usereflow?label=downloads)](https://www.npmjs.com/package/usereflow)
- **smith-mcp** (crates.io) - [![crates](https://img.shields.io/crates/d/smith-mcp?label=downloads)](https://crates.io/crates/smith-mcp)
- **cairn-memory** (crates.io) - [![crates](https://img.shields.io/crates/d/cairn-memory?label=downloads)](https://crates.io/crates/cairn-memory)

## principles

- **open source** - license terms are documented in each repository
- **data minimization** - no telemetry by default; network behavior and optional providers are documented per tool
- **boring tech** - go stdlib, sqlite, json. no frameworks you can't audit
- **local-first** - your data stays on your machine
- **human-in-the-loop** - agents assist, humans decide

## contribute

Start with the repository README and lifecycle status. Use Discussions for early ideas and Issues for reproducible bugs. Read the organization-wide contribution and security policies before opening a PR.

## license

MIT. everything. always.
