# rostam-assets

Character and environment art for **The Seven Labors of Rostam** (Haft Khan) — a narrative mobile game based on Ferdowsi's *Shahnameh*.

**Art style:** Safavid Tabriz miniature (c. 1530).

## Character assets

| File | Character | Status |
|------|-----------|--------|
| `rostam.png` | Rostam | ✅ Locked (canon reference) |
| `arzhang.png` | Arzhang Div | ✅ Locked — Persian *div*, bull-headed mace |
| `div_white.png` | Div-e Sefid (White Div) | ✅ Locked — avoids European grotesque styling |
| `rakhsh_standing.jpg` | Rakhsh | ✅ Locked (standing pose) |
| `rakhsh_gallop.jpg` | Rakhsh | ✅ Locked (gallop pose) |
| `rakhsh_grazing.jpg` | Rakhsh | ✅ Locked (grazing pose) |
| `rakhsh_mountready.jpg` | Rakhsh | ✅ Locked (mount-ready pose) |

**Notes:**
- All character files are **portrait / bestiary versions** on parchment ground. Background-removed cutout versions for in-game scene compositing will be added in the production phase (SOP-A).
- Rakhsh poses are currently `.jpg` and will be re-exported to `.png` for edge fidelity (flat miniature art compresses poorly as JPG).
- Ship pipeline converts all masters to WebP at build time (SOP-D); these PNGs remain the archived masters.

## Usage

Reference an asset by its raw URL:

`https://raw.githubusercontent.com/aryatechnologiesllc-arch/rostam-assets/main/<filename>`

Example: `.../main/rostam.png`
