# Trifold Brochure Mockup

Open `index.html` in any browser. No build step, no server needed.

## Swapping the artwork

Two ways:

1. **Replace the files.** Overwrite the six files in `images/` keeping the same
   filenames and reload the page. Any format the browser reads works (jpg, png, svg, webp).
2. **Edit the paths.** The `ART` block at the top of the `<script>` in `index.html`
   maps each panel to a file — point it anywhere you like.

## Panel map — standard letter fold

Printed on one sheet. The tuck flap folds in first, the front cover folds over it.

**Outside of sheet, left to right**

| File | Panel | Content |
|---|---|---|
| `trifold-outside_01.jpg` | tuck-in flap | Lunch Boxes / A La Carte |
| `trifold-outside_02.jpg` | back cover | "We'd love to cater" + QR |
| `trifold-outside_03.jpg` | front cover | Catering Menu |

**Inside of sheet, left to right**

| File | Panel | Content | Reverse of |
|---|---|---|---|
| `trifold-inside_01.jpg` | inside left | Bagels & Breakfast Platters | front cover |
| `trifold-inside_02.jpg` | inside middle | Hot Breakfast Bundles / Boxes | back cover |
| `trifold-inside_03.jpg` | inside right | Full Lunch Platters | tuck flap |

So when you open the front cover you see Bagels & Breakfast on the left and the *outside*
of the tuck flap (Lunch Boxes / A La Carte) on the right; open the flap and the full
three-panel food spread is revealed.

Artwork is 3.667 in × 8.5 in per panel (letter sheet, 11 × 8.5 folded in thirds).
Current art is ~1300 × 3019 px per panel. The mockup renders all three panels at equal
width, so the slight per-panel width differences in the exports are ignored here.

Earlier numbered placeholders are parked in `images/placeholder/`.

## Controls

- **Slide to fold / unfold** — scrub the fold from flat open to fully closed
- **Closed / Cover open / Fully open** — animated presets
- **Flip over** — spin to the other side
- **Letter fold / Z-fold** — toggle how the flap folds
- **Labels** — panel name overlays
- **Press sheet** — flat imposition view showing both sides of the sheet with fold lines
- **Drag** to rotate, **scroll** to zoom

The mockup is view-only — there's no way for a viewer to alter the artwork from the page.
