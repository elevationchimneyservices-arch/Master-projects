# Chimney Venting System — 3D Model & Code Review

A 3D "skeleton" model and engineering review of a shared masonry chimney serving a **Crown gas
boiler**, a **gas water heater**, and a **first-floor fireplace**, built for **Elevation Chimney
Services** during a chimney rebuild.

## Contents

| Path | What it is |
|------|------------|
| [`index.html`](index.html) | **Interactive 3D model** (Three.js). Open in any modern browser — drag to orbit, scroll to zoom. Toggles for chimney cutaway, labels, code-issue markers, flue-gas flow, fireplace, and the rebuilt top. |
| [`scan-viewer.html`](scan-viewer.html) | **Polycam scan viewer** — loads the uploaded room scan (`assets/scan/`). Serve over http (see below). |
| [`docs/venting-analysis.md`](docs/venting-analysis.md) | **Full code-review write-up** — appliance ID, NFPA 54 / IFGC venting findings, firebox measurements, and what to verify. |
| `assets/reference/` | The field photos the model and review are based on. |
| `assets/scan/` | The Polycam GLB scan of the fireplace room. |

## How to view the 3D model

Just open `index.html` in a browser (double-click it, or serve the folder).
It loads Three.js from a CDN, so the viewing machine needs internet access the first time.

### Viewing the Polycam scans
`scan-viewer.html` loads `.glb` files, which browsers block over `file://`. Serve the folder first:
```
cd Master-projects && python3 -m http.server 8000
# then open http://localhost:8000/scan-viewer.html
```

## Adding more scans (multi-scan workflow)
Scans can be uploaded a few at a time — they accumulate here, no need to send them all at once.

- Each scan lives in `assets/scan/` and is listed in [`assets/scan/scans.json`](assets/scan/scans.json).
- The viewer reads that manifest and shows a **dropdown** to switch between scans.
- You can also **drag-and-drop a `.glb`** onto the viewer for a quick local preview (not saved).
- When you send a new scan in chat, it gets saved + added to the manifest automatically.

**Helpful when capturing:** name/describe what each scan shows (e.g. "basement boiler-to-chimney
run", "chimney exterior / top"), and prefer Polycam **Room/Object/Photo** mode over **Spaces** for
anything where real dimensions matter (the venting run, the chimney).

## Status / open questions

- ✅ **Common vent confirmed** — boiler + water heater merge in the basement into one shared 6" liner.
- ✅ **Fireplace = its own dedicated liner** (correct).
- ✅ **Tree strike** — top ~6 ft above the roofline is being rebuilt (modeled + reviewed; see §3b).
- ❓ **Appliance model numbers / input BTU/hr** — still needed to finalize the **common-vent** sizing
  (confirm whether the shared 6" is correct, oversized, or undersized for the combined load).
- 🟢 Fireplace firebox modeled from your tape measurements (~47" opening, gray-green tile).

> Informational only — not a substitute for an on-site inspection with draft/combustion testing.
