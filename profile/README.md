<p align="center">
  <img src="https://raw.githubusercontent.com/wabox-app/.github/main/profile/assets/banner.svg" alt="wabox — the filesystem is the API" width="100%">
</p>

<p align="center">
  <a href="https://github.com/rodgco/wabox/blob/main/LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-3ddc84.svg"></a>
  <a href="https://www.npmjs.com/package/wabox"><img alt="npm" src="https://img.shields.io/npm/v/wabox.svg?color=3ddc84"></a>
  <a href="https://github.com/rodgco/wabox/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/rodgco/wabox/actions/workflows/ci.yml/badge.svg"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Windows-3b6ea5.svg">
  <img alt="node" src="https://img.shields.io/badge/node-%3E%3D18-3b6ea5.svg">
</p>

<p align="center">
  <b>Connect any chat channel to your filesystem.</b><br>
  Messages land as files in <code>inbox/</code>; reply by writing a file to <code>outbox/</code>.<br>
  No API to learn — point any process, script, or AI agent at two folders.
</p>

## Projects

| Project | What it is | Status |
| --- | --- | --- |
| [**wabox**](https://github.com/rodgco/wabox) | Core bridge — WhatsApp ↔ filesystem, CLI, background service | ✅ shipped · v0.1.10 |
| **wabox-bot** | Bash bridge: filesystem ↔ Claude (more frameworks later) | ◐ in progress |
| **channel adapters** | Slack · Discord · Telegram — same `inbox/`/`outbox/` contract | ○ planned |
| **docs / examples** | Integration recipes & the agent contract | ○ planned |

## Quick start

```bash
npm install -g wabox
wabox config   # pair with WhatsApp, install background service, done
```

Point any process at the `inbox/`/`outbox/` folders — or install the agent skill and your AI knows the contract.

## Roadmap

**Channels:** ✅ WhatsApp · ○ Slack · ○ Discord · ○ Telegram
**Agents:** ◐ wabox-bot (Claude) · ○ other frameworks

---

<p align="center">
  <sub>MIT · built by <a href="https://github.com/rodgco">Rodrigo Couto</a> · ⭐ star the repos · contributors welcome</sub>
</p>
