## I turn messy human input into structured data.

**Fractional CTO / principal engineer — Zürich.** I take a product from idea to a
running, monitored, backed-up production service, and then I keep it alive.

Right now I run **14 production applications** on a single self-hosted box. Every one
of them ships push-to-main through CI, terminates its own TLS, restores from backup,
and is maintained by one person.

---

### What I go deep on

The layer between a human describing something and a row that validates. I have built it
three times, at three altitudes, and it runs against real data today.

**[ai-forms](https://github.com/bitbaum/ai-forms)** — the library. Fill a form from one
sentence, then keep talking to it until it is right. The hard part is not the first fill, it is
that *"actually, make it urgent"* has to patch the form instead of wiping it. Headless,
provider-agnostic, no markup, no styles.

**[DataCat](https://datacat.orangecat.ch)** — the platform. Forms, photos, documents and
audio in; validated records, dashboards and machine commands out. Multi-provider vision with
automatic failover, a confidence score on every extracted field, and schema versioning so old
submissions stay valid when forms change.

**In production** — refugee housing intake at [AOZ Wohnen](https://aoz-wohnen.orangecat.ch)
(38 compatibility factors, full audit trail) and hardware capture at
[evig](https://evig.orangecat.ch), a Zürich nonprofit keeping machines in circulation.

---

### Open source

**[crewless](https://github.com/bitbaum/crewless)** — the harness that lets one person run
all of the below: nobody merges by hand, deploys and npm publishes are reconcilers, and every
repo has exactly one definition of "verified". Extracted from this live fleet, outage reports
preserved in the script headers. Being built in public, numbers included — starting from
one star: [the experiment's opening entry](https://orangecat.ch/articles/one-star-c4w71w).

npm, all tokenless (OIDC trusted publishing):
[`ai-forms`](https://www.npmjs.com/package/ai-forms) ·
[`threadkit`](https://www.npmjs.com/package/threadkit) ·
[`bip-kit`](https://www.npmjs.com/package/bip-kit) — each extracted from a production system
above, none invented for its own sake.

---

### Live

**Platforms**

| | |
| --- | --- |
| [OrangeCat](https://orangecat.ch) | Bitcoin-native funding and commerce. No middlemen. |
| [FleetCrown](https://fleetcrown.orangecat.ch) | Execution OS for builders — projects, goals, money, and AI agent fleets. |
| [Solon](https://solon.orangecat.ch) | Governance you can verify instead of trust. Treasury on-chain, votes signed, decisions tracked against KPIs. |
| [Kivvi](https://kivvi.orangecat.ch) | AI-first ERP for Swiss SMEs. |
| [DataCat](https://datacat.orangecat.ch) | Universal AI data capture, analysis and delivery. |
| [Botsmann](https://botsmann.orangecat.ch) | Domain-specialised AI professionals — legal, medical, research, translation. |

**Swiss institutions & civic**

| | |
| --- | --- |
| [AOZ Wohnen](https://aoz-wohnen.orangecat.ch) | Compatibility-based housing placement for refugees — 38 factors, conflict prediction, full audit trail. |
| [Reparaturbonus Zürich](https://reparaturbonus.orangecat.ch) | City repair-bonus platform. Residents to certified repair shops instead of landfill. |
| [RevampIT](https://revampit.orangecat.ch) | Digital infrastructure for a Zürich nonprofit keeping hardware in circulation. |
| [revamp-info](https://revamp-info.orangecat.ch) | IT support and knowledge base. |
| [evig](https://evig.orangecat.ch) | Affordable intelligence — decent refurbished hardware, repair, workshops. |

**Product & client work**

| | |
| --- | --- |
| [VitaReBa](https://vitareba.orangecat.ch/de) | Metabolic psychiatry & longevity clinic portal — booking, care teams, GDPR-scoped clinician AI. |
| [Petvity](https://petvity.orangecat.ch/en) | Global pet care platform. |
| [S.Ink](https://sinktattoo.com/en) | Tattoo studio portfolio and booking. |

---

### Available for

Rates and scope: **[bitbaum.github.io/hire](https://bitbaum.github.io/hire/)**


- **Fractional CTO** — own the architecture, the deploy pipeline and the engineering bar
  for a team that doesn't have a senior engineer yet.
- **AI-native product builds** — greenfield, fixed scope, delivered in weeks.
- **Agent fleets & internal automation** — the recurring internal work that eats a team's week.
- **Rescue work** — an inherited codebase with no tests, no deploys, and nobody left who wrote it.

### How I work

- **One `verify` command per repo** — lint, typecheck, test. CI runs exactly that. Green
  locally means green on the branch.
- **Self-hosted by default.** Hetzner, Caddy, systemd, Postgres. No vendor lock-in, no
  per-seat pricing, no surprise bill.
- **Everything ships through a branch and CI.** The deliberate step is the pipeline, not a
  person clicking a button.
- TypeScript · Next.js · Postgres · Drizzle/Prisma · Tailwind · GitHub Actions

---

**Zürich, Switzerland** · [orangecat.ch](https://orangecat.ch) · [georgy.butaev@revamp-it.ch](mailto:georgy.butaev@revamp-it.ch)
