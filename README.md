# Old Man Ji Ga Zo

A modern, self-contained, offline-capable browser companion for the **2010 Hasbro Ji Ga Zo physical puzzle**.

**Open the app:** https://udeudeude.github.io/Old-Man-JiGaZo/

**Versioned link (if Safari displays an older cached page):** https://udeudeude.github.io/Old-Man-JiGaZo/workshop-v2.html

The versioned link serves the same up-to-date application through a new file URL, bypassing cached copies of the original homepage. In Safari, Command + Option + R also reloads the page from its origin.

## Make one puzzle

1. Select **One puzzle** and choose a shape.
2. Import a photograph or use the original Mona Lisa example.
3. Adjust the crop using drag, pinch-to-zoom, mouse wheel, zoom slider (up to 800%), and the + / − buttons.
4. Press **Create my puzzle**.
5. View or save the original-symbol assembly map, preview the grayscale mosaic, or print the map.

The original **15 × 20 portrait (300 pieces)** is preserved. Additional layouts include:
- **20 × 15 landscape** (300 pieces)
- **15 × 15 square** (225 pieces)
- **18 × 12 landscape** / **12 × 18 portrait** (216 pieces)
- **20 × 10 panorama** / **10 × 20 tall** (200 pieces)
- Smaller square, portrait, and landscape shapes ranging from 100 to 150 pieces

The software chooses an optimal **subset** for layouts using fewer than 300 pieces. Unused physical pieces stay unused.

## Make two smaller puzzles at once

1. Select **Two smaller puzzles, with different photos**.
2. Choose **Puzzle A**, its layout, photograph, and crop.
3. Choose **Puzzle B**, its layout, photograph, and crop.
4. Select **Create both puzzles**.
5. Switch between A and B to view and save their distinct symbol maps and mosaic previews, or select **Print map(s)** to print both maps on separate pages.

The two layouts may be different shapes, as long as they require **300 pieces or fewer in total**. Their combined placement is optimized together so **no physical piece appears in both maps**. Examples include two **10 × 15** puzzles (150 + 150), two **12 × 12** squares (144 + 144, leaving 12 unused), and a 10 × 15 portrait plus a 12 × 10 landscape (150 + 120).

## Save projects and work offline

**Save project** records the one- or two-puzzle configuration, each photograph, the framing and settings, and the assembly maps. **Open project** supports both the new format and projects saved by the original version of this replacement app.

Download `index.html` from the repository to use the app offline. It includes all symbols, gray tiles, and sample imagery, and sends no photographs to a server.

## Compatibility and provenance

- Includes the **300 authentic original identifying symbols** and corresponding **300 grayscale puzzle-tile images**, recovered from the owner's original Adobe AIR disc.
- Uses the original 2010 Mona Lisa icon map, including the exact piece IDs and rotations.
- Includes the authentic physical pieces at most once per generated puzzle, and **at most once across a two-puzzle project**.
- The independent optimization algorithm can generate maps different from those made by the original software.
- This is an independent preservation/compatibility project, **not an official Hasbro or Tenyo product**. No rights to their trademarks or original artwork are claimed. The original installer is not distributed.

## Testing

Verified in Chromium with a full landscape assignment, a 144-piece subset, two simultaneous 150-piece maps (300 distinct physical pieces), unused-piece cases, separate printable maps, legacy project loading, round-trip project restoration, and desktop/mobile layouts. Physical assembly remains to be validated using the original puzzle pieces.
