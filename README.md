## Adhik Agarwal

I build AI products and the infrastructure that keeps them honest in production.

**Now:** LLM applications that parse messy documents (resumes, job postings, listings) into structured data,
with spend caps, deterministic fallbacks and no invented answers. Underneath: multi-tenant Postgres with row-level
security, Kubernetes on AWS, and CI/CD that ships on merge.

**Care about:** upgrade paths, blast radius, and tests that would have caught the bug.

### Education

- **B.E., BITS Pilani**, 2026

### Certifications

- **Claude Certified Architect – Foundations**, Anthropic (Nov 2026). [Verify on Credly](https://www.credly.com/badges/f2c916f8-d1a1-48b5-b230-e42e7ab3898d)

### Things I've shipped recently

- **Air-gapped installer for a Kubernetes platform.** Two commands from a laptop with no internet
  to a running cluster with every image, chart and dependency included. I also swapped an AGPL
  storage component for a permissively licensed one so customers could install it.
- **Tenant isolation in Postgres.** Row-level security across a multi-tenant schema, plus a
  migration upgrade path that holds for old installs, not just fresh ones.
- **Continuous delivery to EKS.** Merge to `main`, then production, with rollbacks.
- **Cloud cleanup across AWS accounts.** Rebuilt lost Terraform state through imports,
  and decommissioned orphaned stacks with snapshots and backups taken first.

### Projects

| | |
|---|---|
| **[Solum](https://github.com/adhikbuilds/solum)**<br>[▶ live](https://solum-city.vercel.app) | Land feasibility and development appraisal for Dubai. Live plot records, setback geometry and residual land value, with all 100k+ city plots served as vector tiles from PostGIS. |
| **[HireLane](https://github.com/adhikbuilds/hirelane)** | Public job board built from Greenhouse, Lever and Ashby APIs, plus an AI agent that drafts applications and flags what it must not guess. TypeScript monorepo with Postgres RLS, explainable match scores and per-user LLM spend caps. |
| **[Roofline](https://github.com/adhikbuilds/roofline)** | Rental-market explorer for Bangalore: deterministic ingestion and dedup, a fair-rent model, deal detection and commute comparison. |
| **[WarmPath](https://github.com/adhikbuilds/warmpath)**<br>[▶ live](https://warmpath-eta.vercel.app) | B2B outbound built on relationship graphs. Next.js 15 frontend with a [FastAPI intelligence service](https://github.com/adhikbuilds/warmpath-intelligence) for signals and AI-drafted warm intros. |

### Open source

I fix bugs upstream in tools I use: test first, small diffs, explained root cause.

| Project | Contribution | Status |
|---|---|---|
| [agno](https://github.com/agno-agi/agno) (43k★) | Azure AI Foundry Claude still defaulted to a model retiring 2026-11-30; aligned it with the Anthropic default, with a regression test ([PR #11704](https://github.com/agno-agi/agno/pull/11704)) | In review |

All upstream PRs: [github.com/pulls?q=author:adhikbuilds](https://github.com/pulls?q=is%3Apr+author%3Aadhikbuilds+-user%3Aadhikbuilds)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/adhikbuilds/adhikbuilds/output/snake-dark.svg">
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/adhikbuilds/adhikbuilds/output/snake.svg">
</picture>

### Stack

Python · TypeScript · FastAPI · Next.js · PostgreSQL / PostGIS · Terraform · Kubernetes (EKS) · Docker · AWS · GitHub Actions

---

<sub>Reach me through GitHub, or say hi in a PR.</sub>
