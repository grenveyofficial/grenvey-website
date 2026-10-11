# Grenvey Studio — Packaging Artwork MVP

A browser-based, standalone 2D packaging artwork editor prototype.

## Run it
Open `index.html` in a modern browser. No build step or server is required for the current MVP.

## Included
- Flat label, bottle wrap, jar wrap, can wrap and stand-up pouch presets
- Physical canvas dimensions in millimetres
- Full-wrap width estimate using `π × diameter + overlap`
- Editable text, rectangles, circles, lines and imported images
- Object positioning/sizing, fill colours, opacity, layer ordering, visibility and lock toggles
- Grid, rulers, bleed and safe-area guides
- Starter templates, duplicate/delete and alignment controls
- Save/load project JSON
- SVG export and browser print dialog for PDF

## Current limitations
This is an early MVP, not a validated prepress system. Wrap calculations assume a circular cross-section and do not account for taper, panel geometry, seam placement or supplier-specific dielines. Confirm dimensions and bleed requirements with your printer. Text layout, fonts, imported-image embedding, colour profiles, CMYK conversion, dielines, 3D mockups and production PDF validation need further work. The print/PDF output uses the browser's print engine; verify physical scale and page settings before production.

## Next steps
1. Test common bottle/jar/can/pouch dimensions and fix print scale.
2. Add project metadata, autosave and robust image asset handling.
3. Improve text editing, snapping, grouping and multi-selection.
4. Add proper dieline templates and a validated PDF export pipeline.
