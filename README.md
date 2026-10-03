# Compliance Audit & Exceptions Dashboard

A single-page, interactive **audit workflow demo** — it ingests case records,
reconciles key fields, and surfaces **exceptions, value-at-risk and corrective-action
priority** per case.

> **Live demo:** https://jithinjolly2000-maker.github.io/compliance-audit-dashboard/

> ⚠️ **Portfolio demo with synthetic data.** All vendors, amounts and cases are
> randomly generated in the browser. Nothing here comes from any employer or real
> system. It demonstrates the *kind* of tooling and reporting I build.

## What it shows

- **KPI header** — cases audited, exceptions flagged, total value at risk, clean rate.
- **8-week trend** — cases audited vs. exceptions found (inline SVG, no libraries).
- **Case exceptions table** — sortable columns, risk/market filters, free-text search.
- **Click-to-drill-down** — open any case for amount, period, risk flag, the exception
  reason, and a suggested corrective action.
- **Value-at-risk by market** — live bar breakdown that reacts to the active filter.

## Why I built it

At work I designed audit/controls procedures and dashboards that flag financial-exposure
risks early so they can be corrected before period close. This is a sanitized,
self-contained illustration of that pattern — the logic (flagging, VaR, reconciliation
state) without any confidential data.

## Tech

- Vanilla **HTML / CSS / JavaScript** — no frameworks, no build step, no dependencies.
- All data generated client-side; the whole app is one `index.html`.
- Hosted free on **GitHub Pages**.

## Run locally

Just open `index.html` in a browser. That's it.

---

Built by **Jithin J** · [github.com/jithinjolly2000-maker](https://github.com/jithinjolly2000-maker)
