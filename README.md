## Adhik Agarwal

I build backend and infrastructure systems that keep working after the demo, the migration, and the 3am page.

Most of my work sits where product meets platform: multi-tenant SaaS on Postgres, Kubernetes on AWS,
and the delivery pipelines between them. I care about upgrade paths, blast radius, and leaving
systems simpler than I found them.

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
  tore down orphaned stacks, and recovered spend without losing anything we needed.

### Projects

| | |
|---|---|
| **[Solum](https://github.com/adhikbuilds/solum)** | Land feasibility and development appraisal for Dubai. Live plot records, setback geometry and residual land value, with all 100k+ city plots served as vector tiles from PostGIS. |
| **[WarmPath](https://github.com/adhikbuilds/warmpath)** | B2B outbound built on relationship graphs. Next.js 15 frontend with a [FastAPI intelligence service](https://github.com/adhikbuilds/warmpath-intelligence) for signals and AI-drafted warm intros. |

### Open source

I contribute fixes upstream to tools I use. Merged and open PRs are linked [here](https://github.com/pulls?q=is%3Apr+author%3Aadhikbuilds+-user%3Aadhikbuilds).

### Stack

Python · TypeScript · FastAPI · Next.js · PostgreSQL / PostGIS · Terraform · Kubernetes (EKS) · Docker · AWS · GitHub Actions

---

<sub>Reach me through GitHub, or say hi in a PR.</sub>
