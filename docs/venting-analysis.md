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

## 2. Configuration (CONFIRMED by client)

- **Boiler + water heater are COMMON-VENTED** in the basement — both draft-hood connectors
  **merge at a tee**, then a **single shared liner** (the 6" flex stainless) carries the combined
  flue gas up the chimney. (Consistent with the tee in photo 5.)
- The **fireplace has its OWN, separate liner** — a dedicated flue. ✔ This is correct and required;
  a fireplace must **never** be common-vented with gas appliances.
- The chimney was **struck by a tree**; the **top ~6 ft (above the roofline) is being rebuilt**.

This resolves the earlier ambiguity. Because the 6" is now a **common vent serving both
appliances** (not a single water heater), the sizing question flips — see §3.1.

---

## 3. Findings — what looks wrong / needs verifying

Severity: 🔴 likely violation · 🟠 verify / probable issue · 🟢 looks OK

### 🟠 3.1 Verify the 6" common vent is sized for the **COMBINED** input (now plausibly OK)
Now that the 6" liner is the **shared common vent for both appliances**, 6" is **in the realistic
range** — but it must be checked against the **combined input** and the **chimney height/lateral
run** using the NFPA 54 **common-vent tables** (Ch. 13):

- Use the **"Combined Appliances"** column for the shared liner, the **"Connector"** columns for each
  individual connector.
- Rough example: a ~100k BTU boiler + ~40k BTU water heater ≈ **140k BTU combined** — over a typical
  20–30 ft chimney a **6"** common vent is commonly **adequate**, but it can be **borderline either
  way** depending on the *actual* inputs and height. **This is exactly why I need the two model
  numbers.** It could come back "6" is correct," or "needs 7"," or "could drop to 5"."
- Watch the **opposite failure mode too**: if the boiler input is high and the chimney is short,
  6" could be **undersized** for the combined load → poor draft / spillage.

> Bottom line: 6" is no longer an automatic red flag (it's a *shared* vent now), but it is **not
> confirmed** until run through the combined table with real numbers.

### 🟠 3.2 The 3" → 6" increaser
- A vent must **never reduce** in the direction of flow — increasing to the 6" common vent is fine.
- Make the **increaser at the appliance / connector**, and confirm each connector is sized per the
  **connector** column (the WH's 3" draft-hood connector is typical; verify length/rise).

### 🟠 3.3 Common-vent connector rules — **verify these now that it's confirmed common-vented**
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
- **Fireplace on its own dedicated liner** — correct; it must stay independent of the gas vent. ✔

---

## 3b. Tree strike — rebuilding the top 6 ft (do this right)

You're opening the roof and **building the chimney back up ~6 ft**. Key requirements for the rebuild:

### 🔴 3b.1 Termination height — the "3-2-10 rule"
The chimney must terminate **at least 3 ft above** the roof penetration **and at least 2 ft above
any part of the structure within a 10 ft horizontal radius** (NFPA 211 / IRC R1003.9). When you set
the new 6 ft, **confirm both conditions are met** — especially the 2-ft-within-10-ft check against
ridges, dormers, or adjacent roof planes. Taller generally **helps** natural draft, so +6 ft is
usually fine for draft; just don't *under*-shoot the rule.

### 🔴 3b.2 Extend BOTH liners through the new section + new terminations
- Run the **6" appliance common-vent liner** and the **fireplace liner** continuously up through the
  rebuilt masonry — **no gaps, no offsets that trap condensate.**
- New **crown** (sloped, with drip edge / overhang), **top plate + storm collar**, and a **listed
  rain cap** on **each** flue. Keep the two flues separated by a proper **wythe**.

### 🟠 3b.3 Inspect the EXISTING (lower) chimney & liners for impact damage
A tree strike that took out the top can also **crack the masonry, shift the crown, or crush/separate
liners lower down.** Before you re-cap:
- **Camera-scan** both liners full length for crushing, separation, or displacement.
- Check the masonry below the roofline for **cracks, spalling, leaning,** and water entry.
- Verify the **flue-to-wythe separation** is intact (no cross-talk between flues).

### 🟠 3b.4 Rebuild detailing
- **Tie new masonry to sound existing** (toothing / proper bond), correct mortar type.
- New **step/counter-flashing + cricket** if the chimney is wide on the up-slope side.
- Confirm structural support is undamaged.

---

## 4. Quick sizing sanity check (fill in from rating plates)

| Appliance | Input (BTU/hr) | Draft-hood outlet | Connector | Vent |
|-----------|----------------|-------------------|-----------|------|
| Crown boiler | **? (model #)** | ? | ? | → common vent |
| Water heater | **? (model #)** | 3" | 3"→6" | → common vent |
| **Combined (common vent)** | **= sum** | — | — | **6" shared flex liner — size from "Combined" column** |

Once you give me both model numbers, I'll: (1) confirm inputs, (2) run the NFPA 54 **common-vent**
tables for your **chimney height + lateral run**, and (3) confirm whether the **6" shared liner is
correct, oversized, or undersized** for the combined load — plus the right connector sizes.

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

- **Cutaway chimney** showing the **shared 6" common-vent liner** and the **separate fireplace liner**.
- Crown **boiler** + gas **water heater**, draft hoods, connectors **merging at the common-vent tee**,
  the **3"→6" increaser**, and a single pipe into the chimney thimble.
- **Roofline + the rebuilt top 6 ft** (tree strike) highlighted in amber, with the **3-2-10** note.
- **Fireplace above** — modeled from your firebox measurements (gray-green tile, ~47" opening).
- **Flue-gas flow arrows**, **labels**, and **pulsing markers** at each item from §3 / §3b.
- Toggles for cutaway, labels, issues, flow, joists/walls, fireplace, **roof/rebuild**, and auto-rotate.

### About the Polycam scan you sent (`assets/scan/`)
The uploaded `.glb` is a Polycam **"Spaces"** capture — an AI room-segmentation of the **upstairs
living room with the fireplace** (89 walls, 12 windows, doors, stairs, a chair, one `fireplace`
object). View it with `scan-viewer.html`.

- ✅ **Useful:** it confirms the **fireplace surround ≈ 5.8 ft wide × ~2.7 ft deep** (I updated the
  model to match).
- ⚠️ **But it's the wrong capture for the venting:** Spaces produces tidy room geometry, **not** the
  basement, the boiler/water heater, the connectors, or the chimney's vertical run. So it can't give
  me the lateral run or total chimney height.

**To make the venting model dimensionally exact, rescan in Polycam using one of these instead of
"Spaces":**
- **LiDAR → "Room" or "Object" mode** (not Spaces), or **Photo mode**, capturing the **basement**:
  walk the full path *water heater → 3" → increaser → tee → boiler connector → chimney thimble*, then
  pan up the chimney.
- Export that as **GLTF/GLB** (or OBJ) — that mesh *will* contain the real connector run + heights.

### Still needed to finalize the venting verdict
1. Both appliance **rating plates** (model + input BTU/hr) — unlocks exact **common-vent** sizing.
2. **Total chimney height** + **lateral run** of the connectors (basement rescan above, or tape).
3. The **top of the chimney** (existing crown/caps) and a camera-scan down both flues.
4. Tape on the **boiler** connector diameter.
