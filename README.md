# Trifold Brochure Mockup

Open `index.html` in any browser. No build step, no server needed.

## Swapping the artwork

Two ways:

1. **Replace the files.** Overwrite the six files in `images/` keeping the same
   filenames and reload the page. Any format the browser reads works (jpg, png, svg, webp).
2. **Edit the paths.** The `ART` block at the top of the `<script>` in `index.html`
   maps each panel to a file — point it anywhere you like.

## Panel map — letter fold

Both creases bend the same way, so the sheet curls into a "C" and the flap nests
inside the cover. (A Z-fold, where the creases alternate, would expose that panel on
the back instead — not what this piece is built for.)

Printed on one sheet. The tuck flap folds in first, the front cover folds over it.

**Outside of sheet, left to right**

| File | Panel | Content |
|---|---|---|
| `trifold-outside_01.jpg` | tuck-in flap | Lunch Boxes / A La Carte |
| `newback.jpg` | back cover | "Bring Woodgrain to your next event" + QR |
| `newfront.jpg` | front cover | Catering Menu |

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

`images/trifold-outside_01-revised.jpg` is a revised tuck-flap panel that is **not**
currently wired up — see the note in the panel table above.

## Search visibility

`robots.txt` disallows all crawlers and the page carries a `noindex, nofollow` meta tag.
Neither makes the site private — anyone with the URL can open it. They only keep it out
of search results.

## Controls

- **Slide to fold / unfold** — scrub the fold from flat open to fully closed
- **Closed / Cover open / Fully open** — animated presets
- **Flip over** — spin to the other side
- **Labels** — panel name overlays
- **Press sheet** — flat imposition view showing both sides of the sheet with fold lines
- **Drag** to rotate, **scroll** to zoom (the view auto-fits to whatever the fold is
  showing, so the closed cover fills the frame and the open spread pulls back)

The slider deliberately sits on its own row rather than at the very top of the page:
Arc keeps a window-drag strip along the top edge of the web view, and a control up there
drags the browser window instead of the handle.

The mockup is view-only — there's no way for a viewer to alter the artwork from the page.
