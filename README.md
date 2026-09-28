# Justitian: 300 Plot Hooks — Foundry VTT module

A [Foundry Virtual Tabletop](https://foundryvtt.com/) module presenting the community
fanwork **"JUSTITIAN: 300 Plot Hooks"** (by **Obie_Decker & Kleffe**) for the
**DEGENESIS: Rebirth** system as **four rollable tables** — one per chapter of the
original PDF.

## What's inside

| Roll table | Chapter subtitle | Hooks | Die |
|---|---|---|---|
| A Day in the City | Encounters with People of the Protectorate | 81 | 1d81 |
| Conflicts Innumerable | The Struggles that Permeate Life | 99 | 1d99 |
| Lands of Ruin | Discord Brewing Beneath | 73 | 1d73 |
| Justitian Burns | The Plots of Giants, the Ancient War, the End Times | 46 | 1d46 |
| | | **299** | |

Each table entry contains the hook text verbatim, its ▶ addendum lines, and the
original book cross-references (e.g. `[TRF 212] • [MOL 75]`). Special boxed hooks
from the book keep their red all-caps headings (e.g. **MARIONETTES**, **PLAGUE**,
**THE CITY BURNS**) as bold titles.

## Install

### From the manifest (recommended)

1. In Foundry's setup screen, open the **Add-on Modules** tab → **Install Module**.
2. Paste this manifest URL:
   ```
   https://raw.githubusercontent.com/Stefans-ttrpgs-tinkerings/justitian-plot-hooks/main/module.json
   ```
3. Enable **JUSTITIAN: 300 Plot Hooks** in your world (requires the
   **DEGENESIS: Rebirth** system, tested on Foundry v14 with system v0.8).
4. Open the compendium pack **Justitian: 300 Plot Hooks**, unlock the tables, roll.

### Manual

Copy (or symlink) this folder into your Foundry `Data/modules/` directory and
restart Foundry.

## Use

Each table is a regular Foundry `RollTable`. Roll from the compendium directly, or
drop tables into scenes / macros / dialog prompts as usual.

## Reference legend (from the source book)

`TRF` The Righteous Fist • `MOL` Moloch • `KAT` Katharsys • `ART` Artifacts •
`TKG` The Killing Game • `BA` Black Atlantic • `HW` Harm's Way •
`COTM` Clans of the Moloch • `COTF` Clans of the Frontier • `ATL` Atlas

## Notes

- The book advertises 300 hooks; 299 could be verified via two independent extraction
  passes. One hook appears to exist only in the authors' marketing count.
- The Degenesis system is a dependency gate only; the tables are regular
  `RollTable` documents and technically work in any world.

## Credits

Original fanwork: **"JUSTITIAN: 300 Plot Hooks"** by **Obie_Decker & Kleffe**,
with artwork © SIXMOREVODKA used with kind permission of the rightholder (per the
source book's editorial page).

> DEGENESIS® is TM SIXMOREVODKA Studio GmbH. All rights reserved.

This repository is an unofficial adaptation of that community fanwork for Foundry
VTT; no claim of ownership over Degenesis IP is made.
