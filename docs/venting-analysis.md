# Chimney Venting Analysis — Gas Boiler + Gas Water Heater

**Project:** Elevation Chimney Services — chimney rebuild
**Date:** 2026-06-19
**Source:** 5 field photos (see `assets/reference/`)
**Interactive 3D model:** open [`/index.html`](../index.html) in a browser

> ⚠️ **Scope note.** This is an informational engineering review based on photos and your
> verbal description. It is **not** a substitute for an on-site inspection with combustion/draft
> testing, and final sign-off must follow the **National Fuel Gas Code (NFPA 54 / ANSI Z223.1)**
> or your locally adopted **IFGC**, the appliance installation manuals, and the chimney-liner
> listing (UL 1777). Verify everything against the actual **input BTU/hr** on each appliance's
> rating plate.

---

## 1. What the appliances actually are

| Item | Identification | How I can tell |
|------|----------------|----------------|
| The blue cabinet | **Crown gas-fired *boiler* (hydronic / hot-water)** — *not* a warm-air furnace | Copper near-boiler piping + circulator, cast-iron sections, no supply/return air ductwork. "Andy's Heating & Cooling" service sticker on the Crown cabinet (photo 4). |
| The "pipe coming off it" you asked about | The **flue / vent connector** leaving the **draft hood (draft diverter)** on top of the boiler | Galvanized single-wall pipe + elbow off the top of the cabinet (photos 1 & 3). |
| The tank | **Atmospheric (natural-draft) gas storage water heater** with a **draft hood** | Warning label + draft hood + 3" galvanized connector (photo 2). |
| Both appliances | **Category I, natural-draft, atmospheric** gas appliances | Draft hoods present → they rely on the chimney for natural draft. |

Both being Category I natural-draft appliances is what *allows* them to share a masonry chimney
(common venting) under NFPA 54 — **if** the vent is sized correctly.

> **Give me the two rating-plate model numbers** and I'll pull the exact **input BTU/hr** for each.
> Vent/liner sizing is driven entirely by those numbers, so they convert most of the "verify"
> items below into hard yes/no answers.

---

## 2. The one thing I need you to confirm (it changes the verdict)

Your description has an internal contradiction that I modeled both ways:

- You said **"both are common vented into a chimney, the chimney has a 5" liner,"** **and**
- **"the water heater … 3" → increaser to 6" → 6" flexible stainless liner through the chimney."**

Those are two *different* configurations:

- **(A) Two separate liners in one chimney** — boiler on a 5" liner, water heater on its own 6" flex liner. (Each appliance independently vented; *not* common venting.)
- **(B) True common vent** — both connectors join, then one liner carries the combined flue gas.

Photo 5 shows a **tee/increaser** on the galvanized connector, which *hints* at a common
manifold (B), but the two-liner story points to (A). **Please confirm which it is** — the code
analysis below flags the items that depend on it.

---

## 3. Findings — what looks wrong / needs verifying

Severity: 🔴 likely violation · 🟠 verify / probable issue · 🟢 looks OK

### 🔴 3.1 The 6" liner is almost certainly **oversized** for a single water heater
A typical residential gas water heater is **~30,000–50,000 BTU/hr** with a **3" or 4" draft-hood
outlet**. Running that into a **6" liner** roughly **quadruples** the flue area the appliance has
to heat (area ∝ diameter²: 3"→7 in², 6"→28 in²).

Why it matters (NFPA 54 vent sizing tables, Ch. 13):
- **Oversized = under-velocity.** Flue gases slow down, cool below dew point, and **condense**.
- Condensate + flue gas = **corrosive acidic moisture** → rusts connectors and deteriorates masonry
  (consistent with the **rust/corrosion** visible in photos 1 & 3).
- **Slow draft establishment** on a cold start → **spillage at the draft hood** and **CO risk**.

A single WH almost always wants a **3" or 4"** liner, not 6". **Unless** the 6" is the *common*
vent for **both** appliances (config B) — then 6" may be correct; confirm with the combined-input
table.

### 🔴 3.2 The 3" → 6" increaser placement / jump
- A vent should **never reduce** in the direction of flow, and abrupt **oversizing** is its own
  problem (see 3.1). A 3"→6" step at a single small appliance is a red flag.
- Per NFPA 54, the connector size is set by the appliance outlet and the vent-table column —
  arbitrary upsizing to fill a too-big liner is not a fix; **right-size the liner instead.**

### 🟠 3.3 Common-vent connector rules (if config B)
When two appliances share a vent, NFPA 54 requires:
- The **smaller-input** connector should connect **above** the larger where practical.
- Each connector must **rise** continuously to the common vent (**≥ ¼" per foot**).
- The common vent is sized from the **"combined"** table column, the individual connectors from
  the **"connector"** columns — verify against actual inputs.

### 🟠 3.4 Vent-connector slope & rise
Single-wall connectors must **slope upward ≥ ¼ inch per foot** from the appliance to the chimney,
with no sags/low spots that trap condensate. The horizontal galvanized runs in photos 3 & 5 look
**close to level** — measure and correct the pitch.

### 🟠 3.5 Single-wall galvanized clearance to combustibles
Single-wall metal connector requires **6" clearance to combustible materials** (joists, subfloor,
framing) unless listed/shielded for less. The connectors run near the **wood floor joists** above —
verify the 6" or add listed shielding / switch to **Type B** double-wall (1" clearance).

