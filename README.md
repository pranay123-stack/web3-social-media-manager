# Web3 Social Media Manager

Managing a protocol's public surface — announcements, community channels and the shareable
artefacts a launch actually needs.

> ### Status: no management tooling built yet
>
> There is no scheduler, no cross-posting engine and no analytics dashboard in my work, and
> this page does not pretend otherwise. What **is** built is the share-surface engineering
> underneath — the part that decides whether a post looks like anything when it lands.

---

## Built — the share surface

| Where | What exists |
|---|---|
| [kitty-nimiq-mini-app](https://github.com/pranay123-stack/kitty-nimiq-mini-app) | Generated **share cards** and one-link sharing — the whole product is "share one link, watch the pot fill up". 11 share/OG files, EN/DE/ES, 18 documented screenshots |
| [aura-card-asp](https://github.com/pranay123-stack/aura-card-asp) | 14 share/OG files — generated card artwork with a procedural fallback when the image model fails, so a share never renders blank |
| [hook-explorer](https://github.com/pranay123-stack/hook-explorer) | `ShareBar.tsx` for tool results, plus a written `grant/discord-post.md` — the launch announcement drafted alongside the code |

Open Graph images, share cards and deep links are where social work meets engineering. That
part is real; the scheduling layer above it is not built.

---

## Per-platform scope

What each channel actually demands for a protocol, and why they are not interchangeable:

| Platform | What it is for | The hard part |
|---|---|---|
| **Discord** | The community's home — support, governance chatter, contributor coordination | Onboarding and role gating (often token- or NFT-gated), plus moderation load that grows faster than the community |
| **Twitter / X** | Announcements and discovery; still where protocol news breaks | Threads that survive without context, and card previews that render correctly — a broken OG image halves reach |
| **Telegram** | Real-time community, dominant in trading circles | Scam and impersonation control; a channel is only as good as its moderation |
| **LinkedIn** | Institutional and hiring audience — a different register entirely | Writing for readers who want the business case, not the tokenomics |
| **Instagram** | Visual reach and consumer-facing products | Everything must work as an image; protocol mechanics rarely survive the translation |
| **Facebook** | Groups and older/regional audiences | Largely a distribution channel rather than a community one for Web3 |

---

## Scoped, not built

A manager tool would need: scheduled publishing across the six, per-platform formatting from
one source, OG/card generation at post time, engagement analytics, and moderation queues for
Discord and Telegram. None of that exists yet.

---

---

## Design specification

| Repo | Scope |
|---|---|
| [socialfi-projects](https://github.com/pranay123-stack/socialfi-projects) | Decentralized social graphs, creator tokens, content monetization, on-chain reputation, token-gated communities. **No source code** |

*Part of [Web3 Infrastructure](https://github.com/pranay123-stack/web3-infrastructure) ·
related: [Web3 Community Tools](https://github.com/pranay123-stack/web3-community-tools) · [Web3 Articles](https://github.com/pranay123-stack/web3-articles)*
