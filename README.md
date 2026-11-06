# Old Man Ji Ga Zo

A modern, self-contained browser companion for the **Hasbro Ji Ga Zo 300-piece puzzle** (2010 edition).

**App:** https://udeudeude.github.io/Old-Man-JiGaZo/

## Use

1. Open the app in a current browser on a phone, tablet, or computer.
2. Start with the original Mona Lisa sample, or choose a photograph.
3. Adjust the crop and image settings, then select **Create my puzzle**. Use the photo's **+ / −** buttons, zoom slider (up to 800%), mouse-wheel scrolling, or pinch gestures to zoom. Drag to reframe. Zooming keeps the selected point under your cursor or fingers.
4. Use the **symbol map** to arrange your 300 physical pieces, rotating each one to match its printed icon.
5. Print the map, save PNG maps/previews, or save a project to continue later.

All processing happens locally in your browser. Photographs are not sent to a server.

## Authentic puzzle compatibility

- The app contains the **300 actual symbol images** and corresponding **300 grayscale tile images** recovered from the owner's original Adobe AIR installation disc.
- It matches the Hasbro edition's **15-column by 20-row** assembly grid.
- Each physical piece appears **exactly once** in every newly generated assembly map.
- The original Mona Lisa example is reproduced using its exact supplied piece identities and orientations.
- For new photographs, the mosaic optimization algorithm is independently implemented; its choices can differ from the legacy application.

## Run without internet

Download `index.html` and open the file in a modern browser. The piece artwork and sample image are embedded, so no other files or external services are required.

## Publishing with GitHub Pages

If this site's link is not yet active, in **Settings → Pages** choose **Deploy from a branch**, then select **main** and **/(root)**, and save. The site is served directly from `index.html`.

## Provenance and rights

This is an independent preservation/compatibility project, **not an official Hasbro or Tenyo product**. Ji Ga Zo, the original symbols, tile artwork, and sample imagery are associated with their respective owners. Their inclusion is for compatibility with the physical puzzle; no rights to the original artwork or trademarks are claimed. The original Adobe AIR installer and CD are not distributed in this repository.

## Testing

The source has been exercised in desktop and mobile browser layouts and checked against the original Mona Lisa map. Physical assembly should still be validated against the user's actual pieces.
