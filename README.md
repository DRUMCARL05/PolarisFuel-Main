<div align="center">

<img src="emblem.png" alt="Polaris Fuel Emblem" width="120" />

# Polaris Fuel

**Economic coordination infrastructure for Web3 gaming ecosystems.**

*We go deep before we go wide.*

[![Live Site](https://img.shields.io/badge/Live%20Site-polarisfuel.app-FF6B1A?style=flat-square&logo=firefox)](https://polarisfuel.app)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=flat-square&logo=discord)](https://discord.gg/yNfUZ4Gb7k)
[![Twitter](https://img.shields.io/badge/Twitter-@Polaris__Fuel-1DA1F2?style=flat-square&logo=twitter)](https://x.com/Polaris_Fuel)

</div>

---

## What is Polaris Fuel?

Polaris Fuel is a **Web3 gaming organization** specializing in economic coordination infrastructure across blockchain game ecosystems. We operate as the connective layer between complex in-game economies and their player bases — coordinating supply chains, resources, guilds, and political actors to reduce friction and unlock opportunity.

We specialize in **Fire & Metal Logistics**: guild coordination, bulk resource arbitrage, and political consulting within game economies. Each game we enter gets a dedicated team, its own community environment, and deep specialist coverage — not a one-size-fits-all approach.

> *"We dig. We craft. We build."*

---

## What We Do

- **Economic Coordination** — connecting producers, crafters, and traders across profession and racial networks
- **Resource Arbitrage** — bulk supply chain facilitation and cross-wallet asset management
- **Political Consulting** — governance participation, voting bloc coordination, and election strategy
- **Community Infrastructure** — bilingual (EN/ES) Discord ecosystems, expert guides, and recruitment
- **In-House Tooling** — Axon dApp: multi-wallet management, OTC escrow, and resource tracking on Solana

> ★ We prove value before asking for anything. Phase 1 services are always free.

---

## This Repository

Source code for [polarisfuel.app](https://polarisfuel.app) — the **main Polaris Fuel brand hub**. This site serves as the top-level entry point: organizational identity, team, multi-game navigation, and recruitment.

Game-specific content lives on dedicated subdomains, each with its own repository.

### File Structure
```
PolarisFuel-Main/
├── index.html          # Multi-game hub — hero, game cards (Valannia / LOTA), CTA band
├── about.html          # Team bios, origin story, studio partnership, principles
├── join.html           # Recruitment — player-type profiles, Discord CTA, Formspree form
├── emblem.png          # Polaris Fuel coin emblem
├── emblem2.png         # Alternate emblem asset
├── CNAME               # GitHub Pages custom domain: polarisfuel.app
├── _config.yml         # GitHub Pages config
└── .github/workflows/  # GitHub Actions deployment
```

### Navigation (all pages)

`Home | About | Valannia ▾ | LOTA ▾ | Join | Discord`

- **Valannia dropdown** — links to subpages at `valannia.polarisfuel.app`
- **LOTA dropdown** — Coming Soon only (no subpages, no full game name)
- Active page receives `class="active"` on the nav link

### Tech Stack

- **Pure HTML/CSS/JS** — no framework, no build step
- Bilingual EN/ES with `localStorage` language persistence
- CSS scroll-reveal animations via `IntersectionObserver`
- Custom canvas particle system (ember particles)
- Custom cursor (hidden on mobile)
- Recruitment form via [Formspree](https://formspree.io)
- Deployed via GitHub Pages → Porkbun DNS CNAME → `DRUMCARL05.github.io`

---

## Multi-Game Architecture

Polaris Fuel operates across multiple blockchain game ecosystems. Each game gets a dedicated subdomain, repo, and team:

| URL | Repo | Status |
|---|---|---|
| [polarisfuel.app](https://polarisfuel.app) | PolarisFuel-Main *(this repo)* | ✅ Live |
| [valannia.polarisfuel.app](https://valannia.polarisfuel.app) | PolarisFuel-Valannia | ✅ Live |
| lota.polarisfuel.app | PolarisFuel-LOTA | 🔄 In progress |
| staratlas.polarisfuel.app | PolarisFuel-StarAtlas | 📋 Planned |

### Architecture Rules

- **Separate GitHub repo per subdomain** — each has its own `CNAME` file and GitHub Pages config
- **DNS on Porkbun** — CNAME records pointing to `DRUMCARL05.github.io`
- Two repos cannot share the same custom domain — conflicts resolve at GitHub Pages settings
- Local development via GitHub Desktop and local clones (not the GitHub web UI)

---

## Active Game Ecosystems

### Valannia Realms *(Active)*
Blockchain medieval fantasy MMO — Unreal Engine 5 + Solana. Nine interdependent professions, racial territorial politics, Bitcoin-backed `$VALAN` economy. Polaris Fuel operates as the economic coordination layer for mount fuel, profession networks, and Race Leader elections.

→ [valannia.polarisfuel.app](https://valannia.polarisfuel.app)

### Law of the Abyss *(Coming Soon)*
Space MMO with deep player-driven economy. Polaris Fuel infrastructure in development.

→ Details coming soon

---

## Team

| Handle | Role |
|---|---|
| **DRUMCARL05** | Co-Founder — partnerships, strategic direction |
| **Birr4s** | Co-Founder — Spanish-language operations, community |
| **Grimgorr** | Co-Founder — technical infrastructure, Axon dApp |
| **StacheAttack** | Collaborator — marketing and design |
| **Morangø** | Community Moderator |
| **Bufalo Blanco** | Community Moderator |

---

## Join Us

- 💬 **Discord:** [discord.gg/yNfUZ4Gb7k](https://discord.gg/yNfUZ4Gb7k)
- 𝕏 **Twitter/X:** [@Polaris_Fuel](https://x.com/Polaris_Fuel)
- 🌐 **Website:** [polarisfuel.app](https://polarisfuel.app)

---

## Local Development

No build process required. Clone and open any HTML file directly:
```bash
git clone https://github.com/DRUMCARL05/PolarisFuel-Main.git
cd PolarisFuel-Main
open index.html
```

---

<div align="center">

*Many games. One network. Infinite coordination.*

**© 2026 Polaris Fuel**

</div>
