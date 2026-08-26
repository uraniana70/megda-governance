# MEGDA — Genealogy from the EU AI Act

**MEGDA** is a policy-design prototype for a *Model for European Governance of Democratic AI*.

This repository contains an interactive structural reading of Regulation (EU) 2024/1689 (the EU AI Act). It maps selected provisions of the Act to a proposed democratic-governance layer built around:

- a **scientific key** — independent technical verification;
- a **legal key** — rights, responsibility, enforceability and review;
- a **democratic key** — structured civic participation in high-impact uses;
- a **public accountability ledger**;
- a **distributed emergency-review mechanism**;
- **human contestability** for significant AI-mediated decisions;
- two MEGDA-original structural proposals: **Public Compute Commons** and **Systemic AI Power**.

## What the site does

Each interactive card shows:

1. the relevant AI Act provision;
2. a concise description of the current rule;
3. the gap MEGDA identifies;
4. the proposed MEGDA extension;
5. the likely legal vehicle;
6. the institutions that could carry the proposal.

Filters let readers inspect the model by **governance pillar** or by **legal path**:

- Build from the current Act
- AI Act amendment
- Parallel / new legal instrument

## Run locally

No build step is required.

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser, although serving it locally is preferable.

## GitHub Pages

This repository is intentionally static and can be published directly with GitHub Pages.

1. Create a repository.
2. Upload the files in this folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

## Legal source

Primary legal source:

- Regulation (EU) 2024/1689, consolidated version of **27 July 2026**  
  https://eur-lex.europa.eu/eli/reg/2024/1689/2026-07-27/eng

The visualisation is a policy and legal-architecture prototype. Its article descriptions are intentionally concise and are not a substitute for the official text or legal advice.

## Design principle

> No actor should simultaneously control the creation, authorisation, verification and contestability of high-impact AI.

The adoption strategy mirrors that principle: MEGDA should not depend on a single institutional gatekeeper. It is conceived as a proposal that can be advanced through Parliament, Member States, civil society, citizen participation, independent authorities and the Commission in parallel.

## Repository structure

```text
.
├── index.html
├── README.md
├── SOURCES.md
├── LICENSE
└── .gitignore
```

## Suggested next modules

- **MEGDA Governance Simulator** — the three-key institutional flow.
- **Legislative Redline** — proposed amendment language article by article.
- **Adoption Map** — Parliament / Council / Commission / ECI / civil-society routes.
- **Public Compute Commons** — a separate EuroHPC-based governance module.
- **Systemic AI Power Index** — an exploratory concentration-of-power framework.

## Licence

MIT for the code in this repository. EU legislation and official institutional materials remain subject to their own legal terms and are not relicensed by this project.
