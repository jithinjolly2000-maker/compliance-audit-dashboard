<div align="center">

# 🛡️ Compliance Audit & Exceptions Dashboard

### Ingest case records · reconcile fields · surface exceptions, value-at-risk & corrective-action priority

[![View Live Demo](https://img.shields.io/badge/▶_View_Live_Demo-0a5c4a?style=for-the-badge&logoColor=white)](https://jithinjolly2000-maker.github.io/compliance-audit-dashboard/)

![Built with](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0a7a52?style=flat-square)
![Hosting](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat-square&logo=github)
![Data](https://img.shields.io/badge/Data-synthetic_demo-b5841f?style=flat-square)

</div>

---

> ⚠️ **Portfolio demonstration — synthetic data.** All vendors, amounts and cases are randomly generated in the browser. Nothing here comes from any employer or real system. It demonstrates the *kind* of audit / exceptions tooling and reporting I build.

## ✨ What it shows

| Feature | Description |
|---------|-------------|
| 📊 **KPI header** | Cases audited, exceptions flagged, total value at risk, clean rate |
| 📈 **8-week trend** | Cases audited vs. exceptions found — inline SVG, no chart library |
| 🔎 **Exceptions table** | Sortable columns, risk / market filters, free-text search |
| 🗂️ **Drill-down** | Click any case for amount, period, risk flag, reason & suggested action |
| 💶 **Value-at-risk by market** | Live bar breakdown that reacts to the active filter |

## 💡 Why I built it

At work I designed audit / controls procedures and dashboards that flag financial-exposure
risks early, so they can be corrected before period close. This is a sanitized, self-contained
illustration of that pattern — the logic (flagging, value-at-risk, reconciliation state) with
no confidential data.

## 🧰 Tech

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no build step, no dependencies
- All data generated client-side; the whole app is a single `index.html`
- Hosted free on **GitHub Pages**

## ▶️ Run locally

```bash
# just open the file — there is no build step
start index.html      # Windows
```

<div align="center">

---

**Built by Jithin J** · [GitHub](https://github.com/jithinjolly2000-maker) · [LinkedIn](https://www.linkedin.com/in/jithin2k)

</div>
