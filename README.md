# DPDP Retention Navigator

An interactive, click-based guide to data-retention obligations under the **DPDP Act 2023** and the **DPDP Rules 2025** — built so a lawyer can pick a scenario and read the exact retention rule that binds it, instead of parsing a dense matrix.

It's a single `index.html` file. No build step, no dependencies, no server. Open it or host it anywhere.

## What it does

**1. Scenario flow** — Pick who you are from the scenario box on the left (a Data Fiduciary, an e-commerce operator ≥ 2 cr users, a Consent Manager, State/research processing, and so on). The canvas draws that scenario's rule as a connected node flow:

> Applies to → Retention period / trigger → Erasure trigger → Notes

…and shows every **sectoral overlay** that stacks on top (PMLA/KYC, CGST, CERT-In, Companies Act, Income-tax, telecom UL, Aadhaar, etc.) with its own period.

**2. Interplay resolver** — Two retention duties rarely cancel; one governs, or they run in parallel. Pick any two of the seven regimes (A–G) and the resolver tells you which one wins and exactly how they interact — e.g. an erasure request beats the 3-yr ceiling but the 1-yr r. 8(3) floor still runs.

## Content source

Everything is drawn faithfully from the *Retention Obligations – Mapped* reference document (source matrix + interplay mapping). Section and rule citations are preserved on every card.

## How to publish it (GitHub Pages)

1. Create a new repository and add `index.html` (and this README).
2. **Settings → Pages → Build from branch → `main` / root.**
3. Share the `https://<you>.github.io/<repo>/` link with the team.

Or just email `index.html` — it runs offline by double-clicking.

## Notes & disclaimer

- Fonts (Gambarino / General Sans) load from Fontshare's CDN; with no internet the tool still works with system-serif fallback.
- This is a **navigational aid**, not legal advice. Verify every period against the primary instrument before relying on it. In-force dates: most Rule-8 duties bind from **13 May 2027**; Consent-Manager records from **26 Nov 2026**; s. 17 exempt processing is in force with the Act.

---

Built for internal firm use.
