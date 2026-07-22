# rostam-assets

Character and environment art for **The Seven Labors of Rostam** (Haft Khan) — a narrative mobile game based on Ferdowsi's *Shahnameh*.

**Art style:** Safavid Tabriz miniature (c. 1530). Flat cel-shaded, lapis / vermilion / gold palette.

**Cast status: COMPLETE (12/12 assets locked).**

## Character assets

| File | Character | Status |
|------|-----------|--------|
| `rostam.png` | Rostam | ✅ Locked (canon reference) |
| `arzhang.png` | Arzhang Div | ✅ Locked — Persian *div*, bull-headed mace |
| `div_white.png` | Div-e Sefid (White Div) | ✅ Locked — avoids European grotesque styling |
| `sorceress_fair.png` | Sorceress — fair form (Khan 4) | ✅ Locked (paired) |
| `sorceress_true.png` | Sorceress — true/rotted form (Khan 4) | ✅ Locked (paired) |
| `ulad.png` | Ulad — bound (Khan 5) | ✅ Locked |
| `kavus.png` | Kay Kavus (blind Shah, Khan 6) | ✅ Locked (blindfold variant optional) |
| `rakhsh_standing.png` | Rakhsh — standing | ✅ Locked |
| `rakhsh_gallop.png` | Rakhsh — gallop | ✅ Locked |
| `rakhsh_grazing.png` | Rakhsh — grazing | ✅ Locked |
| `rakhsh_mountready.png` | Rakhsh — mount-ready | ✅ Locked |

## Creature assets

| File | Creature | Status |
|------|----------|--------|
| `lion.png` | Lion (Khan 1) | ✅ Locked |
| `dragon.png` | Dragon (Khan 3) | ✅ Locked (menace variant optional) |
| `ram.png` | Ram — divine guide (Khan 2) | ✅ Locked |

## Notes

- **Sorceress is a matched pair.** `sorceress_fair.png` and `sorceress_true.png` share pose and composition so the game can crossfade/morph one into the other at the Khan 4 unmasking ("deceive the hero, never the player").
- **Backgrounds:** all files are portrait / bestiary versions on parchment or pale ground. Background-removed cutout versions for in-game scene compositing will be added in the production phase (SOP-A).
- **Format:** all masters are `.png`.
- **Ship pipeline:** all masters convert to WebP at build time (SOP-D); these files remain the archived masters.
- **Optional future variants:** Kavus with blindfold (Khan 6 blinded state); dragon "menace" version; ram walking pose.

## Usage

Reference an asset by its raw URL:

`https://raw.githubusercontent.com/aryatechnologiesllc-arch/rostam-assets/main/<filename>`

Example: `.../main/rostam.png`
