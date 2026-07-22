# rostam-assets

Character and environment art for **The Seven Labors of Rostam** (Haft Khan) — a narrative mobile game based on Ferdowsi's *Shahnameh*.

**Art style:** Safavid Tabriz miniature (c. 1530). Flat cel-shaded, lapis / vermilion / gold palette.

## Character assets

| File | Character | Status |
|------|-----------|--------|
| `rostam.png` | Rostam | ✅ Locked (canon reference) |
| `arzhang.png` | Arzhang Div | ✅ Locked — Persian *div*, bull-headed mace |
| `div_white.png` | Div-e Sefid (White Div) | ✅ Locked — avoids European grotesque styling |
| `sorceress_fair.png` | Sorceress — fair form (Khan 4) | ✅ Locked (paired) |
| `sorceress_true.png` | Sorceress — true/rotted form (Khan 4) | ✅ Locked (paired) |
| `ulad.png` | Ulad — bound (Khan 5) | ✅ Locked |
| `rakhsh_standing.jpg` | Rakhsh | ✅ Locked (standing pose) |
| `rakhsh_gallop.jpg` | Rakhsh | ✅ Locked (gallop pose) |
| `rakhsh_grazing.jpg` | Rakhsh | ✅ Locked (grazing pose) |
| `rakhsh_mountready.jpg` | Rakhsh | ✅ Locked (mount-ready pose) |

## Creature assets

| File | Creature | Status |
|------|----------|--------|
| `lion.png` | Lion (Khan 1) | ✅ Locked |
| `dragon.png` | Dragon (Khan 3) | ✅ Locked (menace variant optional) |

## Pending assets

| Character | Khan | Status |
|-----------|------|--------|
| Kay Kavus (blind Shah) | Khan 6 | ⬜ Not yet generated |
| Ram (divine guide) | Khan 2 | ⬜ Not yet generated |

## Notes

- **Sorceress is a matched pair.** `sorceress_fair.png` and `sorceress_true.png` share pose and composition so the game can crossfade/morph one into the other at the Khan 4 unmasking ("deceive the hero, never the player").
- **Backgrounds:** all files are portrait / bestiary versions. Background-removed cutout versions for in-game scene compositing will be added in the production phase (SOP-A).
- **Format:** character/creature masters are `.png`. Rakhsh poses are still `.jpg` and will be re-exported to `.png` for edge fidelity (flat miniature art compresses poorly as JPG).
- **Ship pipeline:** all masters convert to WebP at build time (SOP-D); these files remain the archived masters.

## Usage

Reference an asset by its raw URL:

`https://raw.githubusercontent.com/aryatechnologiesllc-arch/rostam-assets/main/<filename>`

Example: `.../main/rostam.png`
