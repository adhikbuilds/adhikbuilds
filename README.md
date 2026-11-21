<h2>Adhik Agarwal</h2>

<p>
  <b>Backend, infrastructure and AI engineer.</b> I build AI products and the infrastructure that keeps them honest in production,
  and I fix bugs upstream in the tools I depend on.
</p>

<p>
  <a href="https://github.com/pulls?q=is%3Apr+author%3Aadhikbuilds+-user%3Aadhikbuilds"><img alt="Upstream pull requests" src="https://img.shields.io/badge/upstream_PRs-view_all-1f6feb?style=flat-square"></a>
  <a href="https://www.credly.com/badges/f2c916f8-d1a1-48b5-b230-e42e7ab3898d"><img alt="Claude Certified Architect" src="https://img.shields.io/badge/Claude_Certified_Architect-Foundations-d97757?style=flat-square"></a>
  <img alt="Location" src="https://img.shields.io/badge/Bengaluru-open_to_roles-2ea043?style=flat-square">
</p>

**Now:** LLM applications that parse messy documents (resumes, job postings, listings) into structured data,
with spend caps, deterministic fallbacks and no invented answers. Underneath: multi-tenant Postgres with row-level
security, Kubernetes on AWS, and CI/CD that ships on merge.

**How I work:** reproduce the bug with a failing test first, keep the diff small, explain the root cause, and check
whether the same bug exists anywhere else.

### Open source

Bugs I've traced to their root cause in other projects. Each fix comes with a regression test that fails without it.
The badges are live, so they show the real state of each pull request.

| Project | What was broken | Status |
|---|---|---|
| [SpiceDB](https://github.com/authzed/spicedb) <br><sub>authorization database</sub> | The server crashed on Postgres, CockroachDB and MySQL when a client disconnected and the running query then timed out. [#3521](https://github.com/authzed/spicedb/pull/3521) | ![status](https://img.shields.io/github/pulls/detail/state/authzed/spicedb/3521?label=&style=flat-square) |
| [lakeFS](https://github.com/treeverse/lakeFS) <br><sub>Git for data lakes</sub> | `log --stop-at` with a path filter walked past the stop commit and returned older history. [#10620](https://github.com/treeverse/lakeFS/pull/10620) | ![status](https://img.shields.io/github/pulls/detail/state/treeverse/lakeFS/10620?label=&style=flat-square) |
| [terraform-provider-github](https://github.com/integrations/terraform-provider-github) | Archiving a repository and changing its visibility in one apply failed with a 403, because the repository was archived first. [#3744](https://github.com/integrations/terraform-provider-github/pull/3744) | ![status](https://img.shields.io/github/pulls/detail/state/integrations/terraform-provider-github/3744?label=&style=flat-square) |
| [PipeCD](https://github.com/pipe-cd/pipecd) <br><sub>CNCF continuous delivery</sub> | The Live State page crashed when the selected deploy target disappeared after a refresh. [#7660](https://github.com/pipe-cd/pipecd/pull/7660) | ![status](https://img.shields.io/github/pulls/detail/state/pipe-cd/pipecd/7660?label=&style=flat-square) |
| [PipeCD](https://github.com/pipe-cd/pipecd) | Reviewed a fix for panics in `pipectl migrate`: ran four malformed configs against it and found one case it still missed, which the author then fixed. [#7326](https://github.com/pipe-cd/pipecd/pull/7326#issuecomment-6917621442) | Review |

### Things I've shipped

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

### Stack

| | |
|---|---|
| **Languages** | Go · Python · TypeScript |
| **Backend** | FastAPI · Next.js · PostgreSQL / PostGIS · row-level security |
| **Infrastructure** | Kubernetes (EKS) · Terraform · Docker · AWS · GitHub Actions |
| **AI** | LLM applications with structured output, spend caps and deterministic fallbacks |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/adhikbuilds/adhikbuilds/output/snake-dark.svg">
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/adhikbuilds/adhikbuilds/output/snake.svg">
</picture>

---

**B.E., BITS Pilani (2026)** · **Open to backend, infrastructure and AI engineering roles.** Message me on GitHub or email
**adhikagarwal16@gmail.com**.
