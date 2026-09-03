**Cato, Zürich.** I design, ship, and operate full production systems.
Fractional CTO / principal engineer.

Six live, CI-green, test-covered web platforms — three of them past 2,300 commits — running
on infrastructure I operate myself.

---

### Flagships

**[OrangeCat](https://orangecat.ch)** — Bitcoin-native economic platform. Live pay-link and
commerce surfaces, Lightning settlement. Exchange, fund, lend, invest and govern are the
roadmap, not what ships today. *2,774 commits · 2,648 tests · CodeQL + Playwright E2E + uptime checks.*

**[evig](https://evig.orangecat.ch)** — storefront, community marketplace, repair and IT-help,
workshops, AI-assisted intake for refurbished hardware. *2,630 commits · 7,783 tests ·
151 migrations · 8-job CI.*

**[FleetCrown](https://fleetcrown.orangecat.ch)** — execution OS and AI-agent orchestration:
hosted control plane plus a local daemon that owns shell, git and PTY to drive coding agents.
Pre-1.0, live. *2,345 commits · 9 workflows · signed desktop binaries across 13 releases.*

**[Hirnli](https://github.com/bitbaum/hirnli)** — Swiss fundraising intelligence: 16,900
foundations turned into actionable grant applications. Multi-tenant SaaS.
*907 commits · 950 tests.*

**[Kivvi](https://kivvi.orangecat.ch)** — AI-first ERP for Swiss SMEs and secondhand retail.
Monorepo, Dockerised. *650 commits · 1,316 tests.*

**[AOZ Wohnen](https://aoz.orangecat.ch)** — compatibility-based housing placement: 38 factors,
conflict prediction, full audit trail. Deployed demo with sample data.
*3,748 tests across 215 files — the highest test-to-code ratio I run.*

---

### What else I build

**Swiss civic & public-service** — [Reparaturbonus Zürich](https://reparaturbonus.orangecat.ch)
(repair-bonus platform, residents to certified repair shops) ·
[SBB Lost & Found](https://sbb.orangecat.ch) (real-time lost-item recovery, Redis pub/sub +
Socket.io) · [revamp-info](https://revamp-info.orangecat.ch) (IT support knowledge base)

**Clinical & care portals** — [VitaReBa](https://vitareba.orangecat.ch/de) (metabolic psychiatry
and longevity: booking, care teams, GDPR-scoped clinician AI) ·
[Surf Your Life](https://surf-your-life.orangecat.ch) (burnout and Long COVID recovery —
daily check-ins, symptom tracking, early practitioner intervention)

**Commerce & booking** — [Petvity](https://petvity.orangecat.ch/en) (pet care platform) ·
[S.Ink](https://sinktattoo.com/en) (studio portfolio and booking) ·
[printcraft](https://printcraft.orangecat.ch) (scene composer for physical art)

**AI & data infrastructure** — [DataCat](https://datacat.orangecat.ch) (forms, photos, documents
and audio in; validated records and dashboards out, with multi-provider vision failover) ·
[Botsmann](https://botsmann.orangecat.ch) (domain-specialised AI professionals) ·
[Solon](https://solon.orangecat.ch) (on-chain treasury, signed votes, decisions tracked
against KPIs)

---

### How I work

- **One `verify` command per repo** — lint, typecheck, test. CI runs exactly that. Green
  locally means green on the branch.
- **Self-hosted by default.** Hetzner, Caddy, systemd, Postgres. No vendor lock-in, no
  per-seat pricing, no surprise bill.
- **Everything ships through a branch and CI.** The deliberate step is the pipeline, not a
  person clicking a button.
- **One automation harness across the whole fleet** — golden CI templates and audits that run
  from [fleet](https://github.com/bitbaum/fleet) against every repo.
- **Built to hand over.** Documentation, backup restores, and runbooks included.
- TypeScript · Next.js · Postgres · Drizzle/Prisma · Tailwind · GitHub Actions

---

### Published libraries

Each one extracted from a system above, published tokenless via OIDC trusted publishing.

- **[@bitbaum/ai-kit](https://www.npmjs.com/package/@bitbaum/ai-kit)** — stay on free LLM tiers:
  multi-vendor fallback, 429 classification that tells the three kinds apart, fair-share
  rationing of a shared daily pool.
- **[ai-forms](https://www.npmjs.com/package/ai-forms)** — fill a form from one sentence, then
  keep talking to it. The hard part isn't the first fill, it's that *"actually, make it urgent"*
  has to patch the form instead of wiping it.
- **[threadkit](https://www.npmjs.com/package/threadkit)** — headless multi-participant threads.
  Permission is participation, unread is per-person, and an AI participant obeys the same
  visibility rules as everyone else.

---

### Available for

**Rates and scope: [bitbaum.github.io/hire](https://bitbaum.github.io/hire/)**

- **Fractional CTO** — own the architecture, the deploy pipeline and the engineering bar
  for a team that doesn't have a senior engineer yet.
- **AI-native product builds** — greenfield, fixed scope, delivered in weeks.
- **Agent fleets & internal automation** — the recurring internal work that eats a team's week.
- **Rescue work** — an inherited codebase with no tests, no deploys, and nobody left who wrote it.

---

**Zürich, Switzerland** · [orangecat.ch](https://orangecat.ch)
