# Chimney Venting System — 3D Model & Code Review

A 3D "skeleton" model and engineering review of a shared masonry chimney serving a **Crown gas
boiler**, a **gas water heater**, and a **first-floor fireplace**, built for **Elevation Chimney
Services** during a chimney rebuild.

## Contents

| Path | What it is |
|------|------------|
| [`index.html`](index.html) | **Interactive 3D model** (Three.js). Open in any modern browser — drag to orbit, scroll to zoom. Toggles for chimney cutaway, labels, code-issue markers, flue-gas flow, and the fireplace. |
| [`docs/venting-analysis.md`](docs/venting-analysis.md) | **Full code-review write-up** — appliance ID, NFPA 54 / IFGC venting findings, firebox measurements, and what to verify. |
| `assets/reference/` | The field photos the model and review are based on. |

## How to view the 3D model

Just open `index.html` in a browser (double-click it, or serve the folder).
It loads Three.js from a CDN, so the viewing machine needs internet access the first time.

## Status / open questions

- ✅ **Common vent confirmed** — boiler + water heater merge in the basement into one shared 6" liner.
- ✅ **Fireplace = its own dedicated liner** (correct).
- ✅ **Tree strike** — top ~6 ft above the roofline is being rebuilt (modeled + reviewed; see §3b).
- ❓ **Appliance model numbers / input BTU/hr** — still needed to finalize the **common-vent** sizing
  (confirm whether the shared 6" is correct, oversized, or undersized for the combined load).
- 🟢 Fireplace firebox modeled from your tape measurements (~47" opening, gray-green tile).

> Informational only — not a substitute for an on-site inspection with draft/combustion testing.