### 🟠 3.6 Connector length & "rule of thumb" limits
- Single-wall connector horizontal length should be **≤ 75% of the vertical height** of the chimney
  it serves (Type B ≤ 100%). Keep connectors **as short and direct as practical**; minimize elbows
  (each elbow adds resistance).

### 🟠 3.7 Corrosion already present
Visible **rust/scale** on the cast-iron drain/vent components and connector (photos 1, 3) suggests
a **history of condensation or spillage**. During the rebuild, inspect the masonry/liner interior
for deterioration and the appliances for **flue-gas spillage staining**.

### 🟠 3.8 Liner installation details to confirm during the rebuild
- Flex liner **continuous & properly sized**, **insulated** if required by its listing/clearance.
- **Bottom tee** with **capped cleanout / condensate drain**.
- **Top plate + storm collar + listed rain cap.**
- **Thimble** connection at the chimney sealed; connector inserted to (not past) the inner wall.
- Liner **listed to UL 1777** and installed per its manual.

### 🟢 3.9 What looks fine
- Two **Category I natural-draft** appliances **may** share a properly sized masonry chimney. ✔
- Using a **listed stainless flex liner** in a masonry chimney is the correct modern approach. ✔
- **Draft hoods** present on both appliances (correct for atmospheric appliances). ✔

---

## 4. Quick sizing sanity check (fill in from rating plates)

| Appliance | Input (BTU/hr) | Draft-hood outlet | Connector | Liner |
|-----------|----------------|-------------------|-----------|-------|
| Crown boiler | **? (model #)** | ? | ? | "5" per notes |
| Water heater | **? (model #)** | 3" | 3"→6" | 6" flex |
| **Combined (if common vent)** | **= sum** | — | — | size from "combined" column |

Once you give me both model numbers, I'll: (1) confirm inputs, (2) run the NFPA 54 vent tables for
your **chimney height + lateral length**, and (3) tell you the **correct liner diameter(s)** —
which I expect will show the **6" should likely be 3" or 4"** for the water heater alone.

---

## 4b. Fireplace above (now modeled from your firebox photos)

The masonry chimney that carries the boiler/water-heater liners also serves a **first-floor
fireplace** directly above (photos 06–10). Approximate field measurements from the tape:

| Firebox dimension | Approx. measured | Notes |
|-------------------|------------------|-------|
| Opening **width** | **~47–48"** | tape bends at corner ~47"–48" (photos 08, 09) |
| Opening **height** | **~30"** (verify) | vertical tape (photo 09) — confirm exact |
| **Depth** (front→back) | **~16–18"** (verify) | photo 10 |
| Hearth / surround | **Gray-green tile** field + raised tiled hearth | photo 06 |

> These are read off the photos and should be **re-measured on site** before any rebuild
> dimensioning. Send a straight-on shot with the tape fully extended across the **opening
> width**, the **opening height** (floor to lintel), and the **depth** for exact numbers.

**Code points for the fireplace during the rebuild:**
- **Hearth extension**: a fireplace opening **≥ 6 ft²** needs a hearth extension **≥ 20"** front
  and **≥ 12"** each side of the opening; smaller openings **≥ 16"** front / **≥ 8"** sides
  (IRC R1001 / NFPA 211). A ~47×30" opening ≈ **9.8 ft²** → it's in the **larger** category.
- **Firebox**: minimum **10"** firebrick depth typical; rebuild with refractory firebrick + mortar.
- **Flue sizing**: the fireplace **flue area** must be sized to the **opening area** (round liner
  typically ≈ **1/12** of the opening; rectangular ≈ **1/10**). A ~9.8 ft² opening needs a sizable
  flue — **confirm the fireplace has its own dedicated flue**, separate from the appliance liners.
- **Never common-vent** the fireplace with the gas appliances — it must be an **independent flue**.

## 5. The 3D model

`index.html` is a self-contained interactive model (Three.js). Open it in any modern browser:

- **Cutaway chimney** showing the 6" flex liner and the 5" liner inside the masonry.
- Crown **boiler**, gas **water heater**, draft hoods, galvanized connectors, the **3"→6" increaser**.
- **Fireplace above** — now modeled from your firebox measurements (gray-green tile, ~47" opening).
- **Flue-gas flow arrows**, **labels**, and **pulsing red/amber markers** at each issue from §3.
- Toggles for cutaway, labels, issues, joists/walls, fireplace, and auto-rotate.

### Next info that would sharpen the model
1. Both appliance **rating plates** (model + input BTU/hr) — unlocks exact liner sizing.
2. A wide shot showing the **chimney height** and where the connectors enter (thimble).
3. The **top of the chimney** (cap, liner terminations, crown) — and **how many flues** it has.
4. A tape on the **boiler** connector diameter and the **chimney lateral run length**.
5. Straight-on fireplace **opening width / height / depth** with the tape fully extended.
