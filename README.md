# Old Man Ji Ga Zo

An independent, offline-capable modern browser companion for the original **2010 Hasbro Ji Ga Zo 300-piece physical puzzle**.

**Open the app:** https://udeudeude.github.io/Old-Man-JiGaZo/

**Versioned link (bypasses older cached versions):** https://udeudeude.github.io/Old-Man-JiGaZo/workshop-v3.html

## Designed around the finished puzzle

The updated workshop works **automatically**. Choose or change a photo, puzzle shape, zoom, crop, or tonal adjustment, and the black-and-white mosaic recalculates after a brief pause. There is no mandatory Create step. A prominent **Refresh preview** button stays in the sticky top toolbar as a manual fallback.

- The photograph editor displays an **actual black-and-white crop**, not a color photograph.
- The main result opens in **Mosaic preview**, with the appearance created by the original shaded physical pieces.
- Choose **Assembly map** to see the original **color-coded identifying icons and their exact rotations**, needed to assemble the physical puzzle. The colors on this map are intentional identification aids, not a color mosaic.
- **Shape & size** and **One / Two puzzles** live at the top of the page.
- Contrast, brightness, edge detail, and tonal distribution are tucked under **Refine tones and detail**.
- Import a photo by selecting **Choose photograph** or dropping a photo on the editor; drag to reposition, pinch/scroll to zoom, or use the zoom slider and +/- buttons.
- **Print assembly map(s)**, save icon maps and mosaic images, and save/reopen complete projects (including legacy project files).

All computation and image processing occurs locally in your browser. No uploaded photographs leave your device.

## Shapes and two-piece-set mode

The original **15 × 20 portrait** uses all 300 pieces. There are also full-size landscape, square, 3:2 and 2:3 rectangles, panoramic formats, and smaller shapes with between 100 and 300 tiles.

In two-puzzle mode, select **Puzzle A** and **Puzzle B**, choose different photographs and shapes, and let the workshop generate both maps. Together, they may use **no more than 300 pieces**; the assignment solver guarantees that **no physical piece appears in both maps**. Unused pieces remain available for a later puzzle. Print both maps on separate pages, or download them individually.

## Offline use

Download the single HTML file (`index.html` or `workshop-v3.html`) and open it in a browser. All assets are embedded, including the authentic pieces and original example. There is no required build process.

## Authentic original puzzle data

The app embeds **all 300 original identifying symbols** and **300 matching grayscale tile patterns**, extracted from the owner's original Adobe AIR installation disc. It also reproduces the supplied original Mona Lisa assembly map with the original physical piece IDs and orientations.

For new photographs, an independently implemented constrained optimization assigns and rotates the original tiles. Results may differ from the historical software but remain physically buildable with the identified set.

## Publication

GitHub Pages serves the app from `index.html` on `main`. The latest versioned URL is `workshop-v3.html`; older `workshop-v2.html` requests redirect to v3.

## Testing

Automated headless Chromium tests cover desktop/mobile layouts, authentic sample loading, grayscale source rendering, automatic regeneration of 300-piece landscape and smaller puzzles, automatic paired 144-piece puzzles with **288 unique physical pieces**, zoom edits, icon maps, and JavaScript errors. Testing was performed on a desktop Chromium engine with an emulated mobile viewport, not on physical iPhone Safari. Assembling the map with actual physical pieces is the final validation.

## Rights and provenance

Independent preservation and compatibility project. Not an official Hasbro or Tenyo product. Ji Ga Zo trademarks, original symbol graphics, and shaded puzzle artwork belong to their respective owners. Original installers and disc images are not distributed here.
