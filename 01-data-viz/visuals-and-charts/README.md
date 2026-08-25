# Visuals & Charts

Individual visuals and the techniques behind them — each self-contained with its own
write-up, source (PBIP), and media.

## Projects

| # | Project | Technique | Source |
|---|---------|-----------|--------|
| 1 | [Sales Growth Between Dates](./sales-growth-between-dates) | Disconnected date harvesting · dynamic annotation geometry · DAX-driven "stagecraft" on a native line chart | PBIP |
| 2 | [Forecasting EV Sales with CAGR](./ev-sales-cagr-forecast) | CAGR forecasting · four calculated-table variants for slicer-aware projection · dynamic CAGR measures · DAX stagecraft | PBIP |

---

Each project folder follows the same layout:

```
project-name/
├─ README.md   ← how it works
├─ pbip/       ← open, forkable Power BI source
├─ data/       ← sample dataset (set the DataFolder parameter to run it)
└─ media/      ← screenshots & demo GIFs
```